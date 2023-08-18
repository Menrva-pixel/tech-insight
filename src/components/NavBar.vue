<!-- eslint-disable no-unused-vars -->
<script>
import { RouterLink } from 'vue-router'
</script>

<template>
    <div class="navbar bg-base-100 flex flex-row fixed">
        <div class="flex-1">
            <a class="btn btn-ghost normal-case text-3xl text-white">Tech Insight</a>
        </div>
        <div class="flex-none">
            <ul class="menu menu-horizontal px-1">
                <li><a>Link</a></li>
                <li><a>Link</a></li>
                <li><a>Link</a></li>
                <li>
                    <details>
                        <summary>
                            Dropdown
                        </summary>
                        <ul class="p-2 bg-base-100">
                            <RouterLink to="/about">about</RouterLink>
                            <li><a>Link 2</a></li>
                        </ul>
                    </details>
                </li>
            </ul>
        </div>
    </div>
</template>

