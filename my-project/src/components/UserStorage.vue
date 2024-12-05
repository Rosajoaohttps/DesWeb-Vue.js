<template>
    <div class="Global">
      <div class="content">
        <div class="card-container">
          <div class="card">
            <img src="@/assets/Tenis1.png" alt="Tênis esportivo verde">
            <div class="card-body">
              <h5>Modelo Speedy Verde</h5>
              <p>Ideal para atividades de alta performance, com design aerodinâmico e leveza incomparável.</p>
              <a href="#" class="btn">Saiba mais</a>
            </div>
          </div>
          <div class="card">
            <img src="@/assets/Tenis2.png" alt="Tênis casual branco e vermelho">
            <div class="card-body">
              <h5>Casual Branco e Vermelho</h5>
              <p>Perfeito para o dia a dia, combina conforto e estilo em qualquer ocasião.</p>
              <a href="#" class="btn">Saiba mais</a>
            </div>
          </div>
          <div class="card">
            <img src="@/assets/Tenis3.png" alt="Tênis de corrida rosa e branco">
            <div class="card-body">
              <h5>Runner Rosa</h5>
              <p>Desenvolvido para corredores, oferece estabilidade e amortecimento em terrenos variados.</p>
              <a href="#" class="btn">Saiba mais</a>
            </div>
          </div>
          <div class="card">
            <img src="@/assets/Tenis4.png" alt="Tênis de basquete azul e branco">
            <div class="card-body">
              <h5>Basquete Clássico</h5>
              <p>Com design robusto e clássico, é perfeito para amantes de basquete e cultura urbana.</p>
              <a href="#" class="btn">Saiba mais</a>
            </div>
          </div>
          <div class="card">
            <img src="@/assets/Tenis5.png" alt="Tênis estampado com detalhes laranja">
            <div class="card-body">
              <h5>Estampado Vibrante</h5>
              <p>Com estampa ousada e moderna, é a escolha ideal para quem gosta de inovar no visual.</p>
              <a href="#" class="btn">Saiba mais</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'UserStorage',
    props: {
      msg: String
    }
  }
  </script>
  
  <style scoped>
  /* Container principal */
.container {
    background-color: rgb(235, 235, 235);
    padding: 20px;
}

/* Conteúdo principal */
.content {
    margin: 0 auto;
    width: 50%;
}

/* Estilo do contêiner de cards */
.card-container {
    display: flex;
    gap: 3%;
    justify-content: center;
    padding: 10px;
}

/* Estilo dos cards */
.card {
    border: 1px solid #ccc;
    border-radius: 5px;
    width: 100%;
    padding: 10px;
    text-align: center;
    background-color: white;
}

.card img {
    width: 100%;
    height: auto;
    width: 300px;
    border-radius: 5px;
}

.card-body {
    padding: 10px;
}

.card-body h5 {
    margin: 10px 0;
    font-size: 1.2rem;
}

.card-body p {
    font-size: 0.9rem;
    color: #555;
}

.card-body .btn {
    display: inline-block;
    background-color: blue;
    color: white;
    padding: 5px 10px;
    text-decoration: none;
    border-radius: 3px;
    margin-top: 10px;
}

/* Estilo do rodapé */
.footer {
    background-color: rgba(235, 235, 235, 0.658);
    padding: 20px;
    text-align: center;
    margin-top: 20px;
}

.footer h5 {
    font-size: 1.2rem;
    margin-bottom: 10px;
}

.footer ul {
    list-style: none;
    padding: 0;
}

.footer ul li {
    margin: 5px 0;
}

.footer ul li a {
    text-decoration: none;
    color: black;
    font-size: 0.9rem;
}

.footer p {
    font-size: 0.8rem;
    color: #555;
}

  </style>
  