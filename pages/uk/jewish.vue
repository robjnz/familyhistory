<template>
<section>
  <b-container>

      <div>

        <h1 class="title-color">United Kingdom </h1>
        <h2>Jewish Resources</h2>
        <b-button-group>
    <jewishB />
  </b-button-group>
  <br><br>
  <b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= " AJEX Record of Honour" align="center">
  <p class="title-color">
    Database jewish men & women who served from 1939 to 1960.
  </p>
  <b-button href="http://bit.ly/2jX2orS" target="_blank" variant="info">open</b-button>
</b-card>



<b-card bg-variant="dark" text-variant="white" title= "JCR - United Kingdom" align="center">

  <p class="title-color">
    Database of jewish record in the United Kingdom.
    <br>
    </p>
    <b-button href="http://bit.ly/2GflEtg" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Jewish Chronical Archives" align="center">
  <p class="title-color">
    search original version of the JC, from 1841.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2jWAXhT" target="_blank" variant="info">open</b-button>
</b-card>
</b-card-group>

<b-card-group deck
      class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Jewish Free School" align="center">
  <p class="title-color">
    Jewish Free School Database 1856 to 1907.
    <br>
  </p>
  <b-button href="https://bit.ly/2KBEaAC" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Jewish London WW1." align="center">
  <p class="title-color">
    Jewish London WW1.
    <br><br>

  </p>
  <b-button href="http://bit.ly/2LrGkod" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Marriage Authorisation Records" align="center">
  <p class="title-color">

1880 to 1918.
  </p>
  <b-button href="http://bit.ly/2wC1AS8" target="_blank" variant="info">open</b-button>
</b-card>
</b-card-group>

<b-card-group deck
      class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Roll Of Honour" align="center">
  <p class="title-color">

    Jews who served in the British army during the first world war.
    <br>

    </p>
    <b-button href="http://bit.ly/320z8W1" target="_blank" variant="info">open</b-button>
</b-card>


<b-card bg-variant="dark" text-variant="white" title= "St Georges in the East" align="center">
  <p class="title-color">
    Jewish St Georges in the East Stepney
    <br>
  </p>
  <b-button href="http://bit.ly/2rFlBSX" target="_blank" variant="info">open</b-button>
</b-card>



<b-card bg-variant="dark" text-variant="white" title= "Pre 1850" align="center">
  <p class="title-color">
    Pre 1850 Anglo Jewry Database
    <br>
  </p>
  <b-button href="https://bit.ly/2KBFjIq" target="_blank" variant="info">open</b-button>
</b-card>
</b-card-group>

 <b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "1851" align="center">
  <p class="title-color">
    1851 Anglo Jewry Database
    <br>
  </p>
  <b-button href="https://bit.ly/3f0oGUE" target="_blank" variant="info">open</b-button>
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
        { hid: 'description', name: 'description', content: 'Jewish genealogy information in the britain united kingdom of birth, death, marriages, military records & a list of jewish cemeteries. ' }
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


