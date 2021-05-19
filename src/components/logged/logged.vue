<template>
    <v-container>
        <v-row>
            <v-col cols="12">
                 <h1 class="pt-5">Username:{{username}}</h1>
            </v-col>
            <v-col cols="12">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-title >Transportation planning modules</v-card-title>
                </v-card>
            </v-col>
            <v-col cols="3">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-title >LPN/TO feed verification</v-card-title>
                </v-card>
            </v-col>
            <v-col cols="3">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-title >Trip planning</v-card-title>
                </v-card>
            </v-col>
            <v-col cols="3">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-title >E-way bill</v-card-title>
                </v-card>
            </v-col>
            <v-col cols="3">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-title >LPN/TO feed verification</v-card-title>
                </v-card>
            </v-col>
            <v-col cols="12">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-title >Transportation management modules</v-card-title>
                </v-card>
            </v-col>
            <v-col cols="3">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-title >Cost calculator</v-card-title>
                </v-card>
            </v-col>
            <v-col cols="6">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-title >OFIN integration for generating vendor invoice</v-card-title>
                </v-card>
            </v-col>
            <v-col cols="3">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-title >Monthly fleet planning</v-card-title>
                </v-card>
            </v-col>
            <v-col cols="12">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-title >Master</v-card-title>
                </v-card>
            </v-col>
            <v-col cols="3" class="mb-5">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-actions><v-btn depressed x-large class="blue lighten-4" to="/origin">Origin-destination</v-btn></v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="3" class="mb-5">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-actions><v-btn depressed x-large class="blue lighten-4" to="/vendor">Vehicle-vendor</v-btn></v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="3" class="mb-5">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-actions><v-btn depressed x-large class="blue lighten-4" to="/contract">Vendor-contract</v-btn></v-card-actions>
                </v-card>
            </v-col>
            <v-col cols="3" class="mb-5">
                <v-card class="d-flex flex-column justify-center align-center blue lighten-4">
                    <v-card-actions><v-btn depressed x-large class="blue lighten-4" to="/itemsuf">Item-SUF</v-btn></v-card-actions>
                </v-card>
            </v-col>

            
        </v-row>
    </v-container>
</template>
<script>

export default {
    name:"logged",
    data(){
        return{
        username:"XYZ",
        }
    }
}
</script>
