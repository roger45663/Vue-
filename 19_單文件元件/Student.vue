<template>
    <div>
        <p>學生名字: {{ name }}</p>
        <p>學生年齡: {{ age }}</p>
    </div>
</template>

<script>
export default {
    name: "Student",
    data() {
        return {
            name: "Peter",
            age: 22,
        };
    },
};
</script>
