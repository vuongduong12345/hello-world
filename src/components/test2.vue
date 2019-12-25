<template>
    <div>
        <h1>lay data tu props</h1>
        <h1>{{title}}</h1>
        <h1>{{demo}}</h1>
        <h1>{{demo2}}</h1>
    </div>
</template>
<script>
export default {
    name: "haha",
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