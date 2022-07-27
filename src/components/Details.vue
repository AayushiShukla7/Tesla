<template>
  <div style="background-color:black;">
    
    <div class="background" style="display:table;" fluid>
        <div style="display:table-cell;vertical-align:bottom;padding-bottom:50px;">

            <v-row class="mt-8">
                <v-col cols="8">
                    <h1 class="white--text font-weight-light text-right">Battery</h1>
                    <p class="white--text text-right">Long Range</p>
                </v-col>

                <v-col cols="3" class="pr-5 ml-5">
                    <h1 class="white--text font-weight-light text-left">Weight</h1>
                    <p class="white--text text-left">4,048 lbs</p>
                </v-col>

                <v-col cols="1"></v-col>
            </v-row>

            <v-row>
                <v-col cols="8">
                    <h1 class="white--text font-weight-light text-right">Acceleration</h1>
                    <p class="white--text text-right">
                        3.1s 0-60 mph*<br/>*with rollout subtracted
                    </p>
                </v-col>

                <v-col cols="3" class="pr-5 ml-5">
                    <h1 class="white--text font-weight-light text-left">Cargo</h1>
                    <p class="white--text text-left">23 cu ft</p>
                </v-col>

                <v-col cols="1"></v-col>
            </v-row>

            <v-row>
                <v-col cols="8">
                    <h1 class="white--text font-weight-light text-right">Range</h1>
                    <p class="white--text text-right">
                        315 miles (EPA est.)
                    </p>
                </v-col>

                <v-col cols="3" class="pr-5 ml-5">
                    <h1 class="white--text font-weight-light text-left">Displays</h1>
                    <p class="white--text text-left">15" Center Touchscreen</p>
                </v-col>

                <v-col cols="1"></v-col>
            </v-row>

            <v-row>
                <v-col cols="8">
                    <h1 class="white--text font-weight-light text-right">Drive</h1>
                    <p class="white--text text-right">
                        Dual Motor All-Wheel Drive
                    </p>
                </v-col>

                <v-col cols="3" class="pr-5 ml-5">
                    <h1 class="white--text font-weight-light text-left">Supercharging Max/ Payment Type</h1>
                    <p class="white--text text-left">250 kW max; Pay Per Use</p>
                </v-col>

                <v-col cols="1"></v-col>
            </v-row>

            <v-row>
                <v-col cols="8">
                    <h1 class="white--text font-weight-light text-right">Seating</h1>
                    <p class="white--text text-right">
                        5 Adults
                    </p>
                </v-col>

                <v-col cols="3" class="pr-5 ml-5">
                    <h1 class="white--text font-weight-light text-left">Onboard Charger Max</h1>
                    <p class="white--text text-left">11.5 kW max (48A)</p>
                </v-col>

                <v-col cols="1"></v-col>
            </v-row>

            <v-row>
                <v-col cols="8">
                    <h1 class="white--text font-weight-light text-right">Wheels</h1>
                    <p class="white--text text-right">
                        20"
                    </p>
                </v-col>

                <v-col cols="3" class="pr-5 ml-5">
                    <h1 class="white--text font-weight-light text-left">Warranty</h1>
                    <p class="white--text text-left">Basic Vehicle - 4 years or 50,000 mi, whichever comes first
Battery & Drive Unit - 8 years or 120,000 mi, whichever comes first</p>
                </v-col>

                <v-col cols="1"></v-col>
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