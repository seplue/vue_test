<template>
    <div>
        {{ message }}
    </div>
</template>

<script>
    export default {
        name: "MyFirstComponent",
        data: function() {
            return {
                message: 'Some Message'
            };
        }
    }
</script>

<style scoped>

</style>
