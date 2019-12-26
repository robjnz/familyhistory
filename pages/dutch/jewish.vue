<template>
<section main>
  <b-container>


  <div>
 <h1 class="title-color">Dutch</h1>
 <h2>Jewish Resources</h2>
<b-button-group>
    <dutchjewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Ashkenazi Cemeteries" align="center">
  <p class="title-color">

Cemetery Records.
    </p>
        <b-button href="http://bit.ly/37byPcI" target="_blank" variant="info">open</b-button>

</b-card>
  <b-card bg-variant="dark" text-variant="white" title= "Dutch Jewry" align="center">
  <p class="title-color">
    Searchable Database.
    
  </p>
  <b-button href="http://bit.ly/2PYfwO6" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Joods Monument" align="center">
  <p class="title-color">

  Search The Holocaust Victims Momorial.
  </p>
    <b-button href="http://bit.ly/2Sr3Chj" target="_blank" variant="info">open</b-button>

</b-card>



</b-card-group>

<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Sephardic Gen" align="center">
  <p class="title-color">

Resources.
    </p>
        <b-button href="http://bit.ly/2EV62gi" target="_blank" variant="info">open</b-button>

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
import dutchjewish from '@/components/buttons/dutchjewish'
import google from '@/components/google'


export default {
  head () {
    return {
      titleTemplate: '%s Dutch',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Dutch jewish of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    dutchjewish,
    google,

  }
}
</script>
