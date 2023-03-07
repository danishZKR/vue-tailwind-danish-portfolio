<template>
    <section class="w-full flex py-16 px-20 h-auto">
        <div class="w-1/4 h-auto flex flex-col gap-5">
            <p class="cursor-pointer" @click="chengeEducation">{{education}}</p>
            <p>Experience</p>
            <p>Skills</p>
            <p>Projects</p>
            <p>Languages</p>
            <p>Hobbies</p>
        </div>
        <div class="w-3/4">
            <div class="flex flex-col gap-5">
                <!-- Education -->
                <h1 class="text-indigo-900 text-4xl font-bold">Education</h1>
                <div class="flex flex-col gap-5">
                    <div class="flex gap-5">
                        <span class="text-indigo-900 p-2 text-4xl">
                            <i class="fa-solid fa-graduation-cap"></i>
                        </span>
                        <div class="flex flex-col gap-2">
                            <p class="text-indigo-900 text-xl font-bold">2014 - 2017</p>
                            <p class="text-2xl font-bold pb-2">Bachelor of Computer Science</p>
                            <p class="text-xl font-bold">Osmania University, Hyderabad, India</p>
                            <p class="text-md text-gray-400">Specialized in Coputer Applications</p>
                        </div>
                    </div>
                    <div class="border-b"></div>
                    <div class="flex gap-5">
                        <span class="text-indigo-900 p-2 text-4xl">
                            <i class="fa-solid fa-graduation-cap"></i>
                        </span>
                        <div class="flex flex-col gap-2">
                            <p class="text-indigo-900 text-xl font-bold">2016 - 2017</p>
                            <p class="text-2xl font-bold pb-2">Diploma in Management</p>
                            <p class="text-xl font-bold">Osmania University, Hyderabad, India</p>
                            <p class="text-md text-gray-400">Development Management Studies & Development Research Methodologies</p>
                        </div>
                    </div>
                    <div class="border-b"></div>
                    <div class="flex gap-5">
                        <span class="text-indigo-900 p-2 text-4xl">
                            <i class="fa-solid fa-graduation-cap"></i>
                        </span>
                        <div class="flex flex-col gap-2">
                            <p class="text-indigo-900 text-xl font-bold">2011 - 2012</p>
                            <p class="text-2xl font-bold pb-2">Baccalaureate, High School</p>
                            <p class="text-xl font-bold">Khatamul-Anbia High School, Poli-khumri, Baghlan, Afghanistan</p>
                            <p class="text-md text-gray-400">Graduated province level top scorer</p>
                        </div>
                    </div>
                    <div class="border-b"></div>
                </div>
                <!-- Experience -->
                <h1 class="text-indigo-900 text-4xl font-bold pt-20">Experience</h1>
                <div class="flex flex-col gap-5">
                    <div class="flex gap-5 pt-5">
                        <span class="text-indigo-900 p-2 text-4xl">
                            <i class="fa-solid fa-briefcase"></i>
                        </span>
                        <div class="flex flex-col gap-2">
                            <p class="text-indigo-900 text-xl font-bold"> Feb 2021 - Current</p>
                            <p class="text-2xl font-bold pb-2">Software Development Deputy Manager</p>
                            <p class="text-xl">Da Afghanistan Bank (Central Bank of Afghanistan), Kabul, Afghanistan</p>
                            <ul class="text-gray-400 list-disc pl-10 pt-2 flex flex-col gap-2">
                                <li>Making plans to design new applications for automating the manual processes</li>
                                <li>Monitoring progress throughout the application SDLC process</li>
                                <li>Onboarding the new software developers on the team</li>
                                <li>Submitting proposals and progress reports to upper management</li>
                                <li>Creating and maintaining a healthy workplace environment</li>
                                <li>Explaining application use to the clients</li>
                            </ul>
                        </div>
                    </div>
                    <div class="border-b"></div>
                    <div class="flex gap-5">
                        <span class="text-indigo-900 p-2 text-4xl">
                            <i class="fa-solid fa-briefcase"></i>
                        </span>
                        <div class="flex flex-col gap-2">
                            <p class="text-indigo-900 text-xl font-bold">Mar 2018 - Feb 2021</p>
                            <p class="text-2xl font-bold pb-2">Software Developer</p>
                            <p class="text-xl">Netlinks LTD, Kabul, Afghanistan</p>
                            <ul class="text-gray-400 list-disc pl-10 pt-2 flex flex-col gap-2">
                                <li>Proficiently worked as Odoo ERP Developer</li>
                                <li>Involved as a key developer in many enterprise applications</li>
                                <li>Proficiently customized Odoo ERP to meet many client requirements</li>
                                <li>Migrated successfully old systems into new systems by the help of python scripts as middleware</li>
                                <li>Trained and supported many newly joined developers</li>
                                <li>Collaborated with a skilled software engineering team, utilizing agile methodologies</li>
                            </ul>
                        </div>
                    </div>
                    <div class="border-b"></div>
                    <div class="flex gap-5">
                        <span class="text-indigo-900 p-2 text-4xl">
                            <i class="fa-solid fa-briefcase"></i>
                        </span>
                        <div class="flex flex-col gap-2">
                            <p class="text-indigo-900 text-xl font-bold">Aug 2017 - Sep 2019 | Part-time</p>
                            <p class="text-2xl font-bold pb-2">University Lecturer</p>
                            <p class="text-xl">Alamah University | Maiwand University</p>
                            <ul class="text-gray-400 list-disc pl-10 pt-2 flex flex-col gap-2"> 
                                <li> Instruct students on Javascript and other relevant technologies</li>
                                <li>Instruct students on how computers work, including the basic science and mathematics behind their operation and the hardware and the software built on those foundations</li>
                                <li>Teach how to write computer programs and algorithms.</li>
                                <li>Keep records of grades, grade papers, and perform other administrative duties as needed</li>
                                <li>Create projects designed to enhance classroom activities</li>
                                <li>Read and stay abreast of current topics in computer science</li>
                                <li>Create lesson plans</li>
                                <li>Utilize various curriculum resources</li>
                                <li>Integrate competencies, goals, and objectives into lesson plans</li>
                                <li>Utilize curricula that reflect the diverse educational, cultural, and linguistic backgrounds of the students served</li>
                                <li>Utilize professional development opportunities to increase computer science knowledge and pedagogical skills</li>
                                <li>Work with the administration and technology team to ensure initiatives are being met</li>
                                <li>Tutor students on an individual basis</li>
                            </ul>
                        </div>
                    </div>
                    <div class="border-b"></div>
                </div>
                <!-- Skills -->
                <h1 class="text-indigo-900 text-4xl font-bold pt-20">Skills</h1>
                <div class="flex flex-col gap-10">
                    <div class="flex gap-5">
                        <div class="flex flex-col justify-center w-52 shadow-2xl py-5 gap-2" v-for="skill in expSkills" :key="skill.title">
                            <p class="text-center text-xl">{{skill.title}}</p>
                            <svg class="pl-[25px]">
                                <circle cx="80" cy="80" r="60" stroke="currentColor" stroke-width="15" fill="transparent"
                                class="text-gray-700" />
                                <circle cx="80" cy="80" r="60" stroke="currentColor" stroke-width="15" fill="transparent"
                                :stroke-dasharray="2 * 22 / 7 * 60"
                                :stroke-dashoffset="(2 * 22 / 7 * 60) - `${skill.percent}`/100 * (2 * 22 / 7 * 60)"
                                class="text-indigo-600" />
                            </svg>
                            <p class="absolute pl-[85px] pb-[75px] text-xl font-bold">{{skill.percent}}%</p>
                            <div class="border-b pt-2 mb-2"></div>
                            <p class="text-center">{{skill.level}}</p>
                            <p class="text-center text-gray-400">for</p>
                            <p class="text-center text-xl">{{skill.experience}} Years</p>
                        </div>
                    </div>
                    <div class="flex flex-wrap gap-10">
                        <div v-for="skill in skills" :key="skill.title" class="flex flex-col w-[425px]">
                            <div class="flex justify-between mb-1">
                                <span class="text-base font-medium text-indigo-900 dark:text-white">{{skill.title}}</span>
                                <span class="text-sm font-medium text-indigo-900 dark:text-white">{{skill.percent}}%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2.5 dark:bg-gray-700">
                                <div class="bg-indigo-600 h-2.5 rounded-full" :style="`width: ${skill.percent}%`"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- Projects -->
                <h1 class="text-indigo-900 text-4xl font-bold pt-20">Implemented Projects</h1>
                <div class="flex flex-col gap-5 text-xl">
                    <div class="flex gap-5 items-center">
                        <i class="fa-solid fa-circle-check text-indigo-900"></i>
                        <p class="text-gray-600">POS & Financial App for Saharpaz Restaurant | <span class="italic text-sm font-bold text-indigo-900">Freelance</span></p>
                    </div>
                    <div class="flex gap-5 items-center">
                        <i class="fa-solid fa-circle-check text-indigo-900"></i>
                        <p class="text-gray-600">POS & Financial App for Friends Bowling and Caffee | <span class="italic text-sm font-bold text-indigo-900">Freelance</span></p>
                    </div>
                    <div class="flex gap-5 items-center">
                        <i class="fa-solid fa-circle-check text-indigo-900"></i>
                        <p class="text-gray-600">MIS for Gulzad Groub of Companies | <span class="italic text-sm font-bold text-indigo-900">Freelance</span></p>
                    </div>
                    <div class="flex gap-5 items-center">
                        <i class="fa-solid fa-circle-check text-indigo-900"></i>
                        <p class="text-gray-600">Netlinks LTD | <span class="italic text-sm font-bold text-indigo-900">Employment</span></p>
                    </div>
                    <div class="flex gap-5 items-center">
                        <i class="fa-solid fa-circle-check text-indigo-900"></i>
                        <p class="text-gray-600">Da Afghanistan Bank | <span class="italic text-sm font-bold text-indigo-900">Employment</span></p>
                    </div>
                </div> 
                <!-- Languages -->
                <h1 class="text-indigo-900 text-4xl font-bold pt-20">Languages</h1>
                <div v-for="lang in languages" :key="lang.title" class="flex flex-col gap-5">
                    <div  class="flex items-center gap-5 shadow-lg p-4">
                        <i class="fa-solid fa-language text-indigo-900 p-2"></i>
                        <p class="text-gray-600">{{lang.name}}</p>
                        <p class="text-gray-400">{{ lang.level }}</p>
                    </div>
                </div>
                <!-- Hobbies -->
                <h1 class="text-indigo-900 text-4xl font-bold pt-20">Hobbies</h1>
                <div class="flex flex-col gap-2"> 
                    <p class="text-gray-500 shadow-lg p-3">Reading about trend technologies</p>
                    <p class="text-gray-500 shadow-lg p-3">Reading and solving programming challanges</p>
                    <p class="text-gray-500 shadow-lg p-3">Reading critical thinking books</p>
                    <p class="text-gray-500 shadow-lg p-3">Fan of political discussions</p>
                    <p class="text-gray-500 shadow-lg p-3">Watching & Playing football occasionally with friends</p>
                    <p class="text-gray-500 shadow-lg p-3">Enjoy being with family</p>
                </div> 
            </div> 
            
        </div>
    </section>
