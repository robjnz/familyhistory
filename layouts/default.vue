<template>
  <div>
    <TheHeader/>
    <TheFooter />
    <main class="main-content">
      <nuxt />
    </main>
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader/TheHeader'
import TheFooter from '@/components/TheFooter/TheFooter'
import NavBar from '@/components/TheHeader/NavBar'


export default {
  components: {
    TheHeader,
    TheFooter,
    NavBar,
  }
}
</script>

<style>
*{
box-sizing: border-box;
}

body {
  font-family: "lato", sans-serif;
  background : #242943;
  color      : white;
}
.title-color{
    color: #FFCB31;
}

.main-color{
color: #1A8c97;
}

.con-color{color: #242943;
}

.main-content{
  margin-top: 4.5rem;
}
.labour{
  color: #ef4836;
}
.tory{
  color: #1e90ff;
}
.asian{
  color: #00ff7f;
}

.today{
  color: #FFF5EE;
}

.text1{
  color: #f1f227;
}

.text2{
  color: #8b0000;
}
.hr {

    background  : #FFCB31;
    margin-left : auto;
    margin-right: auto;
    height      : 7px;

}

#link {
    color          : goldenrod;
    text-decoration: none;
} 



</style>
