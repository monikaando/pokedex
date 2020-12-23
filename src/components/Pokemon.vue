<template>
<div id="pokemon">
    <h2>Name: {{ name }}</h2>
    <p>type: {{type }}</p>

</div>
</template>

<script>
export default {
    name: "pokemon",
    props: {
        name: String,
        type: String,
    },
    data() {
        return {

        };
    },
};
</script>
