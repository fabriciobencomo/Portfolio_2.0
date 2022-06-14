<template>
    <div class="container mt-64 flex justify-between items-center mx-auto px-8 md:px-14 lg:px-24 w-full" id="work">
        <section class="w-full">
            <h2 class="secondary-title">My Projects</h2>
            <p class="section-paragraph">These are some of the personal projects I have worked with, from basic information pages to fully functional web applications. visit them and check the code.</p>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mt-6 space-x-6">
                <div class="card md:w-10/12 w-72 flex-col bg-input">
                    <div>
                        <img src="@/assets/sitioWeb4.png" alt="project">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project text-white">ShareRecipes</p>
                        <p class="text-white text-justify mt-3">It is a social network that allows its users to share their recipes with the world .What are you waiting for? learn a new recipe or share yours.
                        <br><span class="font-bold">Stack used: Laravel, Bootstrap, Javascript.</span></p>
                        <div class="mt-12 mb-8 flex justify-around space-x-6">
                            <a href="http://calm-reaches-90714.herokuapp.com" target="_blank"><button class="px-6 py-2 bg-theme font-bold rounded-sm text-white">Visit it!</button></a>
                            <a href="https://github.com/fabriciobencomo/ShareRecipes" target="_blank"><button class="px-6 py-2 bg-theme font-bold rounded-sm text-white">Check the code! </button></a>
                        </div>
                    </div>
                </div>
                <div class="card md:w-10/12 w-72 flex flex-col bg-white">
                    <div>
                        <img src="@/assets/sitioWeb3.png" alt="project">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project">Exchage-Crypto</p>
                         <p class="text-secondary text-justify mt-3">It is a single page application that allows you to stay informed about the most important cryptocurrencies of the moment.
                        <br><span class="font-bold">Stack used: VueJs, TailwindCss.</span></p>
                        <div class="mt-12 mb-8 flex justify-around space-x-6">
                            <a href="https://exchange-crypto-fabriciobencomo.netlify.app" target="_blank"><button class="px-6 py-2 bg-theme font-bold rounded-sm text-white">Visit it!</button></a>
                            <a href="https://github.com/fabriciobencomo/exchange-crypto" target="_blank"><button class="px-6 py-2 bg-theme font-bold rounded-sm text-white">Check the code! </button></a>
                        </div>
                    </div>
                </div>    
                <div class="card md:w-10/12 w-72 flex flex-col bg-white">
                    <div>
                        <img src="@/assets/sitioWeb6.png" alt="project">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project">DevJobs</p>
                       <p class="text-secondary text-justify mt-3">It is a web application focused on job offers in the technology industry where it unites recruiters with IT workers.
                        <br><span class="font-bold">Stack used: Laravel, VueJs, TailwindCss.</span></p>
                        <div class="mt-12 mb-8 flex justify-around space-x-6">
                            <a href="https://travel-info-page.netlify.app/public/"><button class="px-6 py-2 bg-theme font-bold rounded-sm text-white">Visit it!</button></a>
                            <a href="https://github.com/fabriciobencomo/TravelPage"><button class="px-6 py-2 bg-theme font-bold rounded-sm text-white">Check the code! </button></a>
                        </div>
                    </div>
                </div>
                <div class="card md:w-10/12 w-72 flex flex-col bg-input">
                    <div>
                        <img src="@/assets/sitioWeb1.png" alt="project">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project text-white">TravelPlaces</p>
                        <p class="text-justify mt-3 text-white">It is an informative page on interesting places for different types of travelers. is focused on minimalist and attractive design.
                        <br><span class="font-bold">Stack used: TailwindCss.</span></p>
                        <div class="mt-12 mb-8 flex justify-around space-x-6">
                            <a href="https://travel-info-page.netlify.app/public/><button class=" target="_blank">px-6 py-2 bg-theme font-bold rounded-sm text-white">Visit it!</button></a>
                             <a href="https://github.com/fabriciobencomo/TravelPage" target="_blank"><button class="px-6 py-2 bg-theme font-bold rounded-sm text-white">Check the code! </button></a>
                        </div>
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

<style scoped>
.card {
	border-radius: 1rem;
	box-shadow: 0 .5rem .5rem rgba(0, 0, 0, 0.1);
	display: flex;	
	margin: 1.5rem;
	overflow: hidden;
	height: 32rem;
}





</style>