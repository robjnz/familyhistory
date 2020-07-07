
<template>
<section show class="showcase">
<b-container>
<b-row>
    <b-col>
    <img id="traveler1" src="/travelertwo.svg" alt="traveler"/>
    <img id="traveler2" src="/travelertwo.svg" alt="traveler"/>

  <h1 id="header">Family History <br>On-Line Resourses</h1>

<div class="text-right">

  <img class="plane3" id="plane3" src="/planegoldright.svg" alt="plane"/>
  <img class="plane2" id="plane2" src="/planegoldright.svg" alt="plane"/>
  <img class="plane1" id="plane1" src="/planegoldright.svg" alt="plane"/>

    <img class="treeman" id="treeman" src="/treeman.svg" alt="treeman"/>


  <img id="traveler" src="/travelertwo.svg" alt="traveler"/>
</div>
<div class="text-left">

  <h1 id="notes">Birth, School, War, Census, Emigration, Naturalisation, Death, Will & Cemeteries.</h1>

</div>

  </b-col>
  </b-row>

</b-container>


    <script>

  anime({
  targets   : '#plane1',
  translateX: [1000, -1500],
  duration  : 9999,
  easing    : 'easeInOutSine',

  });

  anime({
  targets   : '#plane2',
  translateX: [1000, -1500],
  duration  : 9999,
  delay     : 2000,
  easing    : 'easeInOutSine',

  });

  anime({
  targets   : '#plane3',
  translateX: [1000, -1500],
  duration  : 9999,
  delay     : 4000,
  easing    : 'easeInOutSine',

  });

  anime({
  targets   : '#notes',
  translateX: [-1500, 70],
  duration  : 9999,
  delay     : 3000,
  easing    : 'easeInOutSine',

  });

  anime({
  targets   : '#header',
  translateY: [-400, 200],
  duration  : 9999,
  delay     : 3000,
  easing    : 'easeInOutSine',

  });

  anime({
  targets   : '#traveler',
  translateX: [1400, 45],
  duration  : 9999,
  delay     : 3000,
  easing    : 'easeInOutSine',

  });

  anime({
  targets   : '#traveler1',
  translateX: [-1000, 130],
  duration  : 9999,
  delay     : 3000,
  easing    : 'easeInOutSine',

  });

  anime({
  targets   : '#traveler2',
  translateX: [1400, 375],
  duration  : 9999,
  delay     : 3000,
  easing    : 'easeInOutSine',

  });
anime({
  targets   : '#treeman',
  translateY: [400, 0],
  duration  : 9999,
  delay     : 3000,
  easing    : 'easeInOutSine',

  });

</script>
  </section>

</template>

<style scoped>
.showcase{
  background             : url(https://res.cloudinary.com/dzhbfdfa5/image/upload/v1562569145/religions_map_l4pc8f.png) no-repeat center center fixed;
  background-size        : cover;
  -webkit-background-size: cover;
  -moz-background-size   : cover;
  -o-background-size     : cover;
  height                 : 1000px;
  margin-top             : -75px;

}

#header{
font-size  : 50px;
color      : red;
line-height: 1.3;
position   : relative;
text-align : center;


}

.plane1 {
      position: relative;
      width   : 100px;
      height  : 100px;
}

.plane2{
      position: relative;
      width   : 100px;
      height  : 100px;
}

.plane3{
      position: relative;
      width   : 100px;
      height  : 100px;
}

#notes{
      font-size  : 30px;
      color      : blue;
      line-height: 1.3;
      position   : relative;
}
#traveler {
      position: relative;
      width   : 200px;
      height  : 200px;
}

#traveler1 {
      position: relative;
      width   : 100px;
      height  : 100px;
}
#traveler2 {
      position: relative;
      width   : 100px;
      height  : 100px;
}
#treeman{
      position: relative;
      width   : 150px;
      height  : 150px;
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
