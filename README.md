# Lista.CSS
Criação de um CSS externo para Lista Usuarios e Lista Produtos.

/* estilo.css */

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f0f4f8;
    margin: 0;
    padding: 20px;
}

h1 {
    color: #333;
    text-align: center;
    margin-bottom: 40px;
}

table {
    width: 90%;
    margin: 0 auto;
    border-collapse: collapse;
    background-color: #fff;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    border-radius: 10px;
    overflow: hidden;
}

th, td {
    padding: 15px;
    text-align: center;
}

th {
    background-color: #007acc;
    color: white;
    text-transform: uppercase;
    font-weight: bold;
}

tr:nth-child(even) {
    background-color: #f2f2f2;
}

tr:hover {
    background-color: #e0f0ff;
}

td {
    color: #333;
}
