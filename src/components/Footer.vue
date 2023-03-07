<template>
    <footer class="w-full bg-gray-800 text-white">
        <div class="flex flex-col gap-5 py-10 px-44">
            <div class="flex justify-between">
                <div class="flex flex-col gap-5">
                    <h1 class="text-center text-xl uppercase border-b border-gray-500">Links</h1>
                    <span class="flex gap-5 items-center cursor-pointer">
                        <i class="fa-solid fa-house"></i>
                        <p class="hover:border-b">Home</p>
                    </span>
                    <span class="flex gap-5 items-center cursor-pointer">
                        <i class="fa-solid fa-address-card"></i>
                        <p class="hover:border-b">About</p>
                    </span>
                    <span class="flex gap-5 items-center cursor-pointer">
                        <i class="fa-solid fa-file"></i>
                        <p class="hover:border-b">Resume</p>
                    </span>
                    <span class="flex gap-5 items-center cursor-pointer">
                        <i class="fa-solid fa-code"></i>
                        <p class="hover:border-b">Services</p> 
                    </span>
                    <span class="flex gap-5 items-center cursor-pointer">
                        <i class="fa-solid fa-message"></i>
                        <p class="hover:border-b">Contact</p>
                    </span>
                </div>
                <div class="flex flex-col gap-5">
                    <h1 class="text-center text-xl uppercase border-b border-gray-500">Services</h1>
                    <span class="flex gap-5 items-center cursor-pointer">
                        <i class="fa-solid fa-code"></i>
                        <p class="hover:border-b">Web Development</p>
                    </span>
                    <span class="flex gap-5 items-center cursor-pointer">
                        <i class="fa-regular fa-window-restore"></i>
                        <p class="hover:border-b">MIS Development</p>
                    </span>
                    <span class="flex gap-5 items-center cursor-pointer">
                        <i class="fa-solid fa-database"></i>
                        <p class="hover:border-b">Database Development</p>
                    </span>
                </div>
                <div class="flex flex-col gap-5">
                    <h1 class="text-center text-xl uppercase border-b border-gray-500">Reach Me In</h1>
                    <a class="flex gap-5 items-center cursor-pointer" href="https://www.linkedin.com/in/danishZKR"> 
                        <i class="fa-brands fa-linkedin"></i>
                        <p class="hover:border-b">Linkedin</p>
                    </a>
                    <a  class="flex gap-5 items-center cursor-pointer" href="https://github.com/danishZKR">
                        <i class="fa-brands fa-github"></i>
                        <p class="hover:border-b">Github</p>
                    </a>
                    <a  class="flex gap-5 items-center cursor-pointer" href="https://twitter.com/danishZKR">
                        <i class="fa-brands fa-twitter"></i>
                        <p class="hover:border-b">Twitter</p>
                    </a>
                    <a  class="flex gap-5 items-center cursor-pointer" href="https://www.facebook.com/danishZKR" >
                        <i class="fa-brands fa-facebook"></i>
                        <p class="hover:border-b">Facebook</p>
                    </a>
                  
                </div>
            </div>
            <div class="border-b border-gray-600"></div>
            <p class="text-center">© 2023. All Reights Reserved.</p>
        </div>
    </footer>
</template>

<script setup>
import {RouterLink} from 'vue-router'
</script>