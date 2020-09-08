<template>
  <div class="home">
    <homeCarousel/>
    <NewCustomerDiscount/>
    <subscribe/>
  </div>
</template>

<script>
// @ is an alias to /src
import homeCarousel from '@/components/homeCarousel'
import NewCustomerDiscount from '@/components/NewCustomerDiscount'
import subscribe from '@/components/subscribe'

export default {
  name: 'Home',
  components: {
    homeCarousel,
    NewCustomerDiscount,
    subscribe
  }
}
</script>
