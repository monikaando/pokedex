<template>
<div id="pokemon">
    <h2>Name: {{ details.name }}</h2>
    <p>type: {{details.type }}</p>
    <p>color: {{details.color}}</p>

</div>
</template>

<script>
export default {
    name: "pokemon",
    props: {
        details: {
            type: Object,
            default: ()=>{
              return {name:"", type:"", color: ""}
            }        
            }

    },
    data() {
        return {

        };
    },
};
</script>
