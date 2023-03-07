<template>
    <section class="w-full px-20 py-10">
        <h1 class="text-4xl text-center py-10 font-bold">My Services</h1>
        <div class="flex gap-10 items-center">
            <div v-for="service in services" :key="service.name" class="flex flex-col gap-5 items-center shadow-2xl p-5 hover:bg-gray-400 cursor-pointer rounded-2xl py-10">
                <span class="text-4xl text-indigo-900">
                    <i :class="`${service.classIcon}`"></i>
                </span>
                <p class="text-2xl shadow-2xl p-5 rounded-xl">{{service.name}}</p>
                <p class="text-sm text-gray-500 text-center">{{service.discription}}</p>
            </div>
        </div>
    </section>
</template>

<script setup>
const services = [
    {
        classIcon: 'fa-solid fa-code',
        name: 'Web Development',
        discription: 'Full stack web development using latest web technologies'
    },
    {
        classIcon: 'fa-regular fa-window-restore',
        name: 'MIS Development',
        discription: 'Advance MIS develoment with Odoo ERP & other latest technologies'
    },
    {
        classIcon: 'fa-solid fa-database',
        name: 'Database Development',
        discription: 'Advance Database Development with latest RDBMS(s)'
    } 
]
</script>