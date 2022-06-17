<template>
  <div class="container mt-64 flex justify-between items-center mx-auto px-8 md:px-14 lg:px-24 w-full">
        <section class="w-full">
            <h2 id="hire" class="secondary-title">Contact me</h2>
            <p class="section-paragraph">Feel free to to contact me any time, through any method below.</p>
            <div class="w-full grid lg:grid-cols-2 gap-8 lg:gap-32 mt-24">
                <form action="https://formsubmit.co/fabriciobencomo.viloria@gmail.com" method="POST">
                    <div class="space-y-12">
                        <div>
                            <label class="block mb-6 text-xl font-bold">Name</label>
                            <input class="w-full border border-input-border bg-input rounded-sm  px-4 py-4 text-white" name="name">
                        </div>
                        <div>
                            <label class="block mb-6 text-xl font-bold">Email</label>
                            <input type="email" class="w-full border border-input-border rounded-sm  bg-input px-4 py-4 text-white" name="email">
                        </div>
                        <div>
                            <label class="block mb-6 text-xl font-bold">Message</label>
                            <textarea type="email" class="w-full border border-input-border rounded-sm  bg-input px-4 py-4 text-white h-56 resize-none" name="message"></textarea>
                        </div>
                        <button class="px-6 py-2 bg-theme text-white font-bold rounded-sm ">Send it!</button>
                    </div>
                </form>
                <div class="mt-12">
                    <!-- Contact info -->
                    <p class="text-secondary">+58 414-4244614</p>
                    <a href="mailto:fabriciobencomo.viloria@gmail.com" class="text-secondary underline mt-3 block">fabriciobencomo.viloria@gmail.com</a>

                    <!-- Socials -->
                    <div class="flex mt-20 space-x-6">
                        <!-- Linkedin -->
                        <a href="https://www.linkedin.com/in/fabricio-bencomo-644829181/">
                            <svg class="w-8 h-8 lg:w-12 lg:h-12"  xmlns="http://www.w3.org/2000/svg" width="42" height="42" viewBox="0 0 50 50" ><path d="M43.1494 28.252C43.3496 27.1533 43.457 26.0303 43.457 24.9072C43.457 22.417 42.9688 20 42.0068 17.7295C41.0791 15.5322 39.7461 13.5596 38.0518 11.8652C36.3716 10.1808 34.3799 8.83914 32.1875 7.91504C29.9121 6.95313 27.5 6.46484 25.0098 6.46484C23.8379 6.46484 22.6611 6.57715 21.5186 6.79687C19.9376 5.9591 18.176 5.51995 16.3867 5.51758C13.4717 5.51758 10.7275 6.65527 8.66699 8.71582C7.65021 9.72738 6.84403 10.9305 6.29507 12.2555C5.74611 13.5806 5.46526 15.0013 5.46875 16.4355C5.46875 18.291 5.94727 20.1172 6.84082 21.7285C6.66016 22.7734 6.5625 23.8428 6.5625 24.9072C6.5625 27.3975 7.05078 29.8145 8.0127 32.085C8.94043 34.2822 10.2686 36.2549 11.9629 37.9492C13.6572 39.6436 15.6299 40.9717 17.8272 41.8994C20.1025 42.8613 22.5147 43.3496 25.0049 43.3496C26.0889 43.3496 27.1729 43.252 28.2373 43.0615C29.8731 43.9844 31.7188 44.4775 33.6084 44.4775C36.5234 44.4775 39.2676 43.3447 41.3281 41.2793C43.3936 39.2188 44.5264 36.4746 44.5264 33.5596C44.5313 31.7041 44.0527 29.873 43.1494 28.252ZM25.083 36.2061C18.5303 36.2061 15.6006 32.9834 15.6006 30.5713C15.6006 29.3311 16.5137 28.4668 17.7734 28.4668C20.5762 28.4668 19.8535 32.4951 25.083 32.4951C27.7637 32.4951 29.2432 31.04 29.2432 29.5508C29.2432 28.6572 28.8037 27.6611 27.0361 27.2266L21.2061 25.7715C16.5137 24.5947 15.6592 22.0557 15.6592 19.6729C15.6592 14.7217 20.3223 12.8613 24.7022 12.8613C28.7354 12.8613 33.4912 15.0928 33.4912 18.0615C33.4912 19.3359 32.3877 20.0732 31.1279 20.0732C28.7354 20.0732 29.1748 16.7627 24.3555 16.7627C21.9629 16.7627 20.6397 17.8467 20.6397 19.3945C20.6397 20.9424 22.5293 21.4355 24.1699 21.8115L28.4863 22.7686C33.2129 23.8232 34.4092 26.582 34.4092 29.1797C34.4092 33.1982 31.3184 36.2061 25.083 36.2061Z" fill="#3F3FFF"/></svg>
                        </a>
                        <!-- Github -->
                        <a href="https://github.com/fabriciobencomo">
                            <svg class="w-8 h-8 lg:w-12 lg:h-12" xmlns="http://www.w3.org/2000/svg" width="42" height="42" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z" fill="#3F3FFF"/></svg>								
                        </a>
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