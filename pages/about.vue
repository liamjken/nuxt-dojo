<template>
    <div>
<h2>About Liam</h2>
<p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nobis magnam dignissimos quia sit numquam totam in blanditiis quas laboriosam at.</p>
<p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nobis magnam dignissimos quia sit numquam totam in blanditiis quas laboriosam at.</p>
<div>{{ data }}</div>
    </div>
</template>

<script setup>
const { data } = await useFetch('server/api/currency/GBP')
</script>

<style scoped>
h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
p{
    margin: 20px 0;
}

</style>