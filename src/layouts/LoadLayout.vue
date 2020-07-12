<template>
  <div class="loading-layout">
    <slot/>
  </div>
</template>

<script>

export default {
  name: 'LoadLayout'
}
</script>

.loading-layout
  height 100vh
  display flex
  align-items center
  justify-content center
