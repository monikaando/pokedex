<template>
<div id="app">
    <Pokemon :details="charmander" />
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
            charmander: {
                name: "charmander",
                type: "fire",
                color: "orange",
            }
        };
    },
};
</script>
