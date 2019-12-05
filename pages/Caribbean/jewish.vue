<template>
<section main>
  <b-container>


  <div>
<h1 class="title-color">Caribbean</h1>
    <h2>Jewish Resources</h2>
<b-button-group>
    <caribbeanjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Jamaican Family Search" align="center">
  <p class="title-color">
Jewish Records.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2RpRQDo" target="_blank" variant="info">open</b-button>
</b-card>
  <b-card bg-variant="dark" text-variant="white" title= "Caribbean" align="center">
  <p class="title-color">
Sephardic Caribbean Resources.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2qnYQ8K" target="_blank" variant="info">open</b-button>
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
import caribbeanjewish from '@/components/buttons/caribbeanjewish'


export default {
  head () {
    return {
      titleTemplate: '%s Caribbean Jewish',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Caribbean Jewish of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    caribbeanjewish,

  }
}
</script>
