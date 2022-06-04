<template>
    <h1>{{greeting}}</h1>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
// import Vue from 'vue'

@Component
export default class FirstTest extends Vue {
    greeting;
    constructor () {
      // eslint-disable-next-line indent
        super()
      // eslint-disable-next-line indent
        this.greeting = 'Welcome to Vue with Vuetify and Typescript'
    }
}

</script>
