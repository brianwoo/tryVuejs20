<template>
    
    <div class="test">
        <h1>{{title}}</h1>
    </div>
</template>


<script>
    export default {
        name: 'test',
        data() {
            return {
                title: "Hello World",
                user: {
                    first_name: "John",
                    last_name: "Doe"
                }
            }
        }
    }
</script>


<style scoped>

</style>