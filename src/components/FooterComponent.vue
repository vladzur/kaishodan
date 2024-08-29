<script setup>
const goToInstagram = () => {
    window.open('https://www.instagram.com/partido.comunista.villarrica/', '_blank');
}
const goToFacebook = () => {
    window.open('https://www.facebook.com/people/PC-Villarrica/61552411023948/', '_blank');
}
const goToYoutube = () => {
    window.open('https://www.youtube.com/@PCVillarrica', '_blank');
}

</script>
<template>
    <v-footer padless height="auto" color="default" class="text-center">
        <v-row class="align-center justify-center">
            <v-col cols="12" class="py-4">
                <img src="@/assets/logo_jka.png" alt="Kai-Shodan" class="logo">
            </v-col>
            <v-col cols="12" class="py-4">
                <span class="black--text">&copy; {{ new Date().getFullYear() }} - Kai-Shodan</span>
            </v-col>
        </v-row>
    </v-footer>
</template>
