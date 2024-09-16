<script>
/* 
Per importare ed utilizzare un componente dentro ad un altro devo SEMPRE seguire 3 passi:
1. Importazione del componente
2. Dichiarazione del componente
3. Utilizzo del componente
*/

//1. Importazione del componente
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  data() {
    return { 
      message: ''
    }
  },
  // 2. Dichiarazione del componente
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  methods: {
  }
}
</script>

<template>
  <!--3. Utilizzo del componente-->
  <AppHeader />
  <AppMain />
  <AppFooter />
  <div>
    <header>
      <div class="container">
        <span>
          <img src="./assets/vue-dc-comics-1/img/dc-logo.png" alt="">

          <nav>
            <ul>
              <li>
                <a href="#">CHARACTERS</a>
              </li>
              <li>
                <a href="#">COMICS</a>
              </li>
              <li>
                <a href="#">MOVIES</a>
              </li>
              <li>
                <a href="#">TV</a>
              </li>
              <li>
                <a href="#">GAMES</a>
              </li>
              <li>
                <a href="#">COLLECTIBLES</a>
              </li>
              <li>
                <a href="#">VIDEOS</a>
              </li>
              <li>
                <a href="#">FANS</a>
              </li>
              <li>
                <a href="#">NEWS</a>
              </li>
              <li>
                <a href="#">SHOP</a>
              </li>
            </ul>
          </nav>
        </span>
        
      </div>
    </header>

    <main>
      <div class="container">
        MAIN
      </div>
    </main>
      
    <footer>
      <div class="container">
        FOOTER
      </div>
    </footer>
    
  </div>
</template>

<style scoped>

header {
  padding: 10px 0;
}

header ul {
  list-style: none;
  display: flex;
  justify-content: end;
}

header ul li a {
  margin: 0 10px;
  text-decoration: none;
  color: black;
}

header ul li a:hover {
  color: #097CEB;
  
}

</style>
