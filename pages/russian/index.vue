<template>
<section main>
  <b-container>


  <div>
 <h1 class="title-color">Russian</h1>
<b-button-group>
    <russianjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "All Russian Family Tree" align="center">
  <p class="title-color">

    <br>
    <br>
  </p>

  <b-button href="http://bit.ly/2Dz1o6Q" target="_blank" variant="info">open</b-button>

</b-card>
<b-card bg-variant="dark" text-variant="white" title= "Cyrillic to Latin conversion" align="center">
  <p class="title-color">
Cyrillic to Latin conversion.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2we7uZz" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Forebears" align="center">
  <p class="title-color">
    Russia Genealogical Records
    <br>
    <br>
    </p>

    <b-button href="http://bit.ly/2OA2V33" target="_blank" variant="info">open</b-button>

  </b-card>
</b-card-group>

  <b-card-group deck
  class="mb-3">
 <b-card bg-variant="dark" text-variant="white" title= "Russian & Ukrainian Family" align="center">
  <p class="title-color">
    searchable databases in Russian.
    <br>
    <br>
    </p>

    <b-button href="http://bit.ly/2w8fnQa" target="_blank" variant="info">open</b-button>

</b-card>



<b-card bg-variant="dark" text-variant="white" title= "Russian Print and Cursive" align="center">
  <p class="title-color">

Converting Russian Print and Cursive
    <br>
    <br>
    </p>
      <b-button href="http://bit.ly/2KByKnY" target="_blank" variant="info">open</b-button>

</b-card>



 <b-card bg-variant="dark" text-variant="white" title= "Russian military memorial" align="center">
  <p class="title-color">
    Russian military memorial.
    <br>
    <br>
    </p>

    <b-button href="http://bit.ly/2IcNoUv" target="_blank" variant="info">open</b-button>

 </b-card>
</b-card-group>

  <b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Russian military awards" align="center">
  <p class="title-color">

Search Russian military awards.

    <br>
    <br>
    </p>
      <b-button href="http://bit.ly/2HRv8Rh" target="_blank" variant="info">open</b-button>

</b-card>


<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">


    <br>
    <br>
    </p>
    <!--
      <b-button href="http://bit.ly/2HRv8Rh" target="_blank" variant="info">open</b-button>
-->
</b-card>

  <b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">

    <br>
    <br>
  </p>
<!--
  <b-button href="http://bit.ly/2Dz1o6Q" target="_blank" variant="info">open</b-button>
-->
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
import russianjewish from '@/components/buttons/russianjewish'
import google from '@/components/google'


export default {
  head () {
    return {
      titleTemplate: '%s Russian',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in russian of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    russianjewish,
    google,

  }
}
</script>
