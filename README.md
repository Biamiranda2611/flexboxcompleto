# flexboxcompleto
!DOCTYPE html>
<html>
<head>
  <title>Exercícios Flexbox</title>
  <style>
    /* Exercício 1: Layout Básico */
    .container1 {
      display: flex;
      justify-content: space-between;
    }
   
    .container1 > div {
      flex: 1;
      background-color: #f1f1f1;
      padding: 20px;
      text-align: center;
    }
   
    /* Exercício 2: Alinhamento Vertical */
    .container2 {
      display: flex;
      height: 300px;
      align-items: center;
    }
   
    .container2 > div {
      background-color: #f1f1f1;
      padding: 20px;
      text-align: center;
      font-size: 20px;
    }
   
    .item1 {
      height: 50px;
    }
   
    .item2 {
      height: 100px;
    }
   
    .item3 {
      height: 150px;
    }
   
    /* Exercício 3: Distribuição de Espaço */
    .container3 {
      display: flex;
      justify-content: space-between;
    }
   
    .container3 > div {
      flex: 1;
      background-color: #f1f1f1;
      padding: 20px;
      text-align: center;
    }
   
    .extra-item {
      flex-grow: 1;
      background-color: #e3e3e3;
      padding: 20px;
      text-align: center;
    }
   
    /* Exercício 4: Reordenação de Itens */
    .container4 {
      display: flex;
    }
   
    .container4 > div {
      flex: 1;
      background-color: #f1f1f1;
      padding: 20px;
      text-align: center;
    }
   
    .item1 {
      order: 3;
    }
   
    .item2 {
      order: 1;
    }
   
    .item3 {
      order: 4;
    }
   
    .item4 {
      order: 2;
    }
   
    .item5 {
      order: 5;
    }
   
    /* Exercício 5: Layout Complexo com Flexbox */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }
   
    .container5 {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
   
    header, footer {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
   
    .content {
      display: flex;
      flex-grow: 1;
    }
   
    .sidebar {
      background-color: #f1f1f1;
      padding: 20px;
      width: 200px;
    }
   
    .sidebar ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
      display: flex;
      flex-direction: column;
      justify-content: center;
      height: 100%;
    }
   
    .sidebar li {
      margin-bottom: 10px;
    }
   
    .sidebar a {
      color: #333;
      text-decoration: none;
    }
   
    main {
      flex-grow: 1;
      padding: 20px;
    }
  </style>
</head>
<body>
  <!-- Exercício 1: Layout Básico -->
  <h2>Exercício 1: Layout Básico</h2>
  <div class="container1">
    <div>Coluna 1</div>
    <div>Coluna 2</div>
    <div>Coluna 3</div>
  </div>
 
  <!-- Exercício 2: Alinhamento Vertical -->
  <h2>Exercício 2: Alinhamento Vertical</h2>
  <div class="container2">
    <div class="item1">Item 1</div>
    <div class="item2">Item 2</div>
    <div class="item3">Item 3</div>
  </div>
 
  <!-- Exercício 3: Distribuição de Espaço -->
  <h2>Exercício 3: Distribuição de Espaço</h2>
  <div class="container3">
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
    <div>Item 4</div>
    <div class="extra-item">Item Extra</div>
  </div>
 
  <!-- Exercício 4: Reordenação de Itens -->
  <h2>Exercício 4: Reordenação de Itens</h2>
  <div class="container4">
    <div class="item1">Item 1</div>
    <div class="item2">Item 2</div>
    <div class="item3">Item 3</div>
    <div class="item4">Item 4</div>
    <div class="item5">Item 5</div>
  </div>
 
  <!-- Exercício 5: Layout Complexo com Flexbox -->
  <h2>Exercício 5: Layout Complexo com Flexbox</h2>
  <div class="container5">
    <header>
      <h1>Cabeçalho</h1>
    </header>
   
    <div class="content">
      <nav class="sidebar">
        <ul>
          <li><a href="#">Item 1</a></li>
          <li><a href="#">Item 2</a></li>
          <li><a href="#">Item 3</a></li>
        </ul>
      </nav>
     
      <main>
        <h2>Conteúdo Principal</h2>
        <p>Conteúdo da página...</p>
      </main>
    </div>
   
    <footer>
      <p>&copy; 2023 Meu Site</p>
    </footer>
  </div>
</body>
</html>
