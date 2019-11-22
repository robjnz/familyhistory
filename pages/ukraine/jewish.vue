<template>
<section main>
  <b-container>


  <div>
<h1 class="title-color">Ukraine</h1>
    <h2>Jewish Resources</h2>
<b-button-group>
    <ukrainejewish />
  </b-button-group>
  <br><br>
<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Ekaterinoslav" align="center">
  <p class="title-color">
    Commemorative Books of Ekaterinoslav Gubernia in russian.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2KLj9E1" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Dnepropetrovsk" align="center">
  <p class="title-color">
Jewishgen kehila links to Dnepropetrovsk.
    <br><br>
    <br>
  </p>
    <b-button href="http://bit.ly/2KHpyyE" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Dnepropetrovsk" align="center">
  <p class="title-color">
Memorial Book.
    <br><br>
    <br>
    </p>

    <b-button href="http://bit.ly/2KGvGar" target="_blank" variant="info">open</b-button>

</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Dnieper." align="center">
  <p class="title-color">
    Jewish community of the Dnieper cemetery records.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/37xezTU" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Elaterinoslav" align="center">
  <p class="title-color">
Jews resettled in Elaterinoslav in 1848 from Raseinai Community.
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/2FNmH3v" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Mogilev" align="center">
  <p class="title-color">
Jewish community of Mogilev (Dnipropetrovsk region).
    <br>
    <br>
  </p>
    <b-button href="http://bit.ly/2rqQ6vP" target="_blank" variant="info">open</b-button>

</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Mohyliv-Podilskyy" align="center">
  <p class="title-color">
    Jewish community of Mohyliv-Podilskyy.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2FOm2P0" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Russian & Ukrainian Family" align="center">
  <p class="title-color">
    searchable databases in Russian.
    <br>
    <br>
    </p>

    <b-button href="http://bit.ly/2w8fnQa" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Ukraine SIG" align="center">
  <p class="title-color">
      Russian Empire gubernias in Ukraine & Russia.
    <br>
  </p>
    <b-button href="http://bit.ly/2HT7zHs" target="_blank" variant="info">open</b-button>

</b-card>

</b-card-group>


  </div>
</b-container>
</section>
</template>


<style>


</style>

<script>
import ukrainejewish from '@/components/buttons/ukrainejewish'


export default {
  head () {
    return {
      titleTemplate: '%s Ukraine Jewish',
      meta         : [
        { hid: 'description', name: 'description', content: 'Genealogy information in Ukraine Jewish of birth, death, marriages, military records & burial records.' }
      ]
    }
    },
    components: {
    ukrainejewish,

  }
}
</script>
