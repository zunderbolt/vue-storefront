<template>
  <div id="product">
    <h1>Product Page </h1>
    <h2> Product JSON </h2>
    <p> {{ product }} </p>
  </div>
</template>

<script>
// Here we are importing Core Page module responsible for business logic injection
import Product from '@vue-storefront/core/pages/Product'

export default {
  // Here we are injecting core Product Page business logic (you can find it under core/pages/Product.vue)
  // You can find the docs for Product Page here: https://github.com/DivanteLtd/vue-storefront/blob/master/doc/components/core/ProductPage.md
  mixins: [Product]
}
</script>
