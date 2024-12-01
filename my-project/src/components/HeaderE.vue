<template>
  <div class="Global">
      <header>
        <nav>
            <a href="#home">Início</a>
            <a href="#about">Sobre</a>
            <a href="#services">Serviços</a>
            <a href="#contact">Contato</a>
        </nav>
      </header>
  </div>
</template>

<script>
export default {
  name: 'HeaderE',
  props: {
    msg: String
  }
}
</script>

<style scoped>
html, body {
  margin: 0;   
  padding: 0; 
  height: 100%; 
  width: 100%;  
}

.Global {
  width: 100%;
  height: 100%;
}

header {
  width: 100%; 
  height: 100%; 
  border-bottom: solid 2px #42b983; 
   
}

/* Estilos de navegação */
nav {
  display: flex;
  justify-content: center; 
  align-items: center; 
  height: 100%; 
  padding: 15px;
}

a {
  color: #42b983;
  text-decoration: none;
  margin: 0 15px; 
}

a:hover {
  text-decoration: underline; 
}
</style>