</template>

<script setup>
import { ref } from 'vue';

const education = ref("Education")

function chengeEducation(){
    education.value = '- ' + education.value
}
 
const languages = [
    {
        name: "Persian",
        level: "Native | Full Professional Proficiency"
    },
    {
        name: "English",
        level: "Professional Working Proficiency"
    },
    {
        name: "Hindi",
        level: "Intermediate Working Proficiency"
    },
    {
        name: "Pashto",
        level: "Intermediate Working Proficiency"
    }
]

const expSkills = [
    {
        title: 'Python',
        percent: 95,
        experience: '3+',
        level: 'Proficientl Experience'
    },
    {
        title: 'Odoo ERP',
        percent: 95,
        experience: '3+',
        level: 'Proficientl Experience'
    },
    {
        title: 'PostgreSQL',
        percent: 90,
        experience: '3',
        level: 'Proficientl Experience'
    },
    {
        title: 'JavaScript',
        percent: 85,
        experience: '3+',
        level: 'Intermediate Experience'
    }
]

const skills = [
    {
        title: 'React JS',
        percent: 85
    },
    {
        title: 'Vue JS',
        percent: 85
    },
    {
        title: 'PHP & Laravel',
        percent: 80
    },
    {
        title: 'SQL',
        percent: 85
    },
    {
        title: 'HTML & CSS',
        percent: 85
    },
    {
        title: 'Tailwind CSS',
        percent: 80
    },
    {
        title: 'Bootstrap',
        percent: 75
    },
    {
        title: 'Git & Github',
        percent: 90
    }
]
</script>