<template>
  <footer
    v-if="$slidev.nav.currentLayout !== 'intro'"
    class="absolute bottom-2 text-right left-0 right-0 p-2 text-2xl"
  >
    {{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }}
  </footer>
</template>