<template>
    <div class="container mt-64 flex justify-between items-center mx-auto px-8 md:px-14 lg:px-24 w-full" id="work">
        <section class="w-full">
            <h2 class="secondary-title">My Projects</h2>
            <p class="section-paragraph">These are some of the personal projects I have worked with, from basic information pages to fully functional web applications. visit them and check the code.</p>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mt-6 space-x-6">
                <div class="card md:w-10/12 w-80 flex-col bg-input">
                    <div>
                        <img src="@/assets/sitioWeb4.png" alt="project">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project text-white">ShareRecipes</p>
                        <p class="text-white justify-end mt-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum, sintLorem ipsum dolor sit amet,
                            consectetur adipisicing elit. Harum, sint??</p>
                    </div>
                </div>
                <div class="card md:w-10/12 w-80 flex flex-col bg-white">
                    <div>
                        <img src="@/assets/sitioWeb3.png" alt="project">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project">Exchage-Crypto</p>
                        <p class="text-secondary justify-end mt-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum, sintLorem ipsum dolor sit amet,
                            consectetur adipisicing elit. Harum, sint??</p>
                    </div>
                </div>    
                <div class="card md:w-10/12 w-80 flex flex-col bg-white">
                    <div>
                        <img src="@/assets/sitioWeb6.png" alt="project">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project">DevJobs</p>
                        <p class="text-secondary justify-end mt-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum, sintLorem ipsum dolor sit amet,
                            consectetur adipisicing elit. Harum, sint??</p>
                    </div>
                </div>
                <div class="card md:w-10/12 w-80 flex flex-col bg-input">
                    <div>
                        <img src="@/assets/sitioWeb1.png" alt="project">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project text-white">TravelPlaces</p>
                        <p class="justify-end mt-3 text-white">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum, sintLorem ipsum dolor sit amet,
                            consectetur adipisicing elit. Harum, sint??</p>
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