<template>
<div id="app">
    <Pokemon :pokemons="starters" />
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
            // charmander: {
            //     name: "charmander",
            //     type: "fire",
            //     color: "orange",
            // },
            //  bulbosaur: {
            //     name: "bulbosaur",
            //     type: "gras",
            //     color: "blue",
            // }
            starters: [
              {name: "charmander", type: "fire", color: "orange"},
              {name: "squirtle", type: "water", color: "orange"},
              {name: "bulbasaur", type: "grass", color: "orange"},
            ]
        };
    },
};
</script>
    // <Pokemon :details="charmander" />