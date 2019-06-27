<template>
  <listOfPrducts :products="getAllProducts"></listOfPrducts>
</template>
<script>
import { mapGetters } from 'vuex';
import listOfPrducts from './ListOfProducts.vue';

export default {
  components: {
    listOfPrducts,
  },
  computed: {
    ...mapGetters(['getAllProducts']),
  },
};
</script>


<style lang="">
</style>
