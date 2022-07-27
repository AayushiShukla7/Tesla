<template>
    <div>
        <promo />    
        <core-features></core-features>    
        <specifications></specifications>
        <interior></interior> 
        <!-- <details></details> -->
    </div>  
</template>

<script>
import Promo from '@/components/Promo.vue'
import Specifications from '@/components/Specifications.vue'
import Interior from '@/components/Interior.vue'
import CoreFeatures from '@/components/CoreFeatures.vue'
import Details from '@/components/Details.vue'

export default {
    components: { 
        Promo, 
        Specifications, 
        Interior, 
        CoreFeatures,
        Details 
    },

}
</script>

<style>

</style>