<template>
  <div>
    <h3>Western</h3>
    <br>
      <b-button-group>
    <western />
    <westernburial />
  </b-button-group>
  <br><br>
    <b-table striped :items="items" :fields="fields"></b-table>
  </div>
</template>

<script>
import westernburial from '@/components/buttons/westernburial'
import western from '@/components/buttons/western'


  export default {
    data() {
      return {
        // Note `isActive` is left out and will not appear in the rendered table
        fields: ['Cemetery', 'Address', 'Year_Opened'],
        items : [
          { isActive: true, Cemetery: 'Cheshunt', Address: 'Bullscross Ride', Year_Opened: '1968'},
          { isActive: true, Cemetery: 'Edmomtom', Address: 'Montague Road', Year_Opened: '1889'},
          { isActive: true, Cemetery: 'Fulham', Address: 'Fulham Road', Year_Opened: '1815'},
          { isActive: true, Cemetery: 'Streatham', Address: 'Rowan Road', Year_Opened: '1915'}


        ]
      }
    },
    components: {
    westernburial,
    western,

  }
  }
</script>

<style>
.table{
color    : aquamarine;
font-size: 1.5rem;
}

</style>
