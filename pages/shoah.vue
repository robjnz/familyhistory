<template>
<section>
  <b-container>
    <b-row>
      <div>

        <h1 class="title-color">Shoah</h1>
        <h2>Holocaust Resources</h2>

  <br>
  <b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= " Auschwitz">
  <p class="title-color">
    Auschwitz prisoners database.
  </p>
  <b-button href="http://bit.ly/2JIO7ts" target="_blank" variant="info">open</b-button>
</b-card>



<b-card bg-variant="dark" text-variant="white" title= "Austrian & Galisian">

  <p class="title-color">
    Austrian & Galisian Victims of the Holocaust.
    <br>
    </p>
    <b-button href="http://bit.ly/2I4pkTt" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Concentration Camps">
  <p class="title-color">
    Concentration Camps list.
    <br>

  </p>
  <b-button href="http://bit.ly/2Jv5v6D" target="_blank" variant="info">open</b-button>
</b-card>
</b-card-group>

<b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "French Deportations.">
  <p class="title-color">
    Memorial de la shoah deportation records
    <br><br>

  </p>
  <b-button href="http://bit.ly/2HFElvB" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Holocaust Database">
  <p class="title-color">

JewishGen holocaust database contains more than 2.75 million entries.
  </p>
  <b-button href="http://bit.ly/2rcyjaR" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Memorial Books">
  <p class="title-color">

    Victims of the Persecution under the National Socialist in Germany 1933 - 1945.
    <br>

    </p>
    <b-button href="http://bit.ly/2w9ISBm" target="_blank" variant="info">open</b-button>
</b-card>
</b-card-group>

<b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "International tracing Service">
  <p class="title-color">
    Archive center for documenting persecution and the liberated survivors.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2XxM9mv" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Survivors and Victims">
  <p class="title-color">
    USA Holocaust database contains more than 270,000 records
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/2JLIKd0" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Yad Vashem">
  <p class="title-color">
    The central database of shoah victims.
    <br>
    
  </p>
  <b-button href="http://bit.ly/2Jm04Iw" target="_blank" variant="info">open</b-button>

</b-card>
</b-card-group>

<hr class="hr">
<br>
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://giphy.com/embed/k5AJKN45cSnny"
          allowfullscreen
  ></b-embed>
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
      titleTemplate: '%s Shoah',
      meta         : [
        { hid: 'description', name: 'description', content: 'La shoah Holocaust Resources, Auschwitz, French Deportations and International tracing sevices. ' }
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


