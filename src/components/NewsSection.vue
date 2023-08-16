<script>
import post1 from '../assets/images/post/post-1.jpg'

export default {
    data() {
        return {
            post: [{
                title: "Berita1",
                image: post1,    
                content: "ini adalah isi dari kontent postingan tersebut"            
            },
            {
                title: "Berita2",
                image: post1,    
                content: "ini adalah isi dari kontent postingan tersebut"            
            },
            {
                title: "Berita3",
                image: post1,    
                content: "ini adalah isi dari kontent postingan tersebut"            
            },
        ],
        };
    },
};
</script>



<template>
<div id="latest-post" class="grid grid-flow-row grid-cols-1 px-8">
    <div v-for="(post, index) in post" :key="index" class="post flex flex-row items-center mx-auto gap-4 m-12 rounded-md px-4 bg-gray-300 border-2 border-blue-700">
        <img :src="post.image" alt="post-image" class="w-1/2 p-16 h-auto rounded-md">
        <div class="title">
            <h2 class="text-7xl text-blue-600">{{ post.title }}</h2>
            <p class="text-2xl text-blue-400">{{ post.content }}</p>
        </div>
    </div>

</div>
</template>
