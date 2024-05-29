<template>
    <div>
        <img :src="streamRoute" crossorigin="anonymous"/>
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'HomeView',
    data() {
        return {
            streamRoute: 'http://IP:PORT/stream',
        };
    },
});
</script>
<style lang="scss">
img {
    width: 100%;
    height: 97vh;
}
</style>
