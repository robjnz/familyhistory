<template>
<section main>
  <b-container>


  <div>
 <h1 class="title-color">Canada</h1>
 <h2>Jewish Resources</h2>
<b-button-group>
    <canadajewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Canadian Jewish Heritage Network" align="center">
  <p class="title-color">
    Searchable Database.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2FI0u6Y" target="_blank" variant="info">open</b-button>
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
import canadajewish from '@/components/buttons/canadajewish'


export default {
  head () {
    return {
      titleTemplate: '%s Canada',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Canada jewish of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    canadajewish,

  }
}
</script>
