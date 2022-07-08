<template>
    <div class="eevee">
        <div class="body">
            <div class="head">
                <Ears />
                <Face />
            </div>
            <Chest />
            <Legs />
            <Tails />
        </div>
    </div>
</template>

<script>
import Chest from './partials/Chest.vue'
import Ears from './partials/Ears.vue'
import Face from './partials/Face.vue'
import Legs from './partials/Legs.vue'
import Tails from './partials/Tails.vue'
export default {
    components: { Ears, Face, Chest, Legs, Tails },
        name: 'PetComponent',
}
</script>

<style lang="scss" scoped>

</style>