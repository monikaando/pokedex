<template>
<div id="Pokemon">
    <div v-for="pokemon in pokemons" :key="pokemon.index">
        <h2>Name: {{ pokemon.name }}</h2>
        <p>type: {{pokemon.type }}</p>
        <p>color: {{pokemon.color}}</p>
    </div>
</div>
</template>

<script>
export default {
    name: "Pokemon",
    props: {
        pokemons: {
            type: Array,
            default: () => {
                return [{
                    name: "",
                    type: "",
                    color: ""
                }];
            }
        },
    
    },
    data() {
        return {

        };
    },
};
</script>



    // props: {
    //     details: {
    //         type: Object,
    //         default: () => {
    //             return {
    //                 name: "",
    //                 type: "",
    //                 color: ""
    //             }
    //         }
    //     },
    
    // },