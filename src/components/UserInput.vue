<template>
    <div>
        <img src="../assets/healthy.png">
        <br>
        <h1>Enter Steps Walked</h1>

        <form>
          <label for="fname"></label>
          <input type="text" id="steps" name="steps"><br>
        </form>

        <button class='btnActivity' v-on:click="togglePopup">Enter</button>
    </div>

    <div class="popup" id="popup-20">
        <div class="overlay"></div>
        <div class="content">
            <div class="close-btn" v-on:click="togglePopup()">&times;</div>
            <div>
                <h1 class='popupTitle'>20th PERCENTILE</h1>
                <img src="../assets/lazy.png">
                <h1 class='popupTitle'>NOT ACTIVE</h1>
                <br>
                <h1 class='popupBody'>You are in the 20th percentile of steps walked.</h1>
                <br>
                <h1 class='popupBody'>You seem to be lacking physical activity and need to incorporate more fitness habits in your daily life.</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <h1 class='popupTitle'>TIPS TO BECOME ACTIVE</h1>
                <h1 class='popupBody'>1. You need to increase the amount of daily steps walked by about 2000-4000 steps.</h1>
                <br>
                <h1 class='popupBody'>2. Understand when and where during the day you can find ways to incorporate more walking and exercising, such as between classes or before/after work.</h1>
                <br>
                <h1 class='popupBody'>3. Most importantly, just start somewhere. It's better to start sooner than later and it's easier to maintain consistency when you have a solid routine.</h1>
                <br>
                <h1 class='popupTitle'>TYPES OF EXERCISES</h1>
                <h1 class='popupBody'>High Intensity Interval Training (HIIT) is the most effective way of burning calories. The main purpose of it is to exercise using short bursts of energy. By doing this, HIIT is also very time efficient. Therefore, doing high intensity cardio in short intervals is the most beneficial way to lose weight.</h1>
                <br>
                <h1 class='popupTitle'>FIND A PARTNER</h1>
                <h1 class='popupBody'>Finding a partner is a key motivator for exercising. They help keep you accountable and maintain a fitness routine. Additionally, exercising when someone else can keep you engaged and have more fun.</h1>
                <br>
                <h1 class='popupTitle'>CHECK YOUR HEALTH</h1>
                <h1 class='popupBody'>Check out the "Medical Information" section to see where your BPM is and how it compares to your target BPM based on age.</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <br>
                <h1 class='popupBody'>Overall, your health may be at risk due to the low physical activity. Therefore, it's urgent to start being active right away.</h1>
                <h1 class='popupBody'>YOU CAN DO IT!</h1>
            </div>
        </div>
    </div>

    <div class="popup" id="popup-40">
        <div class="overlay"></div>
        <div class="content">
            <div class="close-btn" v-on:click="togglePopup()">&times;</div>
            <div>
                <h1 class='popupTitle'>40th PERCENTILE</h1>
                <img src="../assets/active.png">
                <h1 class='popupTitle'>ACTIVE</h1>
                <br>
                <h1 class='popupBody'>You are in the 40th percentile of steps walked.</h1>
                <br>
                <h1 class='popupBody'>You are doing pretty well and seem to be somewhat active.</h1>
                <h1 class='popupBody'>However, if you want to become highly active and improve your physical health even more, then here are some tips.</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <h1 class='popupTitle'>TIPS TO BECOME HIGHLY ACTIVE</h1>
                <h1 class='popupBody'>Increase the number of steps by about 1000-2000 steps.</h1>
                <h1 class='popupBody'>There are a variety ways to do this.</h1>
                <br>
                <h1 class='popupBody'>If you are a student: </h1>
                <h1 class='popupBody'>1. Walk between class buildings rather than bus.</h1>
                <h1 class='popupBody'>2. Find a good balance between academics and fitness.</h1>
                <h1 class='popupBody'>3. Do some exercises in between study breaks.</h1>
                <h1 class='popupBody'>4. Find other students of the same major and similar routine to walk with.</h1>
                <br>
                <h1 class='popupBody'>For people in general: </h1>
                <h1 class='popupBody'>1. Commute by walking or biking, using less vehicles.</h1>
                <h1 class='popupBody'>2. Take stairs when any chance possible rather than elevators or escalators.</h1>
                <h1 class='popupBody'>3. Start a daily routine where you walk a certain distance to form good habits.</h1>
                <br>
                <h1 class='popupBody'>Also, if you are employed, check out the "Fitness Tips" section to see about how many steps your getting based off your work environment.</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <br>
                <h1 class='popupBody'>Overall, you're doing fine and seem to be at a good pace without much risk. Just push yourself a little more and you'll be well off!</h1>
            </div>
        </div>
    </div>

    <div class="popup" id="popup-60">
        <div class="overlay"></div>
        <div class="content">
            <div class="close-btn" v-on:click="togglePopup()">&times;</div>
            <div>
                <h1 class='popupTitle'>60th PERCENTILE</h1>
                <img src="../assets/active.png">
                <h1 class='popupTitle'>ACTIVE</h1>
                <br>
                <h1 class='popupBody'>You are in the 60th percentile of steps walked.</h1>
                <br>
                <h1 class='popupBody'>You are doing pretty well and seem to be somewhat active.</h1>
                <h1 class='popupBody'>However, if you want to become highly active and improve your physical health even more, then here are some tips.</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <h1 class='popupTitle'>TIPS TO BECOME HIGHLY ACTIVE</h1>
                <h1 class='popupBody'>Increase the number of steps by about 1000-2000 steps.</h1>
                <h1 class='popupBody'>There are a variety ways to do this.</h1>
                <br>
                <h1 class='popupBody'>If you are a student: </h1>
                <h1 class='popupBody'>1. Walk between class buildings rather than bus.</h1>
                <h1 class='popupBody'>2. Find a good balance between academics and fitness.</h1>
                <h1 class='popupBody'>3. Do some exercises in between study breaks.</h1>
                <h1 class='popupBody'>4. Find other students of the same major and similar routine to walk with.</h1>
                <br>
                <h1 class='popupBody'>For people in general: </h1>
                <h1 class='popupBody'>1. Commute by walking or biking, using less vehicles.</h1>
                <h1 class='popupBody'>2. Take stairs when any chance possible rather than elevators or escalators.</h1>
                <h1 class='popupBody'>3. Start a daily routine where you walk a certain distance to form good habits.</h1>
                <br>
                <h1 class='popupBody'>Also, if you are employed, check out the "Fitness Tips" section to see about how many steps your getting based off your work environment.</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
                <br>
                <h1 class='popupBody'>Overall, you're doing fine and seem to be at a good pace without much risk. Just push yourself a little more and you'll be well off!</h1>
            </div>
        </div>
    </div>

    <div class="popup" id="popup-80">
        <div class="overlay"></div>
        <div class="content">
            <div class="close-btn" v-on:click="togglePopup()">&times;</div>
            <div>
                <h1 class='popupTitle'>80th PERCENTILE</h1>
                <img src="../assets/highlyactive.png">
                <h1 class='popupTitle'>HIGHLY ACTIVE</h1>
                <br>
                <h1 class='popupBody'>You are in the 80th percentile of steps walked.</h1>
                <br>
                <h1 class='popupBody'>You are doing very well and seem to be on track for a healthy and fit life!</h1>
                <h1 class='popupBody'>Keep doing what you're doing, and maybe use your knowledge to help others around you and motivate them to be more active.</h1>
                <br>
                <h1 class='popupBody'>It seems that you are physically active, but make sure that your internal health is also doing well, such as BPM and other factors.</h1>
                <br>
                <h1 class='popupBody'>Here is a reminder of what your target BPM should be.</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
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
                <br>
                <h1 class='popupBody'>Great job and stay active!</h1>
            </div>
        </div>
    </div>

    <div class="popup" id="popup-100">
        <div class="overlay"></div>
        <div class="content">
            <div class="close-btn" v-on:click="togglePopup()">&times;</div>
            <div>
                <h1 class='popupTitle'>100th PERCENTILE</h1>
                <img src="../assets/highlyactive.png">
                <h1 class='popupTitle'>HIGHLY ACTIVE</h1>
                <br>
                <h1 class='popupBody'>You are in the 100th percentile of steps walked.</h1>
                <br>
                <h1 class='popupBody'>You are doing very well and seem to be on track for a healthy and fit life!</h1>
                <h1 class='popupBody'>Keep doing what you're doing, and maybe use your knowledge to help others around you and motivate them to be more active.</h1>
                <br>
                <h1 class='popupBody'>It seems that you are physically active, but make sure that your internal health is also doing well, such as BPM and other factors.</h1>
                <br>
                <h1 class='popupBody'>Here is a reminder of what your target BPM should be.</h1>
                <h1 class='popupBody'>-------------------------------------------------------------------------------------</h1>
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
                <br>
                <h1 class='popupBody'>Great job and stay active!</h1>
            </div>
        </div>
    </div>
</template>

<script>


export default {
    name: 'UserInput',
    components: {

    },

    methods:{
        togglePopup(){

            var steps = document.getElementById("steps").value;

            if (steps <= 2044) {
                document.getElementById("popup-20").classList.toggle("active");
            }

            else if (steps <= 4089) {
                document.getElementById("popup-40").classList.toggle("active");
            }

            else if (steps <= 6134) {
                document.getElementById("popup-60").classList.toggle("active");
            }

            else if (steps <= 8179) {
                document.getElementById("popup-80").classList.toggle("active");
            }

            else {
                document.getElementById("popup-100").classList.toggle("active");
            }
        }
    }
}
</script>