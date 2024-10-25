<template>
  <div class="about">
    <h1>This is an about page</h1>

    <UiButton> Shadcn UI </UiButton>
  </div>
</template>

<script lang="js">
import { Button as UiButton } from '@/components/ui/button'

export default {
  components: {
    UiButton,
  },
}
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
