<template>
    <div class="example">{{ msg }}</div>
</template>

<script>
    export default {
        data() {
            return {
                msg: "Hello Vue Component",
            };
        },
        mounted() {
            const webpack_babel = "babel check";
            console.log(webpack_babel);
        },
    };
</script>

<style scoped>
    .example {
        font-weight: bold;
    }
</style>
