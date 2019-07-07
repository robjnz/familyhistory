<template>
  <div>
    <h3>United</h3>
    <br>
      <b-button-group>
    <united />
    <unitedburial />
  </b-button-group>
  <br><br>
    <b-table striped :items="items" :fields="fields"></b-table>
  </div>
</template>

<script>
import unitedburial from '@/components/buttons/unitedburial'
import united from '@/components/buttons/united'


  export default {
    data() {
      return {
        // Note `isActive` is left out and will not appear in the rendered table
        fields: ['Cemetery', 'Address', 'Year_Opened'],
        items : [
          { isActive: true, Cemetery: 'Alderny', Address: 'Alderny Road', Year_Opened: '1969'},
          { isActive: true, Cemetery: 'Aldershot', Address: 'Redan Road ', Year_Opened: '1864'},
          { isActive: true, Cemetery: 'Brady', Address: 'Brady Street ', Year_Opened: '1761'},
          { isActive: true, Cemetery: 'Bushey', Address: 'Little Bushey Lane ', Year_Opened: '1947'},
          { isActive: true, Cemetery: 'Dover', Address: 'Old Charlton Road', Year_Opened: '1868'},
          { isActive: true, Cemetery: 'East Ham', Address: 'Marlow Road', Year_Opened: '1919'},
          { isActive: true, Cemetery: 'Eretz Hachaim', Address: 'Jerusalem', Year_Opened: ''},
          { isActive: true, Cemetery: 'Hackney', Address: 'Lauriston Road ', Year_Opened: '1788'},
          { isActive: true, Cemetery: 'Plashet', Address: 'High Street North', Year_Opened: '1896'},
          { isActive: true, Cemetery: 'Sheffield', Address: 'Colley Road', Year_Opened: '1931'},
          { isActive: true, Cemetery: 'Waltham Abbey', Address: 'Skillet Hill Honey Lane ', Year_Opened: '1960'},
          { isActive: true, Cemetery: 'west Ham', Address: 'Buckingham Road', Year_Opened: '1857'},
          { isActive: true, Cemetery: 'Willesden', Address: 'Beaconsfield Road', Year_Opened: '1873'}








        ]
      }
    },
    components: {
    unitedburial,
    united,
  }
  }
</script>

<style>
.table{
color    : aquamarine;
font-size: 1.5rem;
}

</style>
