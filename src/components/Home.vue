<template>
    <div>
        <h1>Trade or View your Portfolio</h1>
        <h4>You may Save & Load your Data</h4>
        <h4>Click on 'End Day' to begin a New Day!</h4>
        <hr>
        <h4 style="color: grey">Your Funds: {{ funds }}</h4>
    </div>
</template>

<script>
export default {
    computed: {
        funds() {
            return this.$store.getters.funds;
        }
    }
}
</script>