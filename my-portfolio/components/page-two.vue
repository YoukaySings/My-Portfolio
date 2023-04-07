<template>
    <div class="wrapper">
        <div>
            <h2 class="header">Frameworks &amp; Tools</h2>
            <br>
            <div class="capitalize">
                <h2 class="md:text-[20px] md:tracking-[3px] uppercase font-bold">web development</h2>
                <p>html, css, javascript, vue.js, store, nuxt, vuex, tailwindcss, bootstrap, vuetify, git &amp; github, gitlab</p>
            </div>

            <br>
            <div class="capitalize">
                <h2 class="md:text-[20px] md:tracking-[3px] uppercase font-bold">ui/ux design</h2>
                <p>dialogue flows &amp; prototyping, user research, user interviews, wireframing, figma, figjam, adobe xd, webflow, sketch, agile ux design</p>
            </div>
            <br>
            <div class="capitalize">
                <h2 class="md:text-[20px] md:tracking-[3px] uppercase font-bold">Skills</h2>
                <p>Problem solving, Interpersonal relation, Object oriented, Design oriented</p>
            </div>
            <br>
            <div class="capitalize">
                <h2 class="md:text-[20px] md:tracking-[3px] uppercase font-bold">Languages</h2>
                <p>javascript</p>
            </div>
        </div>
        <div class="flex justify-center items-center">
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
        </div>
    </div>
</template>

<style scoped>
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