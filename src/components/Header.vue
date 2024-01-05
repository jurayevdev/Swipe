<template>
    <header class="fixed z-10 w-full bg-transparent transition duration-1000">
        <div class="container mx-auto px-5">
            <nav class="w-full flex items-center justify-between py-5">
                <div>
                    <router-link to="/" class="flex items-center">
                        <img class="bg-transparent" src="../../public/logo/IMAGE.png" alt="">
                    </router-link>
                </div>
                <div>
                    <ul class="flex items-center gap-8 text-[16px] font-bold text-[#1A1930]">
                        <li class="textLi p-2">
                            <router-link to="/about">About</router-link>
                        </li>
                        <li class="textLi p-2">
                            <router-link to="/features">Features</router-link>
                        </li>
                        <li class="textLi p-2">
                            <router-link to="/pricing">Pricing</router-link>
                        </li>
                        <li class="textLi p-2">
                            <router-link to="/team">Team</router-link>
                        </li>
                        <li class="textLi p-2">
                            <router-link to="/faq">FAQ</router-link>
                        </li>
                        <li class="textLi p-2">
                            <router-link to="/feedback">Feedback</router-link>
                        </li>
                        <li class="textLi p-2">
                            <router-link to="/blog">Blog</router-link>
                        </li>
                        <li class="textLi p-2">
                            <router-link to="/contact">Contact</router-link>
                        </li>
                    </ul>
                </div>
                <button class="bg-[rgba(255,255,255,0.4)] w-[139px] h-[60px] shadow-lg rounded-lg border-2 border-solid border-[rgba(255,255,255,0.4)]">Buy now</button>
            </nav>
        </div>
    </header>
</template>

<script setup>

</script>

<style lang="scss" scoped></style>