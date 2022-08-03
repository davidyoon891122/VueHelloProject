<template>
    <li>{{text}}</li>
</template>
<script>
export default {
    props: {
        text: {
            type: String,
            required: true,
            default: "안녕",
        }
    }
}
</script>
<style>
    
</style>