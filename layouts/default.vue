<template>
  <div>
    <Navbar />
    <nuxt />
  </div>
</template>

<script>

export default {
  head() {
    return {
      bodyAttrs: {
        class: "antialiased bg-body text-body font-body"
      }
    };
  }
}
</script>