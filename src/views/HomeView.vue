<template>
  <!-- <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div> -->
  <div class="app">
    <p>{{ name }} - {{ age }}</p>
    <button @click="fnChangeName('zelda')">change name</button>
    <button @click="changeAge('40')">change age</button>
  </div>
</template>

<script lang="ts">

import { Component, Vue } from 'vue-property-decorator'
// import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

@Component({
  components: {
    // HelloWorld
  },
  data () {
    return {
      name: '줄리',
      age: 25
    }
  },

  methods: {

    fnChangeName (name: string) {
      name = 'jouse'
      return name
    },
    changeAge (age: string | number) {
      age = 4
      return age
    }
  }
})
export default class HomeView extends Vue {}
</script>
