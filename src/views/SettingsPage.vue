<template>
  <div class="front">
    <Header />
    <main class="flex flex-col">
      <Main />
    </main>
  </div>
</template>

<script>
import Header from '@/components/settings/Header.vue';
import Main from '@/components/settings/Main.vue';

export default {
  components: {
    Header,
    Main,
  },
};
</script>
