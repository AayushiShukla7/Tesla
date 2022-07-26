<template>
  <v-container class="container" fill-width fluid>
    
    <v-layout row>
        <v-flex xs12 class="text-xs-center display-1 white--text font-weight-black ma-5">
            Specifications
        </v-flex>
    </v-layout>

    <v-row class="row">
        <v-col cols="6">
            <v-row>
                <v-col cols="2"></v-col>
                <v-col cols="10">
                    <v-img  width="100%" src="https://tesla-cdn.thron.com/delivery/public/image/tesla/ea753653-02a2-4206-aac5-82a33a0a245d/bvlatuR/std/2880x1800/model-3-hero-a-desktop"></v-img>
                </v-col>
            </v-row>
        </v-col>

        <v-col cols="6" class="white--text" style="align-self:center;">
            <div class="ml-4" style="width:36%;">
                <span style="font-size:23px;" class="mb-2">
                    Built for Safety
                </span>
                <br>
                <span>
                    Safety is the most important part of every Tesla. We design our vehicles to exceed safety standards.
                </span>
            </div>
        </v-col>
    </v-row>

    <v-row>     
        <v-col cols="6" class="white--text" style="align-self:center;">
            <v-row justify="end">
                <div class="mb-2 mr-4" style="width:36%;">
                    <span style="font-size:23px;" class="mb-2">
                    Future of Driving
                    </span>
                    <br>
                    <span>
                        Autopilot's advanced safety and convenience features are designed to assist you with the most burdensome parts of driving.
                    </span>
                </div>
            </v-row>
        </v-col>

        <v-col cols="6">
            <v-row>                
                <v-col cols="10">
                    <v-img  width="100%" src="https://tesla-cdn.thron.com/delivery/public/image/tesla/c960989c-3359-4caf-8cc7-afb07c372d6f/bvlatuR/std/4096x2560/Autopilot-Hero-Vision-Desktop"></v-img>
                </v-col>
                <v-col cols="2"></v-col>
            </v-row>
        </v-col>
    </v-row>

    <v-row>
        <v-col cols="6">
            <v-row>
                <v-col cols="2"></v-col>
                <v-col cols="10">
                    <v-img  width="100%" src="https://tesla-cdn.thron.com/delivery/public/image/tesla/1a5ba4b1-efd8-40bc-8b6d-e81bf8223e37/bvlatuR/std/2560x1440/Model-3-Performance-Hero-Desktop-LHD"></v-img>
                </v-col>
            </v-row>
        </v-col>

        <v-col cols="6" class="white--text" style="align-self:center;">
            <div class="ml-4" style="width:36%;">
                <span style="font-size:23px;" class="mb-2">
                    Quickest Acceleration
                </span>
                <br>
                <span>
                    Model 3 comes with the option of dual motor all-wheel drive, 20” Überturbine Wheels and Performance Brakes for total control in all weather conditions. A carbon fiber spoiler improves stability at high speeds, all allowing Model 3 to accelerate from 0-60 mph* in as little as 3.1 seconds.
                </span>
            </div>
        </v-col>
    </v-row>

    <v-row>     
        <v-col cols="6" class="white--text" style="align-self:center;">
            <v-row justify="end">
                <div class="mb-2 mr-4" style="width:36%;">
                    <span style="font-size:23px;" class="mb-2">
                    Dual Motor
                    </span>
                    <br>
                    <span>
                        Tesla All-Wheel Drive has two independent motors for improved redundancy, each with only one moving part for minimal maintenance and maximum durability. Unlike traditional all-wheel drive systems, they digitally control torque to the front and rear wheels for far better handling and traction control.
                    </span>
                </div>
            </v-row>
        </v-col>

        <v-col cols="6">
            <v-row>                
                <v-col cols="10">
                    <v-img  width="100%" src="https://tesla-cdn.thron.com/delivery/public/image/tesla/a7d91e4d-ba1e-41f1-b996-36fb4c925f57/bvlatuR/std/2560x1600/Model-3-AWD-Hero-Desktop-LHD"></v-img>
                </v-col>
                <v-col cols="2"></v-col>
            </v-row>
        </v-col>
    </v-row>

    <v-row>
        <v-col cols="6">
            <v-row>
                <v-col cols="2"></v-col>
                <v-col cols="10">
                    <v-img  width="100%" src="https://tesla-cdn.thron.com/delivery/public/image/tesla/b314365b-e41d-4682-b890-608bdbdfa49e/bvlatuR/std/2560x2204/Model-3-Range-Hero-Desktop-LHD"></v-img>
                </v-col>
            </v-row>
        </v-col>

        <v-col cols="6" class="white--text" style="align-self:center;">
            <div class="ml-4" style="width:36%;">
                <span style="font-size:23px;" class="mb-2">
                    Go Anywhere
                </span>
                <br>
                <span>
                    Model 3 is fully electric, so you never need to visit a gas station again. If you charge overnight at home, you can wake up to a full battery every morning. And when you’re on the road, it’s easy to plug in along the way—at any public station or with the Tesla charging network. We currently have over 35,000 Superchargers worldwide, with six new locations opening every week.
                </span>
            </div>
        </v-col>
    </v-row>

  </v-container>
</template>

<script>
export default {

}
</script>

<style scoped>
    .container {
        background-color:black;
        margin-top: -10px;
    }

    .row {
        margin-top: 50px;
    }
</style>