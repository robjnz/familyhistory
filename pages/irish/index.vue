<template>
<section main>
  <b-container>


  <div>
 <h1 class="title-color">Ireland</h1>
<b-button-group>
    <irishjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Census of Ireland" align="center">
  <p class="title-color">
Census of Ireland 1901 & 1911
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/2QEr9dP" target="_blank" variant="info">open</b-button>

</b-card>
  <b-card bg-variant="dark" text-variant="white" title= "Irish Genealogy" align="center">
  <p class="title-color">
    Search family history records.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2pDizAW" target="_blank" variant="info">open</b-button>
</b-card>



<b-card bg-variant="dark" text-variant="white" title= "Irish Genealogy Toolkit" align="center">
  <p class="title-color">
Guide to finding Irish ancestors.

    <br>
    <br>
    </p>
      <b-button href="http://bit.ly/2QPwfnR" target="_blank" variant="info">open</b-button>

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
      titleTemplate: '%s Ireland',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Ireland of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    irishjewish,

  }
}
</script>
