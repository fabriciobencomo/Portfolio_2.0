<template>
    <div class="container mt-64 flex justify-between items-center mx-auto px-8 md:px-14 lg:px-24 w-full" id="work">
        <section class="w-full">
            <h2 class="secondary-title">My Projects</h2>
            <p class="section-paragraph">Here some of my differente projects that i did.</p>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mt-6 space-x-6">
                <div class="card flex flex-col">
                    <div>
                        <img src="@/assets/sitioWeb4.png" alt="">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project">ShareRecipes</p>
                        <p class="text-secondary justify-end mt-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum, sintLorem ipsum dolor sit amet,
                            consectetur adipisicing elit. Harum, sint??</p>
                        <button class="button background1-left-column">Empezar</button>
                    </div>
                </div>
                <div class="card flex flex-col">
                    <div>
                        <img src="@/assets/sitioWeb4.png" alt="">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project">ShareRecipes</p>
                        <p class="text-secondary justify-end mt-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum, sintLorem ipsum dolor sit amet,
                            consectetur adipisicing elit. Harum, sint??</p>
                        <button class="button background1-left-column">Empezar</button>
                    </div>
                </div>    
                <div class="card flex flex-col">
                    <div>
                        <img src="@/assets/sitioWeb6.png" alt="">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project">DevJobs</p>
                        <p class="text-secondary justify-end mt-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum, sintLorem ipsum dolor sit amet,
                            consectetur adipisicing elit. Harum, sint??</p>
                        <button class="button background1-left-column">Empezar</button>
                    </div>
                </div>
                <div class="card flex flex-col">
                    <div>
                        <img src="@/assets/sitioWeb4.png" alt="">
                    </div>
                    <div class="mt-5 mx-2">
                        <p class="text-xl font-bold title-project">ShareRecipes</p>
                        <p class="text-secondary justify-end mt-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum, sintLorem ipsum dolor sit amet,
                            consectetur adipisicing elit. Harum, sint??</p>
                        <button class="button background1-left-column">Empezar</button>
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
	width: 30rem;
	height: 23rem;
}
.left-column {	
	padding: 1rem;
	max-width: 10rem;
	display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
}


.left-column i {
	font-size: 5rem
}

.right-column {
	padding: 30px;
	width: 100%;
	display: flex;
    flex-direction: column;
    align-items: start;
    justify-content: space-between;
	
}




</style>