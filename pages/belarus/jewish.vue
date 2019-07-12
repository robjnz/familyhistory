<template>
<section main>
  <b-container>


  <div>
<h1 class="title-color">Belarus</h1>
    <h2>Jewish Resources</h2>
<b-button-group>
    <belarusjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Belarus Jewish Database">
  <p class="title-color">
    Miriam Weiner Archive Database for Belarus.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2KvCmrA" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Belarus Burial Records">
  <p class="title-color">
    Belarus Burial Records.
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2KzCh6b" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Belarus SIG">
  <p class="title-color">

    Jewish genealogy research in Grodno, Minsk, Mogilev and Vitebsk Gubernias.
    <br>
    <br>
    </p>
    <b-button href="http://bit.ly/2rhCJhz" target="_blank" variant="info">open</b-button>
</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Jewish Belarus">
  <p class="title-color">
    Jewish Belarus information.
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2KximVD" target="_blank" variant="info">open</b-button>
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




  </div>
</b-container>
</section>
</template>


<style>


</style>

<script>
import belarusjewish from '@/components/buttons/belarusjewish'


export default {
  head () {
    return {
      titleTemplate: '%s Belarus Jewish',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Belarus Jewish of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    belarusjewish,

  }
}
</script>
