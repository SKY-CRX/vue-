<template>
  <div id="app">
    <hello></hello>
    <hr>
    <hi></hi>
  </div>
</template>

<script>
import Hello from './components/Hello';
import hi from './components/hi.vue';

export default {
  name: 'app',
  data() {
    return {

    }
  },
  components: {
    Hello,
    hi
  },
  methods: {

  }
}  
  </script>

  <style>

  </style>
