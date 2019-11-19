<template>
<section main>
  <b-container>


  <div>
  <h1 class="title-color">Jewish General Resourses</h1>

<b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Jewish Cemeteries In Poland" align="center">
  <p class="title-color">
    Jewish cemeteries searchable database Poland.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/330R55R" target="_blank" variant="info">open</b-button>

</b-card>

  <b-card bg-variant="dark" text-variant="white" title= "Jewish Gem's Genealogy" align="center">
  <p class="title-color">
    Jewish geaneology blog.
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2pwUJXv" target="_blank" variant="info">open</b-button>
</b-card>




<b-card bg-variant="dark" text-variant="white" title= "Jewish Gen" align="center">
  <p class="title-color">
Free Jewish Genealogy Records & Resourses.
    <br>
    <br>
    </p>
      <b-button href="http://bit.ly/35rf1Bh" target="_blank" variant="info">open</b-button>

</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Routes To Roots" align="center">
  <p class="title-color">
      Family History guide to Jewish and civil records in Eastern Europe.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2JVIsk0" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Translate Hebrew" align="center">
  <p class="title-color">
    Translate Hebrew to English.
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2rn3G3j" target="_blank" variant="info">open</b-button>

</b-card>


<b-card bg-variant="dark" text-variant="white" title= "Virtual Shtetl" align="center">
  <p class="title-color">
Shtetl became a symbol of Jewish life before the Holocaust.
<br>
    <br>
    <br>
    </p>
      <b-button href="http://bit.ly/2QyNd9R" target="_blank" variant="info">open</b-button>

</b-card>

</b-card-group>


  </div>

</b-container>
</section>
</template>


<style>


</style>

<script>
import canadajewish from '@/components/buttons/canadajewish'


export default {
  head () {
    return {
      titleTemplate: '%s General Resourses',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    canadajewish,

  }
}
</script>



