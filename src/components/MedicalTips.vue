<template>
    <div class="popup" id="popup-3">
        <div class="overlay"></div>
        <div class="content">
            <div class="close-btn" v-on:click="togglePopup()">&times;</div>
            <div>
                <h1 class='popupTitle'>Medical Tips</h1>
                <h1 class='popupBody'>Here are some general medical tips to keep track of and make sure your healthy internally as well!</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <h1 class='popupBody'>This is what your Average and Maximum BPM should be based on age.</h1>
                <br>
                <h1 class='popupBody'>Age / Target BPM Range / Maximum BPM</h1>
                <br>
                <h1 class='popupBody'>20 yrs = 120-170 / 200</h1>
                <h1 class='popupBody'>25 yrs = 117-166 / 195</h1>
                <h1 class='popupBody'>30 yrs = 114-162 / 190</h1>
                <h1 class='popupBody'>35 yrs = 111-157 / 185</h1>
                <h1 class='popupBody'>40 yrs = 108-153 / 180</h1>
                <h1 class='popupBody'>45 yrs = 105-149 / 175</h1>
                <h1 class='popupBody'>50 yrs = 102-145 / 170</h1>
                <h1 class='popupBody'>55 yrs = 99-140 / 165</h1>
                <h1 class='popupBody'>60 yrs = 96-136 / 160</h1>
                <h1 class='popupBody'>65 yrs = 93-132 / 155</h1>
                <h1 class='popupBody'>70 yrs = 90-123 / 150</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <h1 class='popupBody'>Here are some tips to reduce heart rate and maintain a healthy living!</h1>
                <br>
                <h1 class='popupBody'>1. Exercise More: Going on short walks, biking, swimming, or any other physical activities will gradually slower your resting BPM.</h1>
                <br>
                <h1 class='popupBody'>2. Reduce Stress: Meditating or some sort of activity that relieves stress will lower your resting BPM over time.</h1>
                <br>
                <h1 class='popupBody'>3. Avoid Tobacco: Smoking leads to an increase in your heart rate; therefore, quitting using tobacco products will reduce heart rate.</h1>
                <br>
                <h1 class='popupBody'>4. Lose Weight: Losing weight will make your heart work less since it doesn't have to supply your body as much with blood. Thus, less weight will lead to a lower BPM.</h1>
            </div>
        </div>
    </div>

    <button class="btnHow" v-on:click="togglePopup()">Medical Tips</button>
</template>

<script>
export default {
    name: 'Medical Tips',
    methods:{
    togglePopup(){
        document.getElementById("popup-3").classList.toggle("active");
        }
    }
}
</script>