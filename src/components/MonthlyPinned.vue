<template >
    <v-container>
        <v-row justify="d-flex justify-space-between " class="pa-3">
            <h3>Monthly pinned</h3>
            <subtitle-1 class="grey--text">View all</subtitle-1>
        </v-row>
        <v-card class="mx-auto" max-width="520" outlined>
            <v-list-item three-line>
                <v-list-item-content>
                    <v-row justify="d-flex justify-space-between " class="pa-3">
                        <subtitle-1 class="grey--text">Next-gen immuno</subtitle-1>
                        <subtitle-1 class="grey--text">5d</subtitle-1>
                    </v-row>
                    <p><b>Multispecific liquids anl</b></p>
                </v-list-item-content>
            </v-list-item>

            <v-container>
                <v-row>
                    <v-alert color="orange" border="0" elevation="0" colored-border icon="mdi-numeric-2-circle">
                        Need feedback
                    </v-alert>
                </v-row>
            </v-container>
        </v-card>


        <!-- next card -->

        <v-card class="mt-2" max-width="520" outlined>
            <v-list-item three-line>
                <v-list-item-content>
                    <v-row justify="d-flex justify-space-between " class="pa-3">
                        <subtitle-1 class="grey--text">Harmony</subtitle-1>
                        <subtitle-1 class="grey--text">1h</subtitle-1>
                    </v-row>
                    <p><b>Protein characteriziation during childhood<br> and pregnancy</b></p>
                </v-list-item-content>
            </v-list-item>

            <v-container>
                <v-row>
                    <!-- <v-btn class="mb-2 mx-2   " fab small elevation="0" color="orange">2
                    </v-btn> -->
                    <!-- <p class="mt-2">Dedline is today</p> -->
                    <v-alert color="black" border="0" elevation="0" colored-border icon=" mdi-alert-circle">
                        Dedline is today
                    </v-alert>
                </v-row>
            </v-container>
        </v-card>

        <!-- next card -->

        <v-card class="mt-2" max-width="520" outlined>
            <v-list-item three-line>
                <v-list-item-content>
                    <v-row justify="d-flex justify-space-between " class="pa-3">
                        <subtitle-1 class="grey--text">Pharmaceutical</subtitle-1>
                        <subtitle-1 class="grey--text">7h</subtitle-1>
                    </v-row>
                    <p><b>Quick element dissolution testing</b></p>
                </v-list-item-content>
            </v-list-item>

            <v-container>
                <v-row>
                    <v-alert color="grey" border="0" elevation="0" colored-border icon=" mdi-check-circle">
                        Accepted
                    </v-alert>

                </v-row>
            </v-container>
        </v-card>


        <div>
        </div>

        <div class="pt-5">
            <v-row justify=" d-flex justify-space-between" class="px-5 mb-1 pt-3">
                <div>
                    <h3>My Learning</h3>
                    <p>Your progress of medical lectures</p>
                </div>
                <div>
                    <h6>...</h6>
                </div>
            </v-row>
        </div>


        <div class="pt-5">
            <v-row justify=" d-flex justify-space-between" class="px-5 mb-1 pt-0">
                <div class="d-flex flex-row">
                    <div><v-img class="pt-2 mr-2" max-height="50" max-width="50" src="../assets/pic3.jpg"></v-img></div>
                    <div>
                        <h3>Viruses</h3>
                        <p class="grey--text">96% progress</p>
                    </div>

                </div>


                <div class="d-flex flex-row">
                    <div><v-img class="pt-2 mr-2" max-height="50" max-width="50" src="../assets/pic4.jpg"></v-img></div>
                    <div>
                        <h3>Bactrial</h3>
                        <p class="grey--text">36% progress</p>
                    </div>

                </div>

            </v-row>
        </div>


        <div class="pt-5">
            <v-row justify=" d-flex justify-space-between" class="px-5 mb-1 pt-0">
                <div class="d-flex flex-row">
                    <div><v-img class="pt-2 mr-2" max-height="50" max-width="50" src="../assets/pic5.jpg"></v-img></div>
                    <div>
                        <h3>Med science</h3>
                        <p class="grey--text">7% progress</p>
                    </div>

                </div>


                <div class="d-flex flex-row">
                    <div><v-img class="pt-2 mr-2" max-height="50" max-width="50" src="../assets/pic7.jpg"></v-img></div>
                    <div>
                        <h3>Human gen</h3>
                        <p class="grey--text">58% progress</p>
                    </div>

                </div>

            </v-row>
        </div>
    </v-container>
</template>

<script>

export default {
    name: 'MonthlyPinned',

    data() {
        return {

        };
    }
}
</script>