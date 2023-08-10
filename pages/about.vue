<template>
  <div>About with lowercase</div>
</template>

<script setup>
console.log("about page");
try {
  if (process) {
    console.log("process exist, so this is dev");
  }
} catch (error) {
  console.log("this might be production");
}
</script>

<style scoped></style>
