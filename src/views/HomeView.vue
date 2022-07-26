<template>
    <div>
        <promo />
        <specifications></specifications>
        <interior></interior>
        <core-features></core-features>
    </div>  
</template>

<script>
import Promo from '../components/Promo.vue'
import Specifications from '../components/Specifications.vue'
import Interior from '../components/Interior.vue'
import CoreFeatures from '../components/CoreFeatures.vue'

export default {
    components: { 
        Promo, 
        Specifications, 
        Interior, 
        CoreFeatures 
    },

}
</script>

<style>

</style>