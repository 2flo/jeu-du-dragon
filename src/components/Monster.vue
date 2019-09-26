<template>
    <div class="dragon">
        <img src="../assets/dragon.png" alt="DrogonTheBest">
        <h1>Drogon de la maison Targaryen</h1>
    <div>
        <span class="remaining-point">{{remainingPoint}}</span>
        <span class="life-point">/{{lifePoint}}</span>
    </div>
    </div>
</template>
<script>
export default {
    name: 'Monster',
    data: function(){
        return{
            lifePoint: 100,
            remainingPoint:100
        }
    }
}
</script>

<style>
img{
    width: 25vw;
}

h1{
    font-family: Arial, Helvetica, sans-serif;
}

.remaining-point{
    color: green;
}

.life-point{
    font-weight: 700;
}
</style>