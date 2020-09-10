<template>
<div id="app">
    <!-- Wrapper -->
    <div class="flex flex-col min-h-screen h-full">
        <!-- Header -->
        <header>
            <div>
                <h1 class="font-ptserif font-bold text-4xl leading-2x-loose text-left align-top tracking-tighter py-4 px-3 text-black">The creative crew</h1>
            </div>
            <div class="mt-8">
                <h2 class="uppercase font-poppins font-semibold text-lg text-left align-top px-3 leading-5 text-black">Who we are</h2>
                <p class="font-poppins font-normal text-sm text-left align-top leading-5 mt-3 pl-3 pr-4 text-black">We are team of creatively diverse. driven. innovative individuals working in various locations from the world.</p>
            </div>
        </header>

        <!-- Main -->
        <main class="flex-1">
            <!-- Team members -->
            <div>
                <!-- Row 1 -->
                <div class="flex px-5">
                    <div class="flex">
                        <div>
                            <div class="flex items-end h-64 w-32">
                                <img src="@/assets/images/photo1.png" alt="">
                            </div>
                            <span class="inline-block font-poppins pt-3 font-semibold font-sm text-left align-top leading-5 text-black">Bill Mahoney</span>
                        </div>
                        <div class="flex items-center justify-center h-64">
                            <div class="vertical-text font-ptserif text-xs uppercase align-top leading-4 text-left font-normal text-black">Product Owner</div>
                        </div>
                    </div>
                    <!-- <div>
                        <img src="@/assets/images/photo2.png" alt="">
                    </div> -->
                </div>
                <!-- Row 2 -->
                <div>

                </div>
                <!-- Row 3 -->
                <div>

                </div>
            </div>
        </main>
        <!-- Footer -->
        <footer>
            <div>
                <span class="font-montserrat font-semibold">Nisarg Patel @ DevChallenges.io</span>
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
.vertical-text{
  writing-mode: vertical-lr;
}
</style>
