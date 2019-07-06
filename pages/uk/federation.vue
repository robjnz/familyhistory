<template>
  <div>
    <h3>Federation Synagogue</h3>
    <br>
      <b-button-group>
    <federation />
    <fedburial />
  </b-button-group>
  <br><br>
    <b-table striped :items="items" :fields="fields"></b-table>
  </div>
</template>

<script>
import fedburial from '@/components/buttons/fedburial'
import federation from '@/components/buttons/federation'


  export default {
    data() {
      return {
        // Note `isActive` is left out and will not appear in the rendered table
        fields: ['Cemetery', 'Address', 'Year_Opened'],
        items : [
          { isActive: true, Cemetery: 'Edmonton', Address: 'Montague Road', Year_Opened: '1890'},
          { isActive: true, Cemetery: 'Rainham', Address: 'Upminster Road North ', Year_Opened: '1938'}
        ]
      }
    },
    components: {
    fedburial,
    federation,

  }
  }
</script>

<style>
.table{
color    : aquamarine;
font-size: 1.5rem;
}

</style>
