<template>
    <footer class="bg-[#1A1930] relative ">
        <div class="container mx-auto p-5">
            <div class="my-14 flex items-center 2xl:gap-[500px] gap-32">
                <div class="flex flex-col gap-10">
                    <a href="/">
                        <img src="../../public/logo/IMAGE (2).png" alt="">
                    </a>
                    <div class="text-white flex flex-col gap-2">
                        <span>Kyiv, Ukraine</span>
                        <span>hello.craftengine@gmail.com</span>
                        <span>Made with ❤️ by <a href="#" class="text-[#6259EA]">Craftengine</a>🇺🇦</span>
                    </div>
                    <p class="text-white text-[14px] mt-10">© Swipe. All rights reserved. Powered by <a href="#"
                            class="text-[#6259EA]">Webflow</a></p>
                </div>

                <div class="text-white flex items-center gap-36">
                    <div class="flex flex-col gap-2">
                        <a href="#" class="hover:underline">About</a>
                        <a href="#" class="hover:underline">Features</a>
                        <a href="#" class="hover:underline">Pricing</a>
                        <a href="#" class="hover:underline">Team</a>
                    </div>
                    <div class="flex flex-col gap-2">
                        <a href="#" class="hover:underline">FAQ</a>
                        <a href="#" class="hover:underline">Feedback</a>
                        <a href="#" class="hover:underline">Blog</a>
                        <a href="#" class="hover:underline">Contact</a>
                    </div>
                    <div class="flex flex-col gap-2">
                        <a href="#" class="hover:underline">Twitter</a>
                        <a href="#" class="hover:underline">Facebook</a>
                        <a href="#" class="hover:underline">Instagram</a>
                        <a href="#" class="hover:underline">Licensing</a>
                    </div>
                    <img class="absolute bottom-0 right-0" src="../../public/elements/IMAGE.png" alt="">
                </div>
            </div>
        </div>
    </footer>
</template>

<script setup>

</script>

<style lang="scss" scoped>
footer::before {
    content: '';
    position: absolute;
    width: 850px;
    border-bottom: 1px solid #E7E5FF;
    bottom: 320px;
    right: 0;
}

footer::after {
    content: '';
    position: absolute;
    width: 850px;
    border-bottom: 1px solid #E7E5FF;
    bottom: 80px;
    right: 0;
}
</style>