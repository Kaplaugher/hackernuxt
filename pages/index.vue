<template>
  <div class="f1 code">
    <h1>Hello</h1>
    {{ids}}
    <ul>
      <li v-for="user in users" :key="user.id">{{user.login}}</li>

    </ul>
  </div>
</template>

<script>
import {mapState} from 'vuex'
export default {
  computed: mapState([
    'users',
    'ids'
  ])
}
</script>

<style>

</style>
