<template>
<div id="app">
    <!-- Wrapper -->
    <div class="flex flex-col min-h-screen h-full lg:max-w-screen-lg mx-auto">
        <!-- Header -->
        <header class="lg:flex lg:pt-24">
            <div class="lg:flex lg:justify-center lg:w-1/2 xl:justify-start">
                <h1 class="font-ptserif font-bold text-4xl leading-2x-loose text-left align-top tracking-tighter py-4 px-3 text-black xl:flex-1">The creative crew</h1>
            </div>
            <div class="mt-4 px-3 lg:w-1/2">
                <h2 class="uppercase font-poppins font-semibold text-lg text-left align-top leading-7 text-black">Who we are</h2>
                <p class="font-poppins font-normal text-sm text-left align-top leading-5 mt-3 mr-8 text-black lg:w-76 lg:text-lg lg:leading-7">We are team of creatively diverse. driven. innovative individuals working in various locations from the world.</p>
            </div>
        </header>

        <!-- Main -->
        <main class="flex-1 my-16 lg:my-32 lg:flex">
            <div class="max-w-lg sm:max-w-lg sm:mx-auto lg:mx-0 lg:max-w-full">
                <div class="flex flex-wrap justify-around">
                    <div class="w-2/5 lg:w-26">
                        <div class="flex">
                            <img src="@/assets/images/photo1.png" alt="Bill Mahoney">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black lg:text-xs lg:leading-4">Product Owner</div>
                        </div>
                        <span class="inline-block font-poppins text-sm pt-3 font-semibold font-sm text-left align-top leading-5 lg:text-lg lg:leading-7 text-black">Bill Mahoney</span>
                    </div>
                    <div class="w-2/5 lg:w-26 mt-12 lg:mt-32">
                        <div class="flex">
                            <img src="@/assets/images/photo2.png" alt="Saba Cabrera">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black lg:text-xs lg:leading-4">Art Director</div>
                        </div>
                        <span class="inline-block font-poppins text-sm pt-3 font-semibold font-sm text-left align-top leading-5 lg:text-lg lg:leading-7 text-black">Saba Cabrera</span>
                    </div>
                    <div class="w-2/5 lg:w-26">
                        <div class="flex">
                            <img src="@/assets/images/photo3.png" alt="Shae Le">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black lg:text-xs lg:leading-4">Tech Lead</div>
                        </div>
                        <span class="inline-block font-poppins text-sm pt-3 font-semibold font-sm text-left align-top leading-5 lg:text-lg lg:leading-7 text-black">Shae Le</span>
                    </div>
                    <div class="w-2/5 lg:w-26 mt-12">
                        <div class="flex">
                            <img src="@/assets/images/photo4.png" alt="Skylah Lu">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black lg:text-xs lg:leading-4">UX Designer</div>
                        </div>
                        <span class="inline-block font-poppins text-sm pt-3 font-semibold font-sm text-left align-top leading-5 lg:text-lg lg:leading-7 text-black">Skylah Lu</span>
                    </div>
                    <div class="w-2/5 lg:w-26 lg:mt-32">
                        <div class="flex">
                            <img src="@/assets/images/photo5.png" alt="Griff Richards">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black lg:text-xs lg:leading-4">Developer</div>
                        </div>
                        <span class="inline-block font-poppins text-sm pt-3 font-semibold font-sm text-left align-top leading-5 lg:text-lg lg:leading-7 text-black">Griff Richards</span>
                    </div>
                    <div class="w-2/5 lg:w-26 mt-12">
                        <div class="flex">
                            <img src="@/assets/images/photo6.png" alt="Stan John">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black lg:text-xs lg:leading-4">Developer</div>
                        </div>
                        <span class="inline-block font-poppins text-sm pt-3 font-semibold font-sm text-left align-top leading-5 lg:text-lg lg:leading-7 text-black">Stan John</span>
                    </div>
                </div>
            </div>
        </main>
        <!-- Footer -->
        <footer>
            <div class="flex justify-center items-center">
                <div class="author font-montserrat font-semibold pb-6 text-sm leading-4">Nisarg Patel @ DevChallenges.io</div>
            </div>
        </footer>
    </div>
</div>
</template>

<script>
export default {
    name: 'App',
    components: {}
}
</script>

<style lang="scss">
#app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

.vertical-text {
    writing-mode: vertical-lr;
}

.author {
    color: #A9A9A9;
}
</style>
