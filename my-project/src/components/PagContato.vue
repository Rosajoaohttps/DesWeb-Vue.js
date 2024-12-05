<template>
    <div>
      <div class="header">
        <h1>Contato</h1>
      </div>
      <h3>Formulário de Contato</h3>
      <form class="form-contato">
        <div class="form-group">
          <label for="nome">Seu Nome:</label>
          <input type="text" id="nome" name="nome" />
  
          <label for="email">Seu e-mail para contato:</label>
          <input type="email" id="email" name="email" />
  
          <label for="mensagem">Informe seu problema:</label>
          <textarea id="mensagem" name="mensagem"></textarea>
        </div>
        <!-- O método submitForm será chamado no clique -->
        <button type="button" @click="submitForm">Enviar relatório</button>
      </form>
    </div>
  </template>
  
  <script>
  export default {
    name: "PagContato",
    methods: {
      submitForm() {
        alert(
          "Um e-mail com informações adicionais para o seu problema foi enviado para sua caixa de entrada! Verifique também sua caixa de spam caso não encontre."
        );
      },
    },
  };
  </script>
  
  <style>
  .form-contato {
    max-width: 400px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 8px;
    background-color: #f9f9f9;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }
  
  .form-group {
    margin-bottom: 15px;
  }
  
  .form-group label {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
    color: #333;
  }
  
  .form-group input,
  .form-group textarea {
    width: 100%;
    padding: 10px;
    font-size: 14px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
  }
  
  .form-group input:focus,
  .form-group textarea:focus {
    outline: none;
    border-color: #007bff;
    box-shadow: 0 0 4px rgba(0, 123, 255, 0.5);
  }
  
  textarea {
    resize: none;
  }
  
  button {
    width: 100%;
    padding: 10px;
    font-size: 16px;
    font-weight: bold;
    color: #fff;
    background-color: #007bff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    text-transform: uppercase;
    transition: background-color 0.3s;
  }
  
  button:hover {
    background-color: #0056b3;
  }
  </style>
  