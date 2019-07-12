<template>
<section main>
  <b-container>

  <div>
    <h1 class="title-color">United Kingdom</h1>

<b-button-group>
    <jewishB />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "B.M.D">
  <p class="title-color">
    Free birth marriages and death index from 1837.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2IguCfJ" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "British newspaper archive">
  <p class="title-color">
    British newspaper archive from the 1700s.
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2IeM6t0" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Companies House">
  <p class="title-color">

    Free search the register of Companies House for directors.
    <br>
    <br>
    </p>
    <b-button href="http://bit.ly/2Xlmdz9" target="_blank" variant="info">open</b-button>
</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">

  <b-card bg-variant="dark" text-variant="white" title= "National archives">
  <p class="title-color">
    National archives.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2Xlfsx4" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "RAF">
  <p class="title-color">
    Casualty Cards & Muster Roll from April 1918.
    <br>


  </p>
  <b-button href="http://bit.ly/2rGVfQJ" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "The London Gazette">
  <p class="title-color">

    The Gazette is the UK’s official public record.
    <br>
    <br>
    </p>
    <b-button href="http://bit.ly/2Kio1On" target="_blank" variant="info">open</b-button>
</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Will and Probate">
  <p class="title-color">
    Will and Probate records 1858 to present Day.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2GfeWTV" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "War Graves Commission">
<p class="title-color">
    The 1.7 million men and women of the Commonwealth forces who died in the First and Second World Wars.
    <br>

  </p>
  <b-button href="http://bit.ly/2L2exrF" target="_blank" variant="info">open</b-button>
</b-card>


<b-card bg-variant="dark" text-variant="white" title= "1939 Register">
<p class="title-color">
    1939 Register also avaliable on Ancestry.
    <br>
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2IjAKzA" target="_blank" variant="info">open</b-button>
</b-card>

</b-card-group>
<b-card-group deck
      class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "192">
  <p class="title-color">
    Current electoral roll.
    <br>
    </p>
    <b-button href="http://bit.ly/2FPDJAN" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">
    <br>
    <br>
  </p>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">
    <br>
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
import jewishB from '@/components/buttons/jewishB'


export default {
  head () {
    return {
      titleTemplate: '%s uk',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in the britain united kingdom of birth, death, marriages, military records.' }
      ]
    }
    },
    components: {
    jewishB,

  }
}
</script>
