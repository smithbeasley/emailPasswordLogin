<template>
<div class="mt-8">
    <p class="text-2xl text-center mx-auto m-8 tracking-wider">Welcome {{user?.email || 'New User'}} </p>
 <img src="../assets/home.svg" alt="Home" class="h-40 mx-auto mt-40"> 
</div>
</template>

<script setup>
import {user} from '../helpers/useAuth'
</script>