<template>
<div class="container md:mt-64 mt-10 flex justify-between items-center mx-auto px-8 md:px-14 lg:px-24 w-full" id="about">
        <section class="w-full">
            <h2 id="clients" class="secondary-title">Who am I?</h2>
            <p class="section-paragraph">I'm software engineer student passionate for IT world.<br><span class="font-bold">"The power of code is beyond imagination"</span> </p>

            <!-- Clients -->
            <div class="space-y-12 mt-10">
                <div class="w-full p-16 lg:px-32 lg:py-20 lg:space-x-32 flex justify-center lg:justify-start flex-wrap lg:flex-nowrap">
                    
                    <!-- Client logo -->
                    <div class="mb-6 lg:mb-0">
                        <img src="@/assets/programming-svgrepo-com.svg" alt="programming">
                    </div>

                    <!-- Client info -->
                    <div class="flex flex-wrap justify-center text-center lg:text-left lg:block">
                        <h3 class="text-3xl font-semibold">Tech Skills.</h3>

                        <div class="w-full lg:w-auto flex flex-wrap justify-center lg:justify-start gap-3 mt-6 mb-8">
                            <div class="badge text-white">Backend development</div>
                            <div class="badge text-white">Frontend development</div>
                        </div>

                        <p class="text-secondary text-justify">I handle several tools for different types of web pages, like web apps or Spas. this is my full-stack: Html, Css, Javascript, Git, Php, Laravel, Vue, Scss, Tailwind, Bootstrap, Sql and few others.</p>
                    </div>

                </div>
                <div class="w-full p-16 lg:px-32 lg:py-20 lg:space-x-32 flex justify-center lg:justify-start flex-wrap lg:flex-nowrap">
                    <div class="mb-6 lg:mb-0">
                        <img src="@/assets/skill-svgrepo-com.svg" alt="mind">
                    </div>
                    <div class="flex flex-wrap justify-center text-center lg:text-left lg:block">
                        <h3 class="text-3xl font-semibold">Soft Skills.</h3>

                        <div class="w-full lg:w-auto flex flex-wrap justify-center lg:justify-start gap-3 mt-6 mb-8 text-white">
                            <div class="badge">Predisposed</div>
                            <div class="badge">Responsable</div>
                            <div class="badge">Positive</div>
                        </div>

                        <p class="text-secondary text-justify">I consider myself as a enthusiastic person willing to face challenges, learn new technologies and able to change role if necessary. Hoping be a great addition to the team.</p>
                    </div>

                </div>
            </div>

        </section>
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>