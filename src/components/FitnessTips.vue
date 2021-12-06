<template>
    <div class="popup" id="popup-2">
        <div class="overlay"></div>
        <div class="content">
            <div class="close-btn" v-on:click="togglePopup()">&times;</div>
            <div>
                <h1 class='popupTitle'>Fitness Tips</h1>
                <br>
                <h1 class='popupBody'>Here are some general fitness tips to help as a guide and see an estimate of what you should be doing based on your age/gender!</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <h1 class='popupBody'>Age / Minimum / Active / Highly Active</h1>
                <br>
                <h1 class='popupBody'>4-6 yrs = 6,000 / 10,000 / 14,500</h1>
                <br>
                <h1 class='popupBody'>6-11 yrs (female) = 6,000 / 11,000 / 13,5000</h1>
                <br>
                <h1 class='popupBody'>6-11 yrs (male) = 6,000 / 13,000 / 15,500</h1>
                <br>
                <h1 class='popupBody'>12-19 yrs = 6,000 / 10,000 / 12,500</h1>
                <br>
                <h1 class='popupBody'>20-65 yrs = 3,000 / 7,000 / 11,500</h1>
                <br>
                <h1 class='popupBody'>65+ yrs = 3,000 / 7,000 / 10,500</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <h1 class='popupBody'>Here are the average number of steps taken by people based on their occupation.</h1>
                <br>
                <h1 class='popupBody'>Hospital: 22,778</h1>
                <h1 class='popupBody'>Medical: 16,390</h1>
                <h1 class='popupBody'>Retail: 14,660</h1>
                <h1 class='popupBody'>At-home Parent: 13,813</h1>
                <h1 class='popupBody'>Teaching: 12,564</h1>
                <h1 class='popupBody'>Laborer: 11,585</h1>
                <h1 class='popupBody'>Beautician: 9,209</h1>
                <h1 class='popupBody'>Clerical: 7,570</h1>
                <h1 class='popupBody'>Call Center: 6,618</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <h1 class='popupBody'>Lastly, here's an overall estimation of your activity level based on steps walked in general, without age or gender.</h1>
                <br>
                <h1 class='popupBody'>Sedentary = 5,000 steps or less</h1>
                <h1 class='popupBody'>Low activity = 5,000 - 7,499 steps</h1>
                <h1 class='popupBody'>Somewhat active = 7,500 - 9,999 steps</h1>
                <h1 class='popupBody'>Active = 10,000 - 12,500 steps</h1>
                <h1 class='popupBody'>Highly active = 12,500 steps or more</h1>
            </div>
        </div>
    </div>

    <button class="btnHow" v-on:click="togglePopup()">Fitness Tips</button>
</template>

<script>
export default {
    name: 'FitnessTips',
    methods:{
    togglePopup(){
        document.getElementById("popup-2").classList.toggle("active");
        }
    }
}
</script>