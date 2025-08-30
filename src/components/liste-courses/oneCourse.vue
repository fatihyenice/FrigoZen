<template>
  <div class="container-courses">
    <div class="course">
      <input type="checkbox" :id="`c${nomCourse}`" />
      <label :for="`c${nomCourse}`">{{ nomCourse }}</label>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  nomCourse: String,
});
</script>