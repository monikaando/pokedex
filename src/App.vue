<template>
<div id="app">
    <Pokemon :details="charmander" />
    <Pokemon :details="bulbosaur" />
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
            },
             bulbosaur: {
                name: "bulbosaur",
                type: "gras",
                color: "blue",
            }
        };
    },
};
</script>
