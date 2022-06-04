<template>
    <v-app>
        <v-main>
            <v-container>
                Normal
            </v-container>
        </v-main>
    </v-app>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
// class명은 항상 대문자로 먼저 시작한다.
export default class LayoutNormal extends Vue {

}
</script>

<style scoped>

</style>
