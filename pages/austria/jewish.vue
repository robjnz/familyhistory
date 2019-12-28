<template>
<section main>
  <b-container>


  <div>
<h1 class="title-color">Austria</h1>
    <h2>Jewish Resources</h2>
<b-button-group>
    <austriajewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Austrian Heraldic-Genealogical Society" align="center">
  <p class="title-color">
  Search Cemetery Database & Other Resources.
  </p>
  <b-button href="http://bit.ly/2tecfRJ" target="_blank" variant="info">open</b-button>
</b-card>

  <b-card bg-variant="dark" text-variant="white" title= "Jewish Cemeteries" align="center">
  <p class="title-color">
    <br>
  Search Cemetery Database.
    <br><br>
  </p>
  <b-button href="http://bit.ly/2Q2Vn9L" target="_blank" variant="info">open</b-button>
</b-card>


<b-card bg-variant="dark" text-variant="white" title= "Sephardic Gen" align="center">
  <p class="title-color">
    <br>
 Turkish Jewish Community of Vienna <br>1788-1818.
  </p>
  <b-button href="http://bit.ly/2tecfRJ" target="_blank" variant="info">open</b-button>
</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Sephardic Gen" align="center">
  <p class="title-color">
Turkish jewish Comunity of Vienna <br>Births 1845-1938.
    
    </p>
    <b-button href="http://bit.ly/2EW7Ndc" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Sephardic Gen" align="center">
  <p class="title-color">
Turkish Jewish Comunity of Vienna<br> Weddings 1845-1938.
    
    </p>
    <b-button href="http://bit.ly/37mojPX" target="_blank" variant="info">open</b-button>
</b-card>


  <b-card bg-variant="dark" text-variant="white" title= "Zentral Friedhof Cemetery Vienna" align="center">
  <p class="title-color">
  Search Cemetery Database.
    
  </p>
  <b-button href="http://bit.ly/2Q2Vn9L" target="_blank" variant="info">open</b-button>
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
import austriajewish from '@/components/buttons/austriajewish'
import google from '@/components/google'


export default {
  head () {
    return {
      titleTemplate: '%s Austria Jewish',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Austria Jewish of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    austriajewish,
    google,

  }
}
</script>
