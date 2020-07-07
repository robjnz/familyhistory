
<template>
  <section main>
  
  <div>
   <b-container>
  <b-row>
    
    <h1> Family History On-Line Resourses</h1>
  <br />
  <h3>Birth, School, Marriage, War, Census, Emigration, Naturalisation & Death Records.</h3>
    
  </b-row>

</b-container>
    
  </div>

<div>
  <b-card
    overlay
    img-src="https://res.cloudinary.com/dzhbfdfa5/image/upload/v1562569145/religions_map_l4pc8f.png"
    img-alt="Card Image"
    text-variant="white"
    title="Image Overlay"
    sub-title=""
  >
    <b-card-text>
     .
    </b-card-text>
  </b-card>
</div>
  </section>
</template>

<style scoped>

#header{
font-size  : 50px;
color      : red;
line-height: 1.3;
position   : relative;
text-align : center;
}



</style>

<script>


export default {
  head () {
    return {
      script: [

        {scr: 'https: //cdn.jsdelivr.net/npm/gsap@3.0.4/dist/gsap.min.js'},
        {src: 'https://cdn.jsdelivr.net/npm/jquery@3.4.1/dist/jquery.min.js' },
        {src: 'https://cdn.jsdelivr.net/npm/animejs@3.1.0/lib/anime.min.js'}

      ],
      link: [
        { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css?family=Roboto&display=swap' },
        { rel: 'stylesheet', href: 'https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css'},


      ]
    }
  },
  components: {

}
}

</script>
