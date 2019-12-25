<template>
    <div>
         <!-- <h1>{{title}}</h1> -->
        <h1>{{demo}}</h1>
        <h1>{{demo2}}</h1>
       
    </div>
</template>
<script>
export default {
    name: "Test2",
    props: {
        title: String
    },
    data() {
        return {
            demo: "xin chao",
            demo2: "xin chao 2"
        }
    }
}
</script>
<style>

</style>