<template>
  <a class="whatsNewOuter" :href="url" target="_blank" rel="noopener">
    <span class="link">{{ text }}</span>
  </a>
</template>

<script>
export default {
  props: {
    text: {
      type: String,
      required: true
    },
    url: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss">
.whatsNewOuter {
  display: block;
  align-items: center;
  flex-wrap: wrap;
  background: $white;
  border: 1px solid $gray-4;
  box-shadow: 0 0 2px rgba(0, 0, 0, 0.15);
  border-radius: 4px;
  padding: 0.7em 1em;
  @include font-size(14);
  text-decoration: none;
  &-Icon {
    color: $gray-2 !important;
  }
}
.link {
  @include text-link();
}
</style>