<template>
  <Navbar/>
  <div class="container">
    <h3 class="text-center">{{ titulo }}</h3>
    <Table/>
    <button class="btn btn-success">Test Button</button>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Table from './components/Table.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Table
  },
  data() {
    return {
      titulo: "App Vue Bco",
    }
  }
}
</script>

<style>

</style>
