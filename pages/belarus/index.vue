<template>
<section main>
  <b-container>


  <div>
 <h1 class="title-color">Belarus</h1>
<b-button-group>
    <belarusjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Belarus State Archives" align="center">
  <p class="title-color">
    State archives.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2FFJDBp" target="_blank" variant="info">open</b-button>
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
<section>
    <br><br>
    <google />
<br><br>
</section>

  </div>

</b-container>
</section>
</template>


<style>


</style>

<script>
import belarusjewish from '@/components/buttons/belarusjewish'
import google from '@/components/google'


export default {
  head () {
    return {
      titleTemplate: '%s Belarus',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Belarus of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    belarusjewish,
    google,

  }
}
</script>
