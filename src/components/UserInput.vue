<template>
    <div>
        <img src="../assets/healthy.png">
        <h1 id='status'>Health Status: Neutral</h1>
        <h1>Log new activity:</h1>

        <button class='btnActivity' v-on:click="EnterInput">Enter</button>
    </div>
</template>

<script>


export default {
    name: 'UserInput',
    components: {

    },

    methods:{
        EnterInput(){
             console.log("Hello");
        }
    }
}
</script>