<template>
  <div class="w-full h-screen bg-gray-700 text-white flex">
    <div class="w-24 h-full border-r-2 border-gray-500 border-opacity-25">
      <Sidebar />
    </div>
    <div>
      <Navbar />
      <Body />
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Sidebar from './components/Sidebar.vue';
import Body from './components/Body.vue';
export default {
  components: {
    Navbar,
    Sidebar,
    Body,
  },
  setup() {
    return {};
  },
};
</script>

<style></style>
