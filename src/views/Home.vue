<template>
  <div class="home">
    <subscribe/>
  </div>
</template>

<script>
// @ is an alias to /src
import subscribe from '@/components/subscribe'
export default {
  name: 'Home',
  components: {
    subscribe,
  }
}
</script>
