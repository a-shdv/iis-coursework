<template >
    <v-card class="h-100" style="min-height: 100vh">
        <v-row>
            <v-col class="col col-3">
                <Menu />
            </v-col>
            <v-col class="col col-9">
                <slot />
            </v-col>
        </v-row>
    </v-card>
</template>
<script>
import Menu from "~/components/Menu.vue"
export default {
    components: {
        Menu
    }
}
</script>
<style lang="">

</style>
