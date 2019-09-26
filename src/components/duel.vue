<template>
    <div class="duel">
        <Monster/>
        <Link/>
        <Link/>
        <Link/>
    </div>
</template>
<script>
import Monster from './Monster.vue'
import Link from './Link.vue'
export default {
    name: 'duel',
    components: {
        Monster,
        Link
    }
}
</script>