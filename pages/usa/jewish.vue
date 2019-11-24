<template>
<section>
  <b-container>

      <div>

        <h1 class="title-color">United States Of America </h1>
        <h2>Jewish Resources</h2>
        <b-button-group>
    <usajewish />
  </b-button-group>
  <br><br>
    <h2 class="asian">New York</h2>
  <b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= " Jewish Genealogical Society" align="center">
  <p class="title-color">
    Jewish Genealogical Society of New York.

  </p>
  <b-button href="http://bit.ly/2rO6cis" target="_blank" variant="info">open</b-button>
</b-card>



<b-card bg-variant="dark" text-variant="white" title= "" align="center">

  <p class="title-color">

    <br>
    </p>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">

    <br>
    <br>
  </p>
</b-card>
</b-card-group>



<hr class="hr">
<br>
<h2>Jewish Cemeteries</h2>
<br>

<newyork />
<br><br>

      </div>

</b-container>
</section>
</template>

<style>
.hr {

    background  : #FFCB31;
    margin-left : auto;
    margin-right: auto;
    height      : 7px;


}
</style>

<script>
import usajewish from '@/components/buttons/usajewish'
import newyork from '@/pages/usa/Cemeteries/newyork'





export default {
  head () {
    return {
      titleTemplate: '%s Jewish USA',
      meta         : [
        { hid: 'description', name: 'description', content: 'Jewish genealogy information in United States Of America  New York of birth, death, marriages, military records & jewish cemeteries. ' }
      ]
    }
    },
    components: {
    usajewish,
    newyork,

  }
}
</script>


