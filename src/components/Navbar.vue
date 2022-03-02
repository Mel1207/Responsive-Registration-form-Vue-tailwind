<template>
    <nav class="navbar">
        <div class="container flex items-center justify-between mx-auto md:px-20">
            <a href="#!" class="text-2xl" >LOGO</a>

            <ul class="flex items-center">
                <li class="ml-8"><router-link to="/">Home</router-link></li>
                <li class="ml-8"><router-link to="/about">About</router-link></li>
                <li class="ml-8">Blog</li>
                <li class="ml-8">Contact</li>
                <li><router-link to="/contact" class="ml-8 btn-line">Login</router-link></li>
            </ul>
        </div>
    </nav>
    <router-view />
</template>

<script>
export default {

}
</script>