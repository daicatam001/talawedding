
<script>
export default {};
</script>

<template>
  <div class="layout__default">
    <header>
      <TheHeader />
    </header>
    <main>
      <nuxt />
    </main>
    <footer>
      <TheFooter />
    </footer>
  </div>
</template>

<style scoped>
.layout__default {
  @apply flex flex-col h-full;
}
header,
footer {
  @apply flex-shrink-0;
}
main {
  @apply flex-grow;
}
</style>