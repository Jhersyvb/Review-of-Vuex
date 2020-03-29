<template>
    <div class="container">
        {{ count }}
        <p>
            <button @click="increment">+1</button>
        </p>
    </div>
</template>

<script>
    import { mapState, mapMutations } from 'vuex'

    export default {
        computed: mapState(['count']),

        methods: {
            custom() {},

            ...mapMutations(['increment'])
        }
    }
</script>
