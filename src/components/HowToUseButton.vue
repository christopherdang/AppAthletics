<template>
    <div class="popup" id="popup-1">
        <div class="overlay"></div>
        <div class="content">
            <div class="close-btn" v-on:click="togglePopup()">&times;</div>
            <div>
                <h1 class='popupTitle'>How to Use App Athletics</h1>
                <h1 class='popupBody'>The purpose of the application is to show you generally about how healthy you are compared to other people via steps walked.</h1>
                <br>
                <h1 class='popupBody'>Using a data set that traced people's wireless devices on UF campus, we estimated the average number of steps taken from the traces and created a percentile from it.</h1>
                <br>
                <h1 class='popupBody'>Depending on the number of steps you input, it will be compared to the percentile and will determine your level of physical activity
                based on steps walked.</h1>
                <br>
                <h1 class='popupBody'>The 3 levels of physical activity are: not active, active, and highly active.</h1>
                <h1 class='popupBody'>An avatar will appear depending on the level of physical activity.</h1>
                <h1 class='popupBody'>We will also offer you tips to help you towards your specific goals based on your activity levels.</h1>
                <br>
                <h1 class='popupBody'>There are additional "fitness" and "medical" tips below that provide general information about staying active and healthy!</h1>
                <br>
                <h1 class='popupBody'>Hope you enjoy the app and lets get active together!</h1>
            </div>
        </div>
    </div>

    <button class="btnHow" v-on:click="togglePopup()">How to Use</button>
</template>

<script>
export default {
    name: 'HowToUseButton',
    methods:{
    togglePopup(){
        document.getElementById("popup-1").classList.toggle("active");
        }
    }
}
</script>