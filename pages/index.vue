<template>
<section show class="showcase">
    <b-container>
 <b-row class="text-center">
    <b-col></b-col>
    <b-col >
      <section class="header">
  <h1>Family History On-Line Resourses</h1>
  </section>
    </b-col>
    <b-col></b-col>
  </b-row>

    </b-container>
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
.intro{
  margin-left : 20px;
  margin-right: 900px;
  margin-top  : 50px;
  padding-left: 30px;
  color       : ghostwhite;
  font-family : Roboto;
  }

  .alert{
  margin-left : 20px;
  margin-right: 1000px;
  margin-top  : 1px;
  padding-left: 30px;
  color       : #171718;
  font-family : Damion;
  }

.header h1{
      font-size          : 50px;
      color              : red;
      line-height        : 1.3;
      position           : relative;
      animation          : heading;
      animation-duration : 5s;
      animation-fill-mode: forwards;
}

@keyframes heading {
0% {top: -40px}
100% {top: 375px}

}


</style>

<script>


export default {

  components: {

}
}
</script>
