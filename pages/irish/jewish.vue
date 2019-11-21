<template>
<section main>
  <b-container>


  <div>
<h1 class="title-color">Ireland</h1>
    <h2>Jewish Resources</h2>
<b-button-group>
    <irishjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Irish Genealogical Society" align="center">
  <p class="title-color">
    Irish Jewish database contains info on people from the 1700.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2Daukln" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">

    <br>
    <br>
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




  </div>
</b-container>
</section>
</template>


<style>


</style>

<script>
import irishjewish from '@/components/buttons/irishjewish'


export default {
  head () {
    return {
      titleTemplate: '%s Irish Jewish',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Irish Jewish of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    irishjewish,

  }
}
</script>
