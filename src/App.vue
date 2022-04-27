<template>
 <header-page/>
  <main>
    <home-page />
  </main>
</template>

<script>
import HeaderPage from './components/HeaderPage.vue';
import HomePage from './components/HomePage.vue';

export default {
  name: 'App',
  components: {
    HeaderPage,
    HomePage,
  },
};
</script>

<style>
*, ::before, ::after {
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

body {
  background-color: rgba( 44, 44, 44, 1 );
}

.fd {
  display: flex;
}

ul {
  list-style: none;
  padding: 0;
}

header, main {
  margin: 0 auto;
  width: 95%;
  max-width: 1024px;
}

main {
  background-color: rgba( 234, 234, 234, 1 );
  padding: 20px;
}
</style>
