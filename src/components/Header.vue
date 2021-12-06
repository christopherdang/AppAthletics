<template>
    <header>
        <div class = "headerbg">
            <h1>App Athletics</h1>
            <HowToUseButton />
            <UserInput />
            <FitnessTips />
            <MedicalTips />
        </div>
    </header>
</template>

<script>
import HowToUseButton from './HowToUseButton'
import UserInput from './UserInput'
import FitnessTips from './FitnessTips'
import MedicalTips from './MedicalTips'

export default {
    name: 'Header',
    components: {
        HowToUseButton,
        UserInput,
        FitnessTips,
        MedicalTips,
    }
}
</script>