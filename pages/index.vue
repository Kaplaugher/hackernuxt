<template>
  <div class="code">
    <h1>Top</h1>
    <Items />
  </div>
</template>

<script>
import {mapState} from 'vuex'
import Items from '~/components/Items.vue'
export default {
  components: {
    Items
  },
  async fetch({store}) {
    await store.dispatch('LOAD_ITEMS', 'topstories.json')
  }
}
</script>

<style>

</style>
