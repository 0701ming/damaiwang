<template>
    <div>
        欢迎[{{ this.$route.params.user.name }}]登录
    </div>
</template>

<script>
    export default {
        name: "Home",
        data(){
            return {
                user:""
            }
        },
//        mounted(){
//            console.log(this.$route.params)
//            this.user = this.$route.params.user;
//        }
    }

</script>

<style scoped>

</style>