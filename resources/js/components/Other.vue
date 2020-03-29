<template>
    <div>The count from trat other unrelated component is: {{ count }}</div>
</template>

<script>
    export default {
        computed: {
            count() {
                return this.$store.state.count
            }
        }
    }
</script>
