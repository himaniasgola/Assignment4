<template>
    <div class="component">
        <h3>You may view the User Details here</h3>
        <p>Many Details</p>
        <p>UserName: {{ myName }}</p>
        <p>UserAge: {{ userAge }}</p>
    </div>
</template>

<script>
export default {
    props: {
        myName: {
            type: String
        },
        userAge: Number
    } 
}

</script>
<style scoped>
    div {
        background-color: lightcoral;
    }
</style>
