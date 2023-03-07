<template>
    <section class="w-full h-screen flex flex-col justify-center  bg-gradient-to-r from-teal-900 mt-[-6rem]">
        <div class="m-auto flex flex-col items-center gap-4 font-bold uppercase">
            <p class="text-3xl">H e y ! I a m</p>
            <p class="text-5xl">Zikrullah Danish</p>
            <p class="text-3xl italic text-blue-900">{{ skill }}</p>
        </div>
    </section>
</template>

<script setup>
import { ref } from 'vue';

const skills = [
    'Odoo Developer', 'Python Developer', 'Software Developer'
]

const skill = ref(skills[0])
const counter = ref(0)

function changeSkill(){
    skill.value = skills[counter.value];
}
 
setInterval(()=>{
    if(skills.length === counter.value){
        counter.value = 0
    }
    changeSkill()
    counter.value = counter.value + 1
}, 3000)
</script>