<template>
  <div class="home">
    <homeCarousel/>
    <secondSection/>
    <NewCustomerDiscount/>
    <flashsale/>
    <topSellers/>
    <subscribe/>
  </div>
</template>

<script>
// @ is an alias to /src
import homeCarousel from '@/components/homeCarousel'
import SecondSection from '@/components/SecondSection'
import NewCustomerDiscount from '@/components/NewCustomerDiscount'
import flashsale from '@/components/flashsale'
import topSellers from '@/components/topSellers'
import subscribe from '@/components/subscribe'

export default {
  name: 'Home',
  components: {
    homeCarousel,
    SecondSection,
    NewCustomerDiscount,
    flashsale,
    topSellers,
    subscribe
  }
}
</script>
