<template>
<section main>
  <b-container>


  <div>
  <h1 class="title-color">Ukraine</h1>
<b-button-group>
    <ukrainejewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Dnipropetrovsk" align="center">
  <p class="title-color">
State Archives of Dnipropetrovsk Region.
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/34cy2Hl" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Russian & Ukrainian Family" align="center">
  <p class="title-color">
    searchable databases in Russian.
    <br>
    <br>
    </p>

    <b-button href="http://bit.ly/2w8fnQa" target="_blank" variant="info">open</b-button>

</b-card>
  <b-card bg-variant="dark" text-variant="white" title= "Ukraine" align="center">
  <p class="title-color">
    State Archival Service of Ukraine.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2pDizAW" target="_blank" variant="info">open</b-button>
</b-card>


</b-card-group>

<b-card-group deck
  class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Ukrainian residents" align="center">
  <p class="title-color">
Database of the Ukrainian residents
born between 1650 and 1920
    <br>
    </p>
  <b-button href="http://bit.ly/33c5lJh" target="_blank" variant="info">open</b-button>

</b-card>


<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">

    <br>
    <br>
    </p>
<!--
    <b-button href="http://bit.ly/2w8fnQa" target="_blank" variant="info">open</b-button>
-->
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">

    <br>
    <br>
    </p>
<!--
    <b-button href="http://bit.ly/2w8fnQa" target="_blank" variant="info">open</b-button>
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
import ukrainejewish from '@/components/buttons/ukrainejewish'
import google from '@/components/google'


export default {
  head () {
    return {
      titleTemplate: '%s Ukraine',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Ukraine of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    ukrainejewish,
    google,

  }
}
</script>
