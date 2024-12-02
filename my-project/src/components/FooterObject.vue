<template>
    <div class="Global">
        <footer class="footer">
            <div>
                <h5>CURSOS</h5>
                <ul>
                    <li><a href="#">Cursos de Programação</a></li>
                    <li><a href="#">Cursos de Front-end</a></li>
                    <li><a href="#">Cursos de Data Science</a></li>
                    <li><a href="#">Cursos de IA</a></li>
                    <li><a href="#">Cursos de DevOps</a></li>
                </ul>
            </div>
            <p>© 2024 Empresa. Todos os direitos reservados.</p>
        </footer>
    </div>
  </template>
  
  <script>
  export default {
    name: 'FooterObject',
    props: {
      msg: String
    }
  }
  </script>
  
  <style scoped>
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
  