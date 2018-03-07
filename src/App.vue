<template>
  <div id="app">
    <Home></Home>
  </div>
</template>
<script>
  /* ============
   * Entry Point
   * ============
   *
   * The entry point of the application
   */

  import Home from '@/pages/Home/Index';

  export default {
    /**
     * The name of the application.
     */
    name: 'configurator',

    /**
     * The components that the page can use.
     */
    components: {
      Home,
    },

    /**
     * Fires when the app has been mounted.
     */
    mounted() {},
  };
</script>
