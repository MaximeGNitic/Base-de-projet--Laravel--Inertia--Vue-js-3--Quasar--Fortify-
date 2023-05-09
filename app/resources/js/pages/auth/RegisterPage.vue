<script setup>

</script>

<template>
    <div>
        <h4>Register</h4>
        <form @submit="registerForm">
            <input class="bg-blue-grey-2" label="Nom" v-model="nom"/>
            <input class="bg-blue-grey-2" label="Email" v-model="email"/>
            <input class="bg-blue-grey-2" label="Mot de passe" v-model="password"/>
            <input class="bg-blue-grey-2" label="Confirmer le mot de passe" v-model="confirmPassword"/>

            <btn class="bg-blue-grey-2" label="Submit" type="submit"/>
        </form> 
    </div>
</template>

<style>

</style>