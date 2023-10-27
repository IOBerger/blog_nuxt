<script setup lang="ts">


import Post from '~/components/Post.vue';

let posts = [
        {
            id: 1,
            date: new Date(),
            title: 'Title1',
            text: 'Asdns fdj d k hje jfaj fg fhbvjshefbvjv djfkenkn f  fj fdnkveklnelncln  jvjnjerejknkj'
        },
        {
            id: 2,
            date: new Date(),
            title: 'Title2',
            text: 'Asdns fdj d k hje jfaj fg fhbvjshefbvjv djfkenkn f  fj fdnkveklnelncln  jvjnjerejknkj'
        },
        {
            id: 3,
            date: new Date(),
            title: 'Title3',
            text: 'Asdns fdj d k hje jfaj fg fhbvjshefbvjv djfkenkn f  fj fdnkveklnelncln  jvjnjerejknkj'
        },
        {
            id: 4,
            date: new Date(),
            title: 'Title4',
            text: 'Asdns fdj d k hje jfaj fg fhbvjshefbvjv djfkenkn f  fj fdnkveklnelncln  jvjnjerejknkj'
        },
        {
            id: 5,
            date: new Date(),
            title: 'Title5',
            text: 'Asdns fdj d k hje jfaj fg fhbvjshefbvjv djfkenkn f  fj fdnkveklnelncln  jvjnjerejknkj'
        },
    ]

</script>

<template>
<div class="posts">
    <Post  
        v-for="post in posts"
        :key="post.id"
        :title="post.title"
        :date="post.date"
        :text="post.text"
    ></Post>
</div>
</template>