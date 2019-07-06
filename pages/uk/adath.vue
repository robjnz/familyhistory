<template>
  <div>
    <h3>Adath Yisroel</h3>
    <br>
      <b-button-group>
    <burial />
  </b-button-group>
  <br><br>
    <b-table striped :items="items" :fields="fields"></b-table>
  </div>
</template>

<script>
import burial from '@/components/buttons/burial'

  export default {
    data() {
      return {
        // Note `isActive` is left out and will not appear in the rendered table
        fields: ['Cemetery', 'Address', 'Year_Opened'],
        items : [
          { isActive: true, Cemetery: 'Cheshunt', Address: 'Silver Street', Year_Opened: '1964'},
          { isActive: true, Cemetery: 'Enfield', Address: 'Carterhatch Lane ', Year_Opened: '1927'}
        ]
      }
    },
    components: {
    burial,
  }
  }
</script>

<style>
.table{
color    : aquamarine;
font-size: 1.5rem;
}

</style>
