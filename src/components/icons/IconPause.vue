<script setup>
const props = defineProps({
  size: Number,
});
</script>

<template>
  <svg
    :width="props.size"
    :height="props.size"
    viewBox="0 0 24 24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M5.746 3a1.75 1.75 0 0 0-1.75 1.75v14.5c0 .966.784 1.75 1.75 1.75h3.5a1.75 1.75 0 0 0 1.75-1.75V4.75A1.75 1.75 0 0 0 9.246 3h-3.5ZM14.746 3a1.75 1.75 0 0 0-1.75 1.75v14.5c0 .966.784 1.75 1.75 1.75h3.5a1.75 1.75 0 0 0 1.75-1.75V4.75A1.75 1.75 0 0 0 18.246 3h-3.5Z"
    />
  </svg>
</template>
