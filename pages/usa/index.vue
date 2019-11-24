<template>
<section main>
  <b-container>


  <div>
  <h1 class="title-color">United States Of America</h1>
<b-button-group>
    <usajewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "National archives" align="center">
  <p class="title-color">
National archives.
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/2L79gPt" target="_blank" variant="info">open</b-button>

</b-card>
  <b-card bg-variant="dark" text-variant="white" title= "War Graves" align="center">
  <p class="title-color">
    ABMC memorializations database.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2Ip6h3b" target="_blank" variant="info">open</b-button>
</b-card>



<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">

    </p>

</b-card>

</b-card-group>

  <h2 class="asian">New York</h2>

<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Brooklyn Genealogy" align="center">
  <p class="title-color">
Brooklyn Genealogy.
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/2wNjGkf" target="_blank" variant="info">open</b-button>

</b-card>
  <b-card bg-variant="dark" text-variant="white" title= "New York Passenger" align="center">
  <p class="title-color">
    New York Passenger Lists 1820-1897.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2QMADny" target="_blank" variant="info">open</b-button>
</b-card>



<b-card bg-variant="dark" text-variant="white" title= "Ellis Island" align="center">
  <p class="title-color">
Searchable databases port of New York from 1892 to 1957.
    </p>
  <b-button href="http://bit.ly/2rLhCUW" target="_blank" variant="info">open</b-button>

</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "New York Records" align="center">
  <p class="title-color">
New York Records databases run by the Italian Genealogical Group.
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/2XJ6wPc" target="_blank" variant="info">open</b-button>

</b-card>
  <b-card bg-variant="dark" text-variant="white" title= "NYC Marriage Index" align="center">
  <p class="title-color">
Searchable database New York city marriages 1950-2017.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2wOl8mA" target="_blank" variant="info">open</b-button>
</b-card>



<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">

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
import usajewish from '@/components/buttons/usajewish'


export default {
  head () {
    return {
      titleTemplate: '%s USA',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in United States Of America USA of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    usajewish,

  }
}
</script>
