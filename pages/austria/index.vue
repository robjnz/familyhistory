<template>
<section main>
  <b-container>


  <div>
 <h1 class="title-color">Austria</h1>
<b-button-group>
    <austriajewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Austrian State Archives" align="center">
  <p class="title-color">
    State archives.
    <br>
  </p>
  <b-button href="http://bit.ly/34XEQrF" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "GenTeam" align="center">
  <p class="title-color">
Austrian Databases & neighboring lands.

  </p>
      <b-button href="http://bit.ly/2Sw0RLL" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Vienna" align="center">
  <p class="title-color">
Tracing your Ancestors in Vienna.
    <br>
  </p>
    <b-button href="http://bit.ly/2SrGLCq" target="_blank" variant="info">open</b-button>

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
import austriajewish from '@/components/buttons/austriajewish'
import google from '@/components/google'


export default {
  head () {
    return {
      titleTemplate: '%s Austria',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Austria of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    austriajewish,
    google,

  }
}
</script>
