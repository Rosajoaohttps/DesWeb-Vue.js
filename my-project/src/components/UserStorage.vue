<template>
    <div class="Global">
      <div class="content">
            <div class="card-container">
                <div class="card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1200px-Unofficial_JavaScript_logo_2.svg.png"
                        alt="JavaScript Logo">
                    <div class="card-body">
                        <h5>Card title</h5>
                        <p>Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn">Go somewhere</a>
                    </div>
                </div>
                <div class="card">
                    <img src="https://lh3.googleusercontent.com/csXm00pBuJvmhsXcI1XauxFGrE66sHBbWI9QyKY0lt2h55a1VaKl6F5TrlH0wBC_aijloKw9lh8a=e14-rj-sc0xffffff-w1270"
                        alt="Logo">
                    <div class="card-body">
                        <h5>Card title</h5>
                        <p>Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn">Go somewhere</a>
                    </div>
                </div>
                <div class="card">
                    <img src="https://lh3.googleusercontent.com/csXm00pBuJvmhsXcI1XauxFGrE66sHBbWI9QyKY0lt2h55a1VaKl6F5TrlH0wBC_aijloKw9lh8a=e14-rj-sc0xffffff-w1270"
                        alt="Logo">
                    <div class="card-body">
                        <h5>Card title</h5>
                        <p>Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn">Go somewhere</a>
                    </div>
                </div>
                <div class="card">
                    <img src="https://lh3.googleusercontent.com/csXm00pBuJvmhsXcI1XauxFGrE66sHBbWI9QyKY0lt2h55a1VaKl6F5TrlH0wBC_aijloKw9lh8a=e14-rj-sc0xffffff-w1270"
                        alt="Logo">
                    <div class="card-body">
                        <h5>Card title</h5>
                        <p>Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn">Go somewhere</a>
                    </div>
                </div>
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbm2BN5DgUYAS8mkFN_2ZhT8xT5u1Zd9PqHw&s"
                        alt="Logo">
                    <div class="card-body">
                        <h5>Card title</h5>
                        <p>Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn">Go somewhere</a>
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
  