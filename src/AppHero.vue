<script>
export default {
    data() {
        return{
            titleJumbo:'HELLO WORD!'
        }
    }
}
</script>

<template>
    <div class="jumbotrone">
        <h1>{{ titleJumbo }}</h1>
    </div>
</template>

<style scoped>
.jumbotrone{
    height: 350px;
    width: 750px;
    margin: 5px auto;
    display: flex;
    align-items: center;

    background-color: bisque;
}

.jumbotrone:hover{
    background-color: lightblue;
    box-shadow: 10px 5px 5px black;
    color: brown;
    text-shadow: 5px 5px 5px black;
}

h1{
    width: fit-content;
    margin: 10px auto;
}

</style>