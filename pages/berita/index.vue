<template>
  <div>
    <Berita :isHomePage="false" />
  </div>
</template>

<script setup>
useHead({
  title: "Berita",
  meta: [
    {
      name: "description",
      content: "Berita Page",
    },
  ],
});
</script>
