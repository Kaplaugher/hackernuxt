<template>
  <div class="code">
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
    await store.dispatch('LOAD_ITEMS', 'showstories.json')
  }
}
</script>

<style>

</style>
