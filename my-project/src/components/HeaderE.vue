<template>
  <div class="Global">
    <header class="custom-header">
    <div class="container">
        <a href="#" class="navbar-brand"><img src="@/assets/favicon.png" alt="" width="5%"></a>
        <form class="search-bar">
            <input type="search" placeholder="O que você quer aprender?" aria-label="Search">
            <button type="submit">Q</button>
        </form>
        <nav class="nav">
            <a class="nav-link" href="#">Informações</a>
            <a class="nav-link" href="#">Sobre</a>
            <a class="nav-link" href="#">Contato</a>
        </nav>
        <a href="Login_page.html" class="btn-plan">Criar Conta / fazer Login</a>
    </div>
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
/* Estilos gerais */
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

.custom-header {
    background-color: #858b91; /* Cor de fundo do cabeçalho */
    padding: 1rem 2rem;
    color: white;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

/* Estilo da marca (logo) */
.navbar-brand {
    padding-left: 0; /* Remover padding desnecessário */
    text-decoration: none;
    color: white;
    font-size: 1.5rem;
    font-weight: bold;
}

.navbar-brand img {
    max-height: 100px; /* Ajusta a altura máxima da imagem */
    width: auto; /* Mantém a proporção da imagem */
}

/* Barra de busca */
.search-bar {
    display: flex;
    gap: 0.5rem;
}

.search-bar input {
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1rem;
}

.search-bar button {
    background-color: white;
    color: #343a40;
    border: 1px solid white;
    border-radius: 4px;
    padding: 0.5rem 1rem;
    cursor: pointer;
    font-size: 1rem;
}

.search-bar button:hover {
    background-color: #495057;
    color: white;
}

/* Navegação */
.nav {
    display: flex;
    gap: 1rem;
}

.nav-link {
    text-decoration: none;
    color: white;
    font-size: 1rem;
}

.nav-link:hover {
    text-decoration: underline;
}

/* Botão de login/criar conta */
.btn-plan {
    background-color: #ffc107;
    color: #343a40;
    text-decoration: none;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    font-size: 1rem;
    font-weight: bold;
}

.btn-plan:hover {
    background-color: #e0a800;
    color: white;
}


</style>
