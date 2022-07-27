<template>
    <div>
        <promo />    
        <core-features></core-features>    
        <specifications></specifications>
        <interior></interior> 
        <core-details></core-details>
        <order-now></order-now>
    </div>  
</template>

<script>
import Promo from '@/components/Promo.vue'
import Specifications from '@/components/Specifications.vue'
import Interior from '@/components/Interior.vue'
import CoreFeatures from '@/components/CoreFeatures.vue'
import CoreDetails from '@/components/CoreDetails.vue'
import OrderNow from '@/components/OrderNow.vue'

export default {
    components: { 
        Promo, 
        Specifications, 
        Interior, 
        CoreFeatures,
        CoreDetails,
        OrderNow 
    },

}
</script>

<style>

</style>