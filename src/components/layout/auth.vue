<template>
    <v-app>
        <v-main>
            <v-container class="justify-center align-center fill-height">
                <v-text-field outlined></v-text-field>
                <v-btn @click="test">test</v-btn>
            </v-container>
        </v-main>
    </v-app>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
// class명은 항상 대문자로 먼저 시작한다.
export default class LayoutAuth extends Vue {
  $firebase: any
  test () {
    console.log(this.$firebase)
  }
}
</script>

<style scoped>

</style>
