<template>
  <div>
    <h3>Liberal, Progressive & Reform</h3>
    <br>
      <b-button-group>
    <liberal />
    <progressive />
    <reform />
    <burial />
    <jjbs />
  </b-button-group>
  <br><br>
    <b-table striped :items="items" :fields="fields"></b-table>
  </div>
</template>

<script>
import burial from '@/components/buttons/burial'
import liberal from '@/components/buttons/liberal'
import progressive from '@/components/buttons/progressive'
import reform from '@/components/buttons/reform'
import jjbs from '@/components/buttons/jjbs'


  export default {
    data() {
      return {
        // Note `isActive` is left out and will not appear in the rendered table
        fields: ['Cemetery', 'Address', 'Year_Opened'],
        items : [
          { isActive: true, Cemetery: 'Edgwarebury', Address: 'Edgwarebury Lane', Year_Opened: '1972'},
          { isActive: true, Cemetery: 'Golders Green', Address: 'Hoop Lane ', Year_Opened: '1897'},
          { isActive: true, Cemetery: 'Willesden', Address: 'Pound Lane', Year_Opened: '1914'}
        ]
      }
    },
    components: {
    burial,
    reform,
    liberal,
    progressive,
    jjbs,
  }
  }
</script>

<style>
.table{
color    : aquamarine;
font-size: 1.5rem;
}

</style>
