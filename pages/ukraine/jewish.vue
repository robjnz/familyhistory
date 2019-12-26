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



<b-card bg-variant="dark" text-variant="white" title= "Skala-Podilska" align="center">
  <p class="title-color">
      Jewish community of Mohyliv-Podilskyy.
    <br><br>
  </p>
    <b-button href="http://bit.ly/34s9FW4" target="_blank" variant="info">open</b-button>

</b-card>



  <b-card bg-variant="dark" text-variant="white" title= "Ukraine SIG" align="center">
  <p class="title-color">
      Russian Empire gubernias in Ukraine & Russia.
    <br><br>
  </p>
    <b-button href="http://bit.ly/2HT7zHs" target="_blank" variant="info">open</b-button>

</b-card>

</b-card-group>

<b-card-group deck
  class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Ukraine" align="center">
  <p class="title-color">
History of Jewish settlements in Ukraine can be traced back to the 8th century.
    <br>
    <br>
  </p>

  <b-button href="http://bit.ly/35H9neg" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">

    <br>
    <br>
    </p>
<!--
    <b-button href="http://bit.ly/2w8fnQa" target="_blank" variant="info">open</b-button>
-->
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "" align="center">
  <p class="title-color">

    <br>
    <br>
    </p>
<!--
    <b-button href="http://bit.ly/2w8fnQa" target="_blank" variant="info">open</b-button>
-->
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
import ukrainejewish from '@/components/buttons/ukrainejewish'
import google from '@/components/google'


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
    google,

  }
}
</script>
