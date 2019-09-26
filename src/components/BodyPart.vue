<template>
    <div class="body-part">
        <img :src="require(`../assets/bodypart/${link}`)" alt="pauvresvictimes">
        <div :class="position">
            <span class="remaining-point">{{remainingPoint}}</span>
            <span class="life-point">{{lifePoint}}</span>
        </div>
    </div>
</template>
<script>
export default {
    name: 'BodyPart',
    props: ['link','position'],
    data: function(){
        return{
            lifePoint: 50,
            remainingPoint: 50
        }
    }
}
</script>
