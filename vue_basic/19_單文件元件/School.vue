<template>
    <div class="demo">
        <p>學校名稱: {{ name }}</p>
        <p>學校地址: {{ address }}</p>
    </div>
</template>

<script>
export default {
    name: "School",
    data() {
        return {
            name: "尚硅谷",
            address: "上海",
        };
    },
};
</script>

<style>
.demo {
    background-color: yellow;
    color: green;
}
</style>
