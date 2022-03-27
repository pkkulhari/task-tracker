<template>
  <button class="btn" :style="{ background: color}">{{ text }}</button>
</template>

<script>
export default {
  name: 'ButtonComp',
  props: {
    color: String,
    text: String
  }
}
</script>
