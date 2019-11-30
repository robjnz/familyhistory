<template>
<section main>
  <b-container>


  <div>
<h1 class="title-color">Russian</h1>
    <h2>Jewish Resources</h2>
<b-button-group>
    <russianjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Jewish Soldier" align="center">
  <p class="title-color">
Russian-Jewish Fallen Soldiers of World War I
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/34ypn28" target="_blank" variant="info">open</b-button>
</b-card>

  <b-card bg-variant="dark" text-variant="white" title= "Jewish Soldier" align="center">
  <p class="title-color">
Russian-Jewish Fallen Soldiers of World War 2
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2R6rG8s" target="_blank" variant="info">open</b-button>
</b-card>


<b-card bg-variant="dark" text-variant="white" title= "" align="center">
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
import russianjewish from '@/components/buttons/russianjewish'


export default {
  head () {
    return {
      titleTemplate: '%s Russian Jewish',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Russian Jewish of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    russianjewish,

  }
}
</script>
