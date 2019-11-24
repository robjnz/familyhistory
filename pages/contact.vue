<template>
<section>
  <b-container>

      <div>

        <h1 class="title-color">Contact Me </h1>

  <br><br>

<b-embed
    type   = "iframe"
    aspect = "16by9"
    src    = "https://docs.google.com/forms/d/e/1FAIpQLSfGapXnWx7u_vQ7CogtXbGOnBuaxckE63zjrbdTOZUveVZePQ/viewform?embedded=true" width = "640" height = "1265" frameborder = "0" marginheight = "0" marginwidth = "0">Loading…"
    allowfullscreen
  ></b-embed>
      </div>

</b-container>
</section>
</template>

<style>
.hr {

    background  : #FFCB31;
    margin-left : auto;
    margin-right: auto;
    height      : 7px;


}
</style>

<script>






export default {
  head () {
    return {
      titleTemplate: '%s Contact',
      meta         : [
        { hid: 'description', name: 'description', content: 'contact me ' }
      ]
    }
    },
    components: {


  }
}
</script>



