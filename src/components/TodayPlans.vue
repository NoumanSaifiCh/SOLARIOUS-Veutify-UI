<template >
    <v-container>

        <v-row justify=" d-flex justify-space-between" class="px-5 mb-5">
            <div>
                <h3>Today Plans</h3>
                <p>June 14th, 2022</p>
            </div>
            <div><v-btn fab dark color="black">
                    <v-icon dark>
                        mdi-plus
                    </v-icon>
                </v-btn></div>
        </v-row>

        <v-row class="px-5 mt-5">
            <h3>Sustainable development goals and health innovation</h3>
        </v-row>

        <v-row class="pa-5 mr-5" justify=" d-flex justify-space-between">
            <div class="d-flex">

                <v-avatar color="orange" size="48" >
                    <span class="white--text text-h5">1</span>
                </v-avatar>
                <v-avatar color="teal" size="48" class="ava">
                    <span class="white--text text-h5">+</span>
                </v-avatar>
                

            </div>
            <v-spacer></v-spacer>
            <v-divider class="mx-4" vertical></v-divider>
            <div class="d-flex align-start flex-column">
                <subtitle-1>Media Team meeting</subtitle-1>
                <subtitle-1>13:30 - 14:50</subtitle-1>
            </div>
        </v-row>
        <div elevation="5" class="py-3">
            <v-parallax height="170" src="../assets/pic1.jpg">

                <v-row justify="center">
                    <v-col class="text-start" cols="12">
                        <h3 class="font-weight-thin ma-4 black--text">
                            <b> Weekly report</b>
                        </h3>
                        <h4 class="black--text font-weight-thin ma-4">
                            Track your performance
                        </h4>
                    </v-col>
                </v-row>
                <div> <v-btn class="ma-2" outlined color="black">
                        VIEW REPORT
                    </v-btn></div>
            </v-parallax>
        </div>
        <v-row>
            <v-col cols="6">
                <div elevation="5" class="py-3">
                    <v-parallax height="300" src="../assets/pic2.jpg">
                        <v-row justify="center">
                            <v-col class="text-start" cols="12">
                                <h3 class="font-weight-thin ma-4 black--text">
                                    <b> Study 78X</b>
                                </h3>
                                <h4 class="black--text font-weight-thin ma-4">
                                    <v-icon>mdi-clock</v-icon>
                                    in Progress
                                </h4>
                            </v-col>
                        </v-row>

                    </v-parallax>
                </div>
            </v-col>

            <v-col cols="6">
                <div elevation="5" class="py-3">
                    <v-parallax height="300" src="../assets/pic2.jpg">
                        <v-row justify="center">
                            <v-col class="text-start" cols="12">
                                <h3 class="font-weight-thin ma-4 black--text">
                                    <b> Analyses</b>
                                </h3>
                                <h4 class="black--text font-weight-thin ma-4">
                                    <v-icon>mdi-clock</v-icon>
                                    Completed
                                </h4>
                            </v-col>
                        </v-row>

                    </v-parallax>
                </div>

            </v-col>
        </v-row>


    </v-container>

</template>

<script>

export default {
    name: 'SideBar',

    data() {
        return {

        };
    }
}
</script>
    
<style scoped>

.ava{
 margin-left: -20px;
}

</style>