<template>
<section>
  <b-container>
    <b-row>
      <div>

        <h1 class="title-color">United Kingdom </h1>
        <h2>Jewish Resources</h2>
        <b-button-group>
    <jewishB />
  </b-button-group>
  <br><br>
  <b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= " AJEX Record of Honour">
  <p class="title-color">
    Database jewish men & women who served from 1939 to 1960.
  </p>
  <b-button href="http://bit.ly/2jX2orS" target="_blank" variant="info">open</b-button>
</b-card>



<b-card bg-variant="dark" text-variant="white" title= "JCR - United Kingdom">

  <p class="title-color">
    Database of jewish record in the United Kingdom.
    <br>
    </p>
    <b-button href="http://bit.ly/2GflEtg" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Jewish Chronical Archives">
  <p class="title-color">
    search original version of the JC, from 1841.
    <br>
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2jWAXhT" target="_blank" variant="info">open</b-button>
</b-card>
</b-card-group>

<b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Jewish London WW1.">
  <p class="title-color">
    Jewish London WW1.
    <br><br><br>

  </p>
  <b-button href="http://bit.ly/2LrGkod" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Marriage Authorisation Records">
  <p class="title-color">

1880 to 1918.
  </p>
  <b-button href="http://bit.ly/2wC1AS8" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Roll Of Honour">
  <p class="title-color">

    Jews who served in the British army during the first world war.
    <br>
    <br>
    </p>
    <b-button href="http://bit.ly/320z8W1" target="_blank" variant="info">open</b-button>
</b-card>
</b-card-group>

<b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "St Georges in the East">
  <p class="title-color">
    Jewish St Georges in the East Stepney
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2rFlBSX" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">
    <br>
    <br>
  </p>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">
    <br>
    <br>
    <br>
  </p>
</b-card>
</b-card-group>

<hr class="hr">
<br>
<h2>Jewish Cemeteries</h2>
<br>

<adath />
<federation />
<liberal />
<united />
<western />
<br><br>

      </div>
    </b-row>
</b-container>
</section>
</template>

<style>
.hr {

    background  : #FFCB31;
    margin-left : auto;
    margin-right: auto;
    height      : 7px;


}
</style>

<script>
import jewishB from '@/components/buttons/jewishB'
import adath from '@/pages/uk/adath'
import federation from '@/pages/uk/federation'
import liberal from '@/pages/uk/liberal'
import united from '@/pages/uk/united'
import western from '@/pages/uk/western'




export default {
  head () {
    return {
      titleTemplate: '%s Jewish uk',
      meta         : [
        { hid: 'description', name: 'description', content: 'usefull computer software worth looking at, freeware and paid versions. ' }
      ]
    }
    },
    components: {
    jewishB,
    adath,
    federation,
    liberal,
    united,
    western,

  }
}
</script>


