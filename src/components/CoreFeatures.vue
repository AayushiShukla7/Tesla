<template>
  <div style="background-color:black;margin-top:-10px;">
    
    <div class="background" style="display:table;" fluid>
        <div style="display:table-cell;vertical-align:bottom;padding-bottom:50px;">
            <v-row>
                <v-col>
                    <!-- <i class="fa-regular fa-gauge-simple-min fa-spin"></i> -->
                    <h1 class="white--text font-weight-light text-right">3.1 s</h1>
                    <p class="white--text text-right">0-60 mph*</p>
                </v-col>

                <v-col>
                    <h1 class="white--text font-weight-light text-center">358 mi</h1>
                    <p class="white--text text-center">Range (EPA est.)</p>
                </v-col>

                <v-col>
                    <h1 class="white--text font-weight-light">AWD</h1>
                    <p class="white--text">Dual Motor</p>
                </v-col>
            </v-row>
        </div>
    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style>
    .background {
        background-image: url('../../public/tesla-core-features.jpg');
        background-size: cover;
        width: 70%;
        height: 70vh;
    }
</style>