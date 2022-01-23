<template>
  <div>
    <AppHeader />
    <AppBody />
  </div>
</template>

<script>
import AppBody from '~/components/parts/AppBody.vue'
import AppHeader from '~/components/parts/AppHeader.vue'
export default {
  name: 'IndexPage',
  components: { AppHeader, AppBody },
}
</script>
