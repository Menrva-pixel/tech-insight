<!-- eslint-disable no-unused-vars -->
<script>
import { RouterLink } from 'vue-router'
</script>

<template>
    <div class="navbar backdrop-blur-sm bg-transparent flex flex-row fixed justify-around">
        <div class="logo w-10">
            <img src="../assets/vue.png">
        </div>
        <div class="flex-none">
            <ul class="menu menu-horizontal text-md text-gray-300 font-bold">
                <li><a class="">Home</a></li>
                <li><a class="">About</a></li>
                <li class="">
                    <details>
                        <summary>
                            Dropdown
                        </summary>
                        <ul class="py-8 bg-base-100 flex flex-col items-center mx-auto w-32 gap-4">
                            <RouterLink to="/about">about</RouterLink>
                            <RouterLink to="/404">about</RouterLink>
                        </ul>
                    </details>
                </li>
            </ul>
        </div>
    </div>
</template>

