<template>
  <ul>
    <li v-for="post in posts" :key="post.id">
      <div>
        <h1>{{ post.title }}</h1>
        <p>{{ post.content }}</p>
      </div>
    </li>
  </ul>
</template>

<script setup>
const props = defineProps(['posts']);
</script>
