<template>
    <div>
        <div>
            <TopNav/>
            
            <slot/>
        </div>
    </div>
</template>

<script>
import TopNav from '../components/TopNav.vue';

    export default {
    components: { TopNav }
}
</script>

<style lang="scss" scoped>

</style>