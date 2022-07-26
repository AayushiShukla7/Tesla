<template>
  <div style="background-color:black;margin-top:-10px;">
    
    <div class="background" style="display:table;" fluid>
        <div style="display:table-cell;vertical-align:bottom;padding-bottom:50px;">

            <v-row>
                <v-col>
                    <h1 class="white--text font-weight-light text-right">Battery</h1>
                    <p class="white--text text-right">Long Range</p>
                </v-col>

                <v-col>
                    <h1 class="white--text font-weight-light text-right">Weight</h1>
                    <p class="white--text text-right">4,048 lbs</p>
                </v-col>
            </v-row>

            <v-row>
                <v-col>
                    <h1 class="white--text font-weight-light text-right">Acceleration</h1>
                    <p class="white--text text-right">
                        3.1s 0-60 mph*<br/>*with rollout subtracted
                    </p>
                </v-col>

                <v-col>
                    <h1 class="white--text font-weight-light text-right">Cargo</h1>
                    <p class="white--text text-right">23 cu ft</p>
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
        background-image: url('../../public/tesla-specs.jpeg');
        background-size: cover;
        width: 100%;
        height: 120vh;
    }
</style>