<template>
    <div class="link">
        <div class="part">
            <BodyPart link="body.png" position="center" class="part body"/>
            <BodyPart link="head.png" position="top" class="part head"/>
            <BodyPart link="left-arm.png" position="top-left" class="part arm_left"/>
            <BodyPart link="right-arm.png" position="top-right" class="part arm_right"/>
            <BodyPart link="left-foot.png" position="bottom-left" class="part foot_left"/>
            <BodyPart link="right-foot.png" position="bottom-right" class="part foot_right"/>
        </div>
    </div>
</template>
<script>
import BodyPart from './BodyPart'
export default {
    name: 'Link',
    components: {
        BodyPart
    }
}
</script>
<style scoped>

.part{
    display: flex;
    position: relative;
    width: 10vw;
}

.head{
    position: relative;
    z-index:2;
    bottom: 100px;
    left: 100px;
    z-index:2;
}

.body{
    z-index:1;
    position: relative;
    top: 300px;
}

.arm-left{
    z-index:2;
    position: relative;
    top: 45px;
}

.arm-right{
    z-index:2;
}

.foot-left{
    z-index:2;
}

.foot-right{
    z-index:2;
}
</style>