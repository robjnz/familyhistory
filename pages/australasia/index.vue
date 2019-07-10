<template>
<section main>
  <b-container>
    <b-row>
    <h1 class="title-color">Australasia</h1>
  <div>

<b-button-group>
    <australasiajewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Allambe Memorial Park">
  <p class="title-color">
    Allambe Memorial park burial records.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2NJaaHn" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Family History SA">
  <p class="title-color">
    South Australian ancestry records.
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2w1EYu0" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "National Archives">
  <p class="title-color">

    National Archives holds many records about your ancestors.
    <br>
    <br>
    </p>
    <b-button href="http://bit.ly/2I46PPj" target="_blank" variant="info">open</b-button>
</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "South Australian family history">
  <p class="title-color">
    Resource for South Australian family history information.
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2rgXJ7a" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">

    <br>
    <br>
    <br>
  </p>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">


    <br>
    <br>
    </p>
</b-card>
</b-card-group>
<hr class="hr">

  <h1 class="title-color">New Zealand</h1>

<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Archway">
  <p class="title-color">
    Government records from Auckland, Christchurch, Dunedin and Wellington.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2HJxCwH" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Auckland Cemeteries">
  <p class="title-color">
    Burial and cremation record.
    <br>


  </p>
  <b-button href="http://bit.ly/2Kwl25S" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Birth Death & Marriages">
  <p class="title-color">

    Online records.
    <br>
    <br>
    </p>
    <b-button href="http://bit.ly/2JzPBrF" target="_blank" variant="info">open</b-button>
</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Companies Register">
  <p class="title-color">
    Companies Register.
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2FAOF2j" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Gazette">
  <p class="title-color">
    Search the gazette 1993 - 2017.
    <br>
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/2Kvu3vP" target="_blank" variant="info">open</b-button>


</b-card>

<b-card bg-variant="dark" text-variant="white" title= "New Zealand National Archives">
  <p class="title-color">
    New Zealand national archives.

    <br>
    <br>
    </p>
        <b-button href="http://bit.ly/2xItUAd" target="_blank" variant="info">open</b-button>

</b-card>
</b-card-group>



  </div>
  </b-row>
</b-container>
</section>
</template>


<style>


</style>

<script>
import australasiajewish from '@/components/buttons/australasiajewish'


export default {
  head () {
    return {
      titleTemplate: '%s Australasia',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Australia & New Zealand of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    australasiajewish,

  }
}
</script>
