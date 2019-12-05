<template>
<section main>
  <b-container>


  <div>
 <h1 class="title-color">Caribbean</h1>
<b-button-group>
    <caribbeanjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Barbados" align="center">
  <p class="title-color">
Barbados Genealogical Records
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2Ls7SZP" target="_blank" variant="info">open</b-button>
</b-card>
  <b-card bg-variant="dark" text-variant="white" title= "Barbados Family History" align="center">
  <p class="title-color">

Barbados Family History.
    <br>
    <br>
    </p>
        <b-button href="http://bit.ly/2PggG63" target="_blank" variant="info">open</b-button>


</b-card>




 <b-card bg-variant="dark" text-variant="white" title= "Bermuda Genealogy" align="center">
  <p class="title-color">
Family history for Bermuda.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2PeNSLm" target="_blank" variant="info">open</b-button>
</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Candoo" align="center">
  <p class="title-color">
Caribbean Resourses.
    <br><br>
    <br>
  </p>
  <b-button href="http://bit.ly/389OgTR" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Caribbean Gen" align="center">
  <p class="title-color">
 Caribbean Resourses.
    <br>
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/2Yi4aan" target="_blank" variant="info">open</b-button>


</b-card>


<b-card bg-variant="dark" text-variant="white" title= "Caribbean Family History Group" align="center">
  <p class="title-color">

Family History Group
    <br>
    <br>
    </p>
        <b-button href="http: //bit.ly/33TMFOO" target="_blank" variant="info">open</b-button>


</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Caribbean Family History" align="center">
  <p class="title-color">
Family history for Caribbean.
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/2Yum1ep" target="_blank" variant="info">open</b-button>


</b-card>


<b-card bg-variant="dark" text-variant="white" title= "Creole" align="center">
  <p class="title-color">
Creole & Barbados Genealogy.
    <br>
    <br>

  </p>
    <b-button href="http://bit.ly/35Yon7I" target="_blank" variant="info">open</b-button>


</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Cuban" align="center">
  <p class="title-color">

Cuban Family History
    <br>
    <br>
    </p>
        <b-button href="http://bit.ly/2LscpLA" target="_blank" variant="info">open</b-button>


</b-card>
</b-card-group>

<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Jamaican Family Search" align="center">
  <p class="title-color">
Family history for Jamaica, West Indies.
    <br><br>
    <br>
  </p>
  <b-button href="http://bit.ly/2RjnCC9" target="_blank" variant="info">open</b-button>
</b-card>



<b-card bg-variant="dark" text-variant="white" title= "The Jamaica Gleaner" align="center">
  <p class="title-color">
online database contains more than 970,000 historical pages from The Gleaner, dating back to 1834.
    <br>
  </p>
    <b-button href="http://bit.ly/2ORvqZX" target="_blank" variant="info">open</b-button>
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
import caribbeanjewish from '@/components/buttons/caribbeanjewish'


export default {
  head () {
    return {
      titleTemplate: '%s Caribbean',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Caribbean of birth, death, marriages, military records & burial records.' }
    ]
    }


    },
    components: {
    caribbeanjewish,

  }
  }
</script>


