<template>
  <div id="page-wrap">
    <ProductsGrid
      :products="products" />
  </div>
</template>

<script>
import {products} from '../fake-data.js'
import ProductsGrid from '../components/ProductsGrid.vue'

export default{
  components: {
    ProductsGrid,
  }
}
</script>