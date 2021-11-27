<template>
    <header>
        <div class = "headerbg">
            <h1 class='welcome'>App Athletics</h1>
            <HowToUseButton />
            <UserInput />
        </div>
    </header>
</template>

<script>
import HowToUseButton from './HowToUseButton'
import UserInput from './UserInput'

export default {
    name: 'Header',
    components: {
        HowToUseButton,
        UserInput,
    }
}
</script>