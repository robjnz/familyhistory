<template>
<section main>
  <b-container>


  <div>
 <h1 class="title-color">Belgium</h1>
<b-button-group>
    <belgiumjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Belgium Ancestry" align="center">
  <p class="title-color">

Resources.
    
    </p>
        <b-button href="http://bit.ly/2ZAAYfv" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Belgium Genealogy" align="center">
  <p class="title-color">
    Resources.
    
  </p>
  <b-button href="http://bit.ly/2Mx0ZH1" target="_blank" variant="info">open</b-button>
</b-card>
  <b-card bg-variant="dark" text-variant="white" title= "Belgium State Archives" align="center">
  <p class="title-color">
    State archives.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/37aGuHZ" target="_blank" variant="info">open</b-button>
</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Surname Search" align="center">
  <p class="title-color">

  Belgium Databases.
  </p>
    <b-button href="http://bit.ly/2Qk3Ioq" target="_blank" variant="info">open</b-button>

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
      titleTemplate: '%s Belgium',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Belgium of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    belgiumjewish,
    google,

  }
}
</script>
