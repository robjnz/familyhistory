<template>
<section main>
<b-container>


<div>
<h1 class="title-color">Dutch</h1>
<b-button-group>
    <dutchjewish />
</b-button-group>
<br><br>
<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "Amstadam" align="center">
<p class="title-color">
Amstadam Archives.

    </p>
    <b-button href="http://bit.ly/35XWZqP" target="_blank" variant="info">open</b-button>

    
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Dutch & Belgian archives" align="center">
<p class="title-color">
Search the genealogical database.

    </p>
    <b-button href="http://bit.ly/2QpaE3s" target="_blank" variant="info">open</b-button>

    
</b-card>
<b-card bg-variant="dark" text-variant="white" title= "Dutch roots" align="center"> 
<p class="title-color">
Dutch genealogy guide.
    
</p>
<b-button href="http://bit.ly/2SrGK17" target="_blank" variant="info">open</b-button>


</b-card>


</b-card-group>

<b-card-group deck
  class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "wie was wi" align="center">
<p class="title-color">
Dutch databases for family research.
</p>
<b-button href="http://bit.ly/2sc4OL3" target="_blank" variant="info">open</b-button>
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


<style scoped>


</style>

<script>
import dutchjewish from '@/components/buttons/dutchjewish'
import google from '@/components/google'



export default {
    head () {
    return {
    titleTemplate: '%s Dutch',
    meta         : [
    { hid: 'description', name: 'description', content: 'Genealogy information in Dutch of birth, death, marriages, military records & burial records.' }
    ]
    }


    },
    components: {
    dutchjewish,
    google,

    }
    }
</script>


