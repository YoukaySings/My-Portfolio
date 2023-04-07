<template>
    <div class="wrapper h-screen md:h-auto">

        <div class="flex justify-center md:justify-start items-center text-center md:text-left">
            <div>
            <h2 class="text-xl md:text-3xl pb-2 mb-3 border-b-[0.2px] font-light border-gray-500/50">IDRIS TESLIM O.</h2>
            <h2 class="text-[32px] md:text-[60px] leading-[28px] md:leading-[48px] font-bold mt-6">FRONT-END DEVELOPER</h2>
            <p class="md:text-[24px] mt-3">&amp;</p>
            <h2 class="text-[24px] md:text-[40px] tracking-[3px]">UI/UX DESIGNER</h2>
            <i>With Over <b>Two Years</b> Of Experience</i>
            <br>
            <div class="mt-6 md:mt-8">
                <NuxtLink to="https://github.com/YoukaySings"><icon class="socialicon mr-8" name="uil:github"/></NuxtLink>
                <NuxtLink to="iteslimidris09@gmail.com"><icon class="socialicon" name="uil:envelope"/></NuxtLink>
                <NuxtLink to="https://www.linkedin.com/in/teslim-idris-7a1695215/"><icon class="socialicon ml-8" name="uil:linkedin"/></NuxtLink>
            </div>
            <NuxtLink to="https://docs.google.com/document/d/e/2PACX-1vTOyt24_tCV-ZwTqlUDl0EKEiPfJZwLoX9svu53EqvMopGGyETWdL44mOThQtV6zXcM9KnuUwsMLhZv/pub" class="hidden md:inline-flex">
            <button class="custom-btn mt-20 items-center inline-flex">VIEW RESUME <icon class="ml-2 text-[20px]" name="uil:book-open"/></button>
            </NuxtLink>
            </div>
        </div>


        <div class="bg-[url('/mobile.svg')] background w-full h-auto md:h-full rounded-lg">
        </div>
        <div class="md:hidden w-full flex justify-center relative top-[-30px]">
        <img class="w-[400px]" src="/mobile.svg" alt="">
        </div>

            <NuxtLink to="https://docs.google.com/document/d/e/2PACX-1vTOyt24_tCV-ZwTqlUDl0EKEiPfJZwLoX9svu53EqvMopGGyETWdL44mOThQtV6zXcM9KnuUwsMLhZv/pub" class="md:hidden inline-flex justify-center relative top-[-30px]">
            <button class="mobile-custom-btn mb-10 items-center inline-flex">VIEW RESUME</button>
            </NuxtLink>
    </div>
</template>

<style scoped>
.socialicon {
    font-size: 28px;
}

.socialicon:hover {
    color: #f3af64;
}
</style>