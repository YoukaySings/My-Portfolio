<template>
    <div class="h-auto md:h-screen gridCenter mb-[100px] md:mb-[140px]">

         <!-- icon images -->
         <!-- <div class="flex justify-center items-center">
            <div class="w-full grid grid-cols-3 md:grid-cols-3 gap-6 md:gap-12 mt-10 md:mt-0">
                <div><img class="md:opacity-60" src="/icons/vue.svg" alt=""></div>
                <div class="w-full flex justify-center md:justify-center"><img class="md:opacity-60" src="/icons/tailwind.svg" alt=""></div>
                <div class="w-full flex justify-end md:justify-center"><img class="md:opacity-60" src="/icons/nuxt.svg" alt=""></div>
                <div><img class="md:opacity-70" src="/icons/bootstrap.svg" alt=""></div>
                <div class="w-full flex justify-center md:justify-center"><img class="md:opacity-60" src="/icons/javascript.svg" alt=""></div>
                <div class="w-full flex justify-end md:justify-center"><img class="md:opacity-40" src="/icons/git.svg" alt=""></div>
                <div><img class="md:opacity-40" src="/icons/adobe.svg" alt=""></div>
                <div class="w-full flex justify-center md:justify-center"><img class="md:opacity-40" src="/icons/figma.svg" alt=""></div>
                <div class="w-full flex justify-end md:justify-center"><img class="md:opacity-40" src="/icons/sketch.svg" alt=""></div>
            </div>
        </div> -->

        <div class="h-full flex flex-col justify-between gap-4">
            <div class="capitalize card">
                <p>html, css, javascript, vue.js, store, nuxt, vuex, tailwindcss, bootstrap, vuetify, git &amp; github, gitlab</p>
                <h2 class="circle relative flex items-end">web development</h2>
            </div>
            <br>
            <div class="capitalize card">
                <p>dialogue flows &amp; prototyping, UX Writing, user research, user interviews, wireframing, figma, figjam, adobe xd, webflow, sketch, agile ux design</p>
                <h2 class="circle relative flex items-end">ui/ux design</h2>
            </div>
            <br>
            <div class="capitalize card">
                <p>Problem solving and Time management, Prototyping & Wireframing, Information architecture, User research, UX Writing/Content, Visual design, Detail oriented, Visual design elements, Productivity, Adequate delivery, Great communication skills</p>
                <h2 class="circle relative flex items-end">Skills</h2>
            </div>
            <br>
            <div class="capitalize card">
                <p>Html, Css, Javascript, Vue.js, Vue 2, Vue 3, Vuex, Nuxt 2, Nuxt 3, Vuetify, Tailwind css, Bootstrap, Composition API, REST API.</p>
                <h2 class="circle relative flex items-end">Languages</h2>
            </div>
            <br>
        </div>
    </div>
</template>

<style scoped>

.circle::after {
  content: '';
  display: block;
  width: 10px; /* Adjust size of the circle */
  height: 10px;
  background-color: #0f0905; /* Tailwind's gray-600 color */
  border-radius: 50%; /* Fully round */
  position: absolute;
  left: -6px; /* Center it relative to the border */
  bottom: -10px; /* Position it at the bottom of the div */
}


img{
    width: 50px;
    height: 50px;
}

p{
    font-size: 16px;
    font-weight: 300;
    width: 90%;
    line-height: 26px;
    word-break: break-all;
}

@media (min-width: 768px) {
    img {
        width: 100px;
        height: 100px;
    }
}

@media (max-width: 768px) {
    p {
        width: 100%;
        font-size: 16px;
    }
}
</style>