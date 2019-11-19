<template>
<section main>
  <b-container>


  <div>
 <h1 class="title-color">General Resourses</h1>

<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Ancestry" align="center">
  <p class="title-color">
    Largest genealogy website Sometimes available free in local libraries.
    <br>
    <br>
  </p>
  <b-button href="https://ancstry.me/2jrZviB" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Billion Graves" align="center">
  <p class="title-color">
    Searchable cemetery records around the world.
    <br>
    <br>
  </p>
 <b-button href="http://bit.ly/2I6KSPz" target="_blank" variant="info">open</b-button>

</b-card>


<b-card bg-variant="dark" text-variant="white" title= "Family Search" align="center">
  <p class="title-color">
Free access to Mormons records.
<br>
    <br>
    <br>
    </p>
      <b-button href="http://bit.ly/3442Qd1" target="_blank" variant="info">open</b-button>

</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Find A Grave" align="center">
  <p class="title-color">
      Searchable cemetery records around the world.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2I5p6M2" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Find My Past" align="center">
  <p class="title-color">
    Searchable Genealogy Database.
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2IaI3wT" target="_blank" variant="info">open</b-button>

</b-card>


<b-card bg-variant="dark" text-variant="white" title= "Family Search" align="center">
  <p class="title-color">
Free access to Mormons records.
<br>
    <br>
    <br>
    </p>
      <b-button href="http://bit.ly/3442Qd1" target="_blank" variant="info">open</b-button>

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
      titleTemplate: '%s General Resourses',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    canadajewish,

  }
}
</script>



