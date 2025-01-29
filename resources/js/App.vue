<template>
    <v-app>
      <ExampleComponent />
    </v-app>
  </template>

  <script>
  import ExampleComponent from './components/ExampleComponent.vue'

  export default {
    name: 'App',
    components: {
      ExampleComponent,
    },
  }
  </script>
