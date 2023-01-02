<template>
    <div>
        <v-card class="d-flex align-start flex-column mb-6 " color="grey lighten-5" flat height="820">
            <v-card class="pa-2 mb-auto d-lex " outlined tile color="grey lighten-5">

                <div> <v-badge bordered bottom color="green accent-10" dot offset-x="15" offset-y="65"
                        class="ml-3 py-3">
                        <v-avatar size="50">
                            <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img>
                        </v-avatar>
                    </v-badge></div>
                <div class="ml-1">
                    <h4>Dr. Riddle</h4>
                    <p class="grey--text ml-1">Scientist</p>
                </div>
            </v-card>



            <v-card class="pa-2 align-center" outlined tile color="grey lighten-5">

                <div class="text-center ml-2">
                    <div class="my-2">
                        <v-btn color="white" fab x-small dark>
                            <v-icon color="black">mdi-pencil</v-icon>
                        </v-btn>
                    </div>
                    <div class="my-2">
                        <v-btn color="white" fab small dark>
                            <v-icon color="black">mdi-message-processing-outline</v-icon>
                        </v-btn>
                    </div>
                    <div class="my-2">
                        <v-btn color="black" fab dark>
                            <v-icon dark>
                                mdi-plus
                            </v-icon>
                        </v-btn>
                    </div>
                </div>
            </v-card>
        </v-card>


    </div>

</template>
<script>
export default {
    name: 'ProfileDoctor',

    data() {
        return {

        };
    }
}
</script>