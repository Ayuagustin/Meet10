<template>
    <h1>{{title}}</h1>
</template>
<script>
export default{
    props :{
        title : String,
    }
}
</script>
<style scoped>
h1{
    colour : #F08080;
    text-align : center;
}
</style>