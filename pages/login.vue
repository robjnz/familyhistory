<template>
<section>
  <b-container>

      <div>
        <b-card bg-variant="danger" text-variant="white" header="Private family History Pages" class="text-center">

          <!--
          ><b-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</b-card-text>
-->
<password />

<input type="button" value="Enter Protected Page" onClick="passWord()">

</b-card>

      </div>
  </b-container>
</section>

</template>

<script>

import password from '@/pages/family/password'


export default {

  components: {
password,
}
}
</script>
