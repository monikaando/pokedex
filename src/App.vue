<template>
<div id="app">
    <Pokemon name="charmander" :type="type" />
    <Pokemon name="bulbosaur" type="grass" />

</div>
</template>

<script>
import Pokemon from "./components/Pokemon";

export default {
    name: "App",
    components: {
        Pokemon,
    },
    data() {
        return {
            type: "fire"
        };
    },
};
</script>
