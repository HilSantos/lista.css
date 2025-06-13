# Lista.CSS
Criação de um CSS externo para Lista Usuarios e Lista Produtos.

/* Reset básico para evitar diferenças entre navegadores */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  /* Corpo com fundo suave e fonte moderna */
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #f0f0f0, #e0e0e0);
    color: #333;
    padding: 20px;
  }
  
  /* Títulos */
  h1, h2, h3, h4, h5, h6 {
    color: #222;
    margin-bottom: 10px;
  }
  
  /* Tabelas com visual moderno */
  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 20px;
    background-color: #fff;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  
  th, td {
    padding: 15px;
    text-align: left;
  }
  
  th {
    background-color: #38105e;
    color: white;
    font-weight: normal;
  }
  
  tr:nth-child(even) {
    background-color: #f9f9f9;
  }
  
  tr:hover {
    background-color: #f1f1f1;
  }
  
  /* Botões */
  input[type="submit"],
  input[type="button"],
  button {
    background-color: #2e4e74;
    color: white;
    border: none;
    padding: 10px 20px;
    margin-top: 10px;
    border-radius: 25px;
    cursor: pointer;
    font-size: 1rem;
    transition: background-color 0.3s;
  }
  
  input[type="submit"]:hover,
  input[type="button"]:hover,
  button:hover {
    background-color: #921c3f;
  }
  
  /* Inputs de texto */
  input[type="text"],
  input[type="email"],
  input[type="password"],
  input[type="date"],
  select {
    width: 100%;
    padding: 12px 15px;
    margin: 8px 0;
    border: 1px solid #ccc;
    border-radius: 8px;
    font-size: 1rem;
  }
  
  /* Responsividade */
  @media (max-width: 600px) {
    th, td {
      padding: 10px;
    }
  
    body {
      padding: 10px;
    }
  
    table {
      font-size: 0.9rem;
    }
  
    input[type="submit"],
    input[type="button"],
    button {
      width: 100%;
    }
  }
  #mensagem{
    color: #f00;
    font-weight: bolder;
    text-align: center;
  }
