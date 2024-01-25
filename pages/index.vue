<template>
  <div>
    <h1>Welcome to My Blog</h1>
    <BlogList :posts="posts" />
  </div>
</template>

<script setup>
import BlogList from '~/components/BlogList.vue';

const posts = [
  { id: 1, title: 'First Post', content: 'This is my first post.' },
  { id: 2, title: 'Another Post', content: 'This is another post.' },
];
</script>
