<template>
<div id="app">
    <!-- Wrapper -->
    <div class="flex flex-col min-h-screen h-full lg:max-w-screen-lg mx-auto">
        <!-- Header -->
        <header class="lg:flex">
            <div class="lg:w-1/2">
                <h1 class="font-ptserif font-bold text-4xl leading-2x-loose text-left align-top tracking-tighter py-4 px-3 text-black">The creative crew</h1>
            </div>
            <div class="mt-4 px-3 lg:w-1/2">
                <h2 class="uppercase font-poppins font-semibold text-lg text-left align-top leading-5 text-black">Who we are</h2>
                <p class="font-poppins font-normal text-sm text-left align-top leading-5 mt-3 mr-8 text-black">We are team of creatively diverse. driven. innovative individuals working in various locations from the world.</p>
            </div>
        </header>

        <!-- Main -->
        <main class="flex-1 my-16">
            <div class="max-w-lg sm:max-w-lg sm:mx-auto lg:mx-0">
                <div class="flex flex-wrap justify-around">
                    <div class="w-2/5">
                        <div class="flex">
                            <img src="@/assets/images/photo1.png" alt="Bill Mahoney">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black">Product Owner</div>
                        </div>
                        <span class="inline-block font-poppins pt-3 font-semibold font-sm text-left align-top leading-5 text-black">Bill Mahoney</span>
                    </div>
                    <div class="w-2/5 mt-12">
                        <div class="flex">
                            <img src="@/assets/images/photo2.png" alt="Saba Cabrera">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black">Art Director</div>
                        </div>
                        <span class="inline-block font-poppins pt-3 font-semibold font-sm text-left align-top leading-5 text-black">Saba Cabrera</span>
                    </div>
                    <div class="w-2/5">
                        <div class="flex">
                            <img src="@/assets/images/photo3.png" alt="Shae Le">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black">Tech Lead</div>
                        </div>
                        <span class="inline-block font-poppins pt-3 font-semibold font-sm text-left align-top leading-5 text-black">Shae Le</span>
                    </div>
                    <div class="w-2/5 mt-12">
                        <div class="flex">
                            <img src="@/assets/images/photo4.png" alt="Skylah Lu">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black">UX Designer</div>
                        </div>
                        <span class="inline-block font-poppins pt-3 font-semibold font-sm text-left align-top leading-5 text-black">Skylah Lu</span>
                    </div>
                    <div class="w-2/5">
                        <div class="flex">
                            <img src="@/assets/images/photo5.png" alt="Griff Richards">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black">Developer</div>
                        </div>
                        <span class="inline-block font-poppins pt-3 font-semibold font-sm text-left align-top leading-5 text-black">Griff Richards</span>
                    </div>
                    <div class="w-2/5 mt-12">
                        <div class="flex">
                            <img src="@/assets/images/photo6.png" alt="Stan John">
                            <div class="vertical-text font-ptserif text-xxs uppercase align-top leading-3 text-left font-normal text-black">Developer</div>
                        </div>
                        <span class="inline-block font-poppins pt-3 font-semibold font-sm text-left align-top leading-5 text-black">Stan John</span>
                    </div>
                </div>
            </div>
        </main>
        <!-- Footer -->
        <footer>
            <div class="flex justify-center items-center">
                <div class="author font-montserrat font-semibold pb-6">Nisarg Patel @ DevChallenges.io</div>
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
