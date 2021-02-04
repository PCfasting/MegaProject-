<template>
    <v-container fluid>
        <v-row class="text-left">
            <v-col cols="10">
                <h1 class="green--text text--darken-2">
                    <v-icon large color="green darken-2">mdi-account-outline</v-icon>
                    Иван Иванов
                </h1>
            </v-col>
        </v-row>
        <v-row class="text-left">
            <v-col cols="2">
                <img src="https://randomuser.me/api/portraits/men/7.jpg" style="max-width: 100%">
            </v-col>
            <v-col cols="10" class="text-left">
                <p>
                    Веб-сайт: <a href="elvis.io" target="_blank">elvis.io</a>
                </p>
                <p>
                    E-mail: <a href="mailto:pochta@mail.da">pochta@mail.da</a>
                </p>
                <p>
                    Город: Rysia)
                </p>
                <p>
                    Место работы: Безработный
                </p>
            </v-col>
        </v-row>

    
    </v-container>
</template>

<script>
export default {
    mounted(){

    },
    watch: {
        $route(){
            
        }
    }
}

</script>
