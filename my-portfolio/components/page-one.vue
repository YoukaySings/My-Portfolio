<template>
    <div class="wrapper">
        <div>
            <h2 class="text-3xl pb-2 mb-3 border-b-[0.2px] border-gray-500/50">IDRIS TESLIM O.</h2>
            <h2 class="text-[54px] md:text-[60px] leading-[48px] font-bold mt-6">FRONT-END DEVELOPER</h2>
            <p class="text-[24px] mt-3">&amp;</p>
            <h2 class="text-[40px] tracking-[3px]">UI/UX DESIGNER</h2>
            <i>With Over <b>Two Years</b> Of Experience</i>
            <br>
            <div class="mt-8">
                <NuxtLink to=""><icon class="socialicon" name="uil:github"/></NuxtLink>
                <NuxtLink to=""><icon class="socialicon" name="uil:envelope"/></NuxtLink>
                <NuxtLink to=""><icon class="socialicon" name="uil:linkedin"/></NuxtLink>
            </div>

            <button class="custom-btn mt-20 flex items-center">VIEW RESUME <icon class="ml-2 text-[20px]" name="uil:book-open"/></button>

        </div>

        <div class="bg-[url('/image-01.svg')] background w-12/12 h-full rounded-lg overflow-hidden">
        </div>
    </div>
</template>

<style scoped>
.socialicon{
    font-size: 24px;
    margin-right: 12px;
}

.socialicon:hover {
    color: #f3af64;
}
</style>