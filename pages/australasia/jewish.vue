<template>
<section main>
  <b-container>

  <div>
    <h1 class="title-color">Australasia</h1>
    <h2>Jewish Resources</h2>

<b-button-group>
    <australasiajewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Australian Jewish Genealogical Society" align="center">
  <p class="title-color">
    Jewish Genealogical Society, New South Wales, Northern Territory and Queensland.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2rjNUpk" target="_blank" variant="info">open</b-button>
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
  <h2>Jewish Resources</h2>

<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Jewish Burial Database" align="center">
  <p class="title-color">
    The Beverley Davis Burial Database.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2Xlfsx4" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">
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

  </div>

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
      titleTemplate: '%s Australasia Jewish',
      meta         : [
        { hid: 'description', name: 'description', content: 'Jewish Genealogy information in the Australia & New zealand of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    australasiajewish,

  }
}
</script>
