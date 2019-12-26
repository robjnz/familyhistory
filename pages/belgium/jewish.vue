<template>
<section main>
  <b-container>


  <div>
<h1 class="title-color">Belgium</h1>
    <h2>Jewish Resources</h2>
<b-button-group>
    <belgiumjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">
    
    <br>
    <br>
  </p>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">
  
  </p>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">

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
import belgiumjewish from '@/components/buttons/belgiumjewish'
import google from '@/components/google'


export default {
  head () {
    return {
      titleTemplate: '%s Belgium Jewish',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Belgium Jewish of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    belgiumjewish,
    google,

  }
}
</script>
