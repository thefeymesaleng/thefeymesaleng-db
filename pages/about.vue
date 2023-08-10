<template>
  <div>About with lowercase</div>
</template>

<script setup>
console.log("about page");
if (process) {
  console.log("process exist");
} else {
  console.log("this might be production");
}
</script>

<style scoped></style>
