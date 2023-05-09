<script setup>

</script>

<template>
    <div>
        <h4 class="text-blue-grey-2 text-center">Login</h4>
        <form @submit="loginForm">
            <input class="bg-blue-grey-2" label="Email" v-model="email"/>
            <input class="bg-blue-grey-2" label="Mot de passe" v-model="password"/>

            <btn class="bg-blue-grey-2" label="Submit" type="submit"/>
        </form>
    </div>
</template>

<style>

</style>