<template>
    <h1>Hello Woffsrlddd {{ name }}</h1>
    <ul>
        <li
            v-for="framwork of framworks"
            v-text="framwork"
            :key="framwork"
        ></li>
    </ul>
</template>

<script>
export default {
    props: {
        name: String,
        framworks: Array,
    },
};
</script>
