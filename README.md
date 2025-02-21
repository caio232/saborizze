# saborizze
menu saborizze 
<!DOCTYPE html> 
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Saborize - Cardápio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #efebf2;
      color: #150101;
      margin: 0;
      padding: 20px;
    }
    .header {
      text-align: center;
      background-color: #f0ebf4;
      color: #8f0bf5;
      padding: 20px 10px;
      border-radius: 10px;
    }
    .language-selector {
      margin-top: 10px;
    }
    .language-selector button {
      background-color: #F7C948;
      border: none;
      padding: 8px 12px;
      margin: 0 5px;
      cursor: pointer;
      border-radius: 8px;
      font-weight: bold;
      display: flex;
      align-items: center;
      gap: 5px;
    }
    .language-selector img {
      width: 20px;
      height: 15px;
      border: 1px solid #8c5151;
      border-radius: 2px;
    }
    .menu-section {
      margin-top: 30px;
    }
    h2 {
      color: #5E2A84;
      border-bottom: 2px solid #F7C948;
      padding-bottom: 5px;
    }
    h3 {
      margin-top: 20px;
      color: #5E2A84;
    }
    .item {
      display: flex;
      justify-content: space-between;
      padding: 10px 0;
      border-bottom: 1px solid #ca27d0;
    }
    .qr-code {
      text-align: center;
      margin-top: 40px;
    }
    .qr-code img {
      width: 200px;
      height: 200px;
      border: 5px solid #F7C948;
      border-radius: 15px;
    }
    .illustration {
      width: 100%;
      max-width: 300px;
      margin: 15px auto;
      display: block;
      border-radius: 10px;
    }



    /* Cabeçalho */
.header {
    text-align: center;
    padding: 20px;
    background-color: #5E2A84;
    position: relative;
}

/* Barra superior com idiomas e Instagram */
.top-bar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
    max-width: 800px;
    margin: 0 auto;
}

/* Idiomas alinhados no topo */
.language-selector {
    display: flex;
    gap: 15px;
}

.language-selector button {
    background: none;
    border: none;
    font-size: 16px;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 8px;
    font-weight: bold;
}

.language-selector button img {
    width: 24px;
}

/* Instagram no canto direito */
.social-media a img {
    width: 30px;
    transition: 0.3s;
}

.social-media a img:hover {
    transform: scale(1.1);
}

/* Logo centralizada */
.logo-container {
    display: flex;
    justify-content: center;
    margin-top: 20px;
}

.logo {
    width: 150px; /* Ajuste conforme necessário */
}




.header {
    text-align: center;
    padding: 20px;
    background-color: #fff;
}

.logo {
    width: 120px; /* Ajuste conforme necessário */
    display: block;
    margin: 0 auto 10px;
}

.language-container {
    margin-top: 10px;
}

.language-selector {
    display: flex;
    justify-content: center;
    gap: 10px;
}

.language-selector button {
    background: #8f0bf5;
    border: 1px solid #8f0bf5;
    padding: 8px 15px;
    display: flex;
    align-items: center;
    gap: 5px;
    cursor: pointer;
    border-radius: 5px;
    transition: 0.3s;
}

.language-selector button:hover {
    background: #8f0bf5;
}




  </style>
</head>
<body>
 
    <style>  </style>
 
    <div class="header">
        <img src="./FOTOS/Captura de ecrã 2025-02-21 020339.png" alt="Saborize Logo" class="logo"> <!-- Logo no topo -->
        <h1>Saborize</h1>
        
        <div class="language-container">
            <p>🌍 Escolha seu idioma:</p> <!-- Mensagem sugestiva -->
            <div class="language-selector">
                <button onclick="setLanguage('pt')">
                    <img src="https://flagcdn.com/w40/pt.png" alt="PT"> Português
                </button>
                <button onclick="setLanguage('en')">
                    <img src="https://flagcdn.com/w40/gb.png" alt="EN"> English
                </button>
                <button onclick="setLanguage('fr')">
                    <img src="https://flagcdn.com/w40/fr.png" alt="FR"> Français
                </button>
            </div>
        </div>
    </div>
    
    
    
    
      
 


  <div class="menu-section" id="tapioca-section">
    <h2>Tapioca</h2>
    <img class="illustration" src="./FOTOS/Tapioca de Chocolate com Morango (1).jpg" alt="Tapioca" />
    <div class="item" data-pt="Frango com queijo" data-en="Chicken with cheese" data-fr="Poulet avec fromage"><span></span><span>8,00€</span></div>
    <div class="item" data-pt="Carne e queijo" data-en="Beef with cheese" data-fr="Boeuf avec fromage"><span></span><span>8,00€</span></div>
    <div class="item" data-pt="Queijo mozzarella" data-en="Mozzarella cheese" data-fr="Fromage mozzarella"><span></span><span>11,00€</span></div>
    <div class="item" data-pt="Doce de leite" data-en="Dulce de leche" data-fr="Confiture de lait"><span></span><span>8,00€</span></div>
    <div class="item" data-pt="Dois amores" data-en="Two loves" data-fr="Deux amours"><span></span><span>8,00€</span></div>
  </div>

  <div class="menu-section" id="pastel-section">
    
    <img class="illustration" src="./FOTOS/Brazilian Street Fair Pastel.jpg" alt="Pastel" />
    <h2>PASTEL BASE 4,90€</h2>
    <p>SABORES: CARNE, FRANGO, QUEIJO, PIZZA (fiambre, queijo, tomate, orégano)</p>
    <div class="item" data-pt="Carne" data-en="Beef" data-fr="Boeuf"><span>Carne</span><span>4,90€</span></div>
    <div class="item" data-pt="Frango" data-en="Chicken" data-fr="Poulet"><span>Frango</span><span>4,90€</span></div>
    <div class="item" data-pt="Queijo" data-en="Cheese" data-fr="Fromage"><span>Queijo</span><span>4,90€</span></div>
    <div class="item" data-pt="Pizza" data-en="Pizza" data-fr="Pizza"><span>Pizza (fiambre, queijo, tomate, orégano)</span><span>4,90€</span></div>
    <div class="item" data-pt="Carne Seca" data-en="Dried beef" data-fr="Viande séchée"><span>Carne Seca</span><span>7,50€</span></div>
  
    <h3>PASTEL VENTO 3,90€</h3>
    <div class="item" data-pt="Pastel Vento" data-en="Wind pastry" data-fr="Pâtisserie légère"><span>Pastel Vento</span><span>3,90€</span></div>
  
    <h3>PASTEL DOCE 5,90€</h3>
    <div class="item" data-pt="Romeu e Julieta" data-en="Romeo and Juliet" data-fr="Roméo et Juliette">
      <span>Romeu e Julieta (goiabada com queijo)</span><span>5,90€</span>
    </div>
    <div class="item" data-pt="Dois Amores" data-en="Two Loves" data-fr="Deux Amours">
      <span>Dois Amores (creme de avelã com morango)</span><span>5,90€</span>
    </div>
  
    <h3>INGREDIENTES EXTRAS (+1,35€)</h3>
   
    <div class="item" data-pt="Carne extra" data-en="Extra beef" data-fr="Boeuf supplémentaire"><span>Carne extra</span><span>+1,35€</span></div>
    <div class="item" data-pt="Frango extra" data-en="Extra chicken" data-fr="Poulet supplémentaire"><span>Frango extra</span><span>+1,35€</span></div>
    
  <p></p>
    <h3>INGREDIENTES EXTRAS 1,00€</h3>
    <div class="item" data-pt="Azeitonas" data-en="Olives" data-fr="Olives"><span>Azeitonas</span><span>+1,00€</span></div>
    <div class="item" data-pt="Bacon" data-en="Bacon" data-fr="Bacon"><span>Bacon</span><span>+1,00€</span></div>
    <div class="item" data-pt="Cebola" data-en="Onion" data-fr="Oignon"><span>Cebola</span><span>+1,00€</span></div>
    <div class="item" data-pt="Cogumelos" data-en="Mushrooms" data-fr="Champignons"><span>Cogumelos</span><span>+1,00€</span></div>
    <div class="item" data-pt="Fiambre" data-en="Ham" data-fr="Jambon"><span>Fiambre</span><span>+1,00€</span></div>
    <div class="item" data-pt="Milho" data-en="Corn" data-fr="Maïs"><span>Milho</span><span>+1,00€</span></div>
    <div class="item" data-pt="Palmito" data-en="Heart of palm" data-fr="Cœur de palmier"><span>Palmito</span><span>+1,00€</span></div>
    <div class="item" data-pt="Queijo Cheddar" data-en="Cheddar cheese" data-fr="Fromage cheddar"><span>Queijo Cheddar</span><span>+1,00€</span></div>
    <div class="item" data-pt="Queijo Mozzarela" data-en="Mozzarella cheese" data-fr="Fromage mozzarella"><span>Queijo Mozzarela</span><span>+1,00€</span></div>
    <div class="item" data-pt="Queijo Catupiry" data-en="Catupiry cheese" data-fr="Fromage catupiry"><span>Queijo Catupiry</span><span>+1,00€</span></div>
    <div class="item" data-pt="Tomate" data-en="Tomato" data-fr="Tomate"><span>Tomate</span><span>+1,00€</span></div>
  </div>
  

  <div class="menu-section" id="acai-section">
    <h2>Açaí</h2>
    <img class="illustration" src="./FOTOS/Veja Como Ganhar Dinheiro com a Venda de Açaí no Copo 🥤💜 Clique no Pin.jpg" alt="Açaí" />
    <div class="item" data-pt="300g (2 toppings)" data-en="300g (2 toppings)" data-fr="300g (2 garnitures)">
      <span>300g (2 toppings)</span><span>6,90€</span>
    </div>
    <div class="item" data-pt="400g (3 toppings)" data-en="400g (3 toppings)" data-fr="400g (3 garnitures)">
      <span>400g (3 toppings)</span><span>8,90€</span>
    </div>
    <div class="item" data-pt="500g (4 toppings)" data-en="500g (4 toppings)" data-fr="500g (4 garnitures)">
      <span>500g (4 toppings)</span><span>10,90€</span>
    </div>
  
    <h3>Toppings</h3>
    <p>Toppings inclusos conforme o tamanho do açaí. Toppings extras +1,00€ cada.</p>
    <div class="item" data-pt="Aveia" data-en="Oats" data-fr="Avoine"><span>Aveia</span><span>+1,00€</span></div>
    <div class="item" data-pt="Banana" data-en="Banana" data-fr="Banane"><span>Banana</span><span>+1,00€</span></div>
    <div class="item" data-pt="Calda de Caramelo" data-en="Caramel syrup" data-fr="Sirop de caramel"><span>Calda de Caramelo</span><span>+1,00€</span></div>
    <div class="item" data-pt="Calda de Morango" data-en="Strawberry syrup" data-fr="Sirop de fraise"><span>Calda de Morango</span><span>+1,00€</span></div>
    <div class="item" data-pt="Calda de Chocolate" data-en="Chocolate syrup" data-fr="Sirop de chocolat"><span>Calda de Chocolate</span><span>+1,00€</span></div>
    <div class="item" data-pt="Creme de Avelã" data-en="Hazelnut cream" data-fr="Crème de noisette"><span>Creme de Avelã</span><span>+1,00€</span></div>
    <div class="item" data-pt="Farinha Láctea" data-en="Lactose flour" data-fr="Farine lactée"><span>Farinha Láctea</span><span>+1,00€</span></div>
    <div class="item" data-pt="Granola" data-en="Granola" data-fr="Granola"><span>Granola</span><span>+1,00€</span></div>
    <div class="item" data-pt="Leite Condensado" data-en="Condensed milk" data-fr="Lait concentré"><span>Leite Condensado</span><span>+1,00€</span></div>
    <div class="item" data-pt="Leite em Pó" data-en="Powdered milk" data-fr="Lait en poudre"><span>Leite em Pó</span><span>+1,00€</span></div>
    <div class="item" data-pt="Mel" data-en="Honey" data-fr="Miel"><span>Mel</span><span>+1,00€</span></div>
    <div class="item" data-pt="Morango" data-en="Strawberry" data-fr="Fraise"><span>Morango</span><span>+1,00€</span></div>
    <div class="item" data-pt="Paçoca" data-en="Peanut candy" data-fr="Bonbon d'arachide"><span>Paçoca</span><span>+1,00€</span></div>
  </div>
  

  

 
  <!-- Seção de Milkshake -->
  <div class="menu-section" id="milkshake-section">
    <h2>Milkshake</h2>
    <img class="illustration" src="./FOTOS/The best milkshake in every US state.jpg" alt="Milkshake" />
    <div class="item" data-pt="Açaí" data-en="Açaí" data-fr="Açaí"><span>Açaí</span><span>6,90€</span></div>
    <div class="item" data-pt="Morango" data-en="Strawberry" data-fr="Fraise"><span>Morango</span><span>6,90€</span></div>
    <div class="item" data-pt="Nutella" data-en="Nutella" data-fr="Nutella"><span>Nutella</span><span>6,90€</span></div>
    <div class="item" data-pt="Oreo" data-en="Oreo" data-fr="Oreo"><span>Oreo</span><span>6,90€</span></div>
    <div class="item" data-pt="Ovomaltine" data-en="Ovomaltine" data-fr="Ovomaltine"><span>Ovomaltine</span><span>6,90€</span></div>
    <div class="item" data-pt="Paçoca" data-en="Peanut candy" data-fr="Bonbon d'arachide"><span>Paçoca</span><span>6,90€</span></div>
    <div class="item" data-pt="Chocolate" data-en="Chocolate" data-fr="Chocolat"><span>Chocolate</span><span>6,90€</span></div>
  </div>

  <!-- Seção de Vitaminas -->
  <div class="menu-section" id="vitamina-section">
    <h2>Vitamina 400ml</h2>
    <img class="illustration" src="./FOTOS/Shake de açaí_ http___abr_ai_1fZziSu.jpg" alt="Vitamina" />
    <div class="item" data-pt="Açaí, banana e morango" data-en="Açaí, banana and strawberry" data-fr="Açaí, banane et fraise">
      <span>Açaí, banana e morango</span><span>6,90€</span>
    </div>
  </div>

  <!-- Seção de Sumos de Polpa -->
  <div class="menu-section" id="sumos-polpa-section">
    <h2>Sumos de Polpa</h2>
    <img class="illustration" src="./FOTOS/Suco Verde Detox - Receita Natureba.jpg" alt="Sumos de Polpa" />
    <div class="item" data-pt="Abacaxi" data-en="Pineapple" data-fr="Ananas"><span>Abacaxi</span><span>3,50€</span></div>
    <div class="item" data-pt="Acerola" data-en="Acerola" data-fr="Acerola"><span>Acerola</span><span>3,50€</span></div>
    <div class="item" data-pt="Cupuaçu" data-en="Cupuaçu" data-fr="Cupuaçu"><span>Cupuaçu</span><span>3,50€</span></div>
    <div class="item" data-pt="Frutos Vermelhos" data-en="Red fruits" data-fr="Fruits rouges"><span>Frutos Vermelhos</span><span>3,50€</span></div>
    <div class="item" data-pt="Goiaba" data-en="Guava" data-fr="Goyave"><span>Goiaba</span><span>3,50€</span></div>
    <div class="item" data-pt="Graviola" data-en="Soursop" data-fr="Graviola"><span>Graviola</span><span>3,50€</span></div>
    <div class="item" data-pt="Manga" data-en="Mango" data-fr="Mangue"><span>Manga</span><span>3,50€</span></div>
    <div class="item" data-pt="Maracujá" data-en="Passion fruit" data-fr="Fruit de la passion"><span>Maracujá</span><span>3,50€</span></div>
    <div class="item" data-pt="Cajá" data-en="Cajá" data-fr="Cajá"><span>Cajá</span><span>3,50€</span></div>
  </div>

  <!-- Seção de Sumos Detox -->
  <div class="menu-section" id="sumos-detox-section">
    <h2>Sumos Detox</h2>
    <img class="illustration" src="./FOTOS/5 Benefícios do Suco detox.jpg" alt="Sumos Detox" />
    <div class="item" data-pt="Laranja (cenoura, laranja, maçã e gengibre)" data-en="Orange (carrot, orange, apple and ginger)" data-fr="Orange (carotte, orange, pomme et gingembre)">
      <span>Laranja (cenoura, laranja, maçã e gengibre)</span><span>4,50€</span>
    </div>
    <div class="item" data-pt="Verde (couve, ananás, maçã verde, alho e gengibre)" data-en="Green (kale, pineapple, green apple, garlic and ginger)" data-fr="Vert (chou, ananas, pomme verte, ail et gingembre)">
      <span>Verde (couve, ananás, maçã verde, alho e gengibre)</span><span>4,50€</span>
    </div>
    <div class="item" data-pt="Vermelho (beterraba, cenoura, laranja, maçã e gengibre)" data-en="Red (beetroot, carrot, orange, apple and ginger)" data-fr="Rouge (betterave, carotte, orange, pomme et gingembre)">
      <span>Vermelho (beterraba, cenoura, laranja, maçã e gengibre)</span><span>4,50€</span>
    </div>
  </div>

  <!-- Seção de Sumos Naturais -->
  <div class="menu-section" id="sumos-naturais-section">
    <h2>Sumos Naturais</h2>
    <img class="illustration" src="./FOTOS/Suco para reduzir gordura do fígado_ veja 3 receitas naturais.jpg" alt="Sumos Naturais" />
    <h3>1 Fruta - 3,50€</h3>
    <div class="item" data-pt="Abacaxi" data-en="Pineapple" data-fr="Ananas"><span>Abacaxi</span><span>3,50€</span></div>
    <div class="item" data-pt="Beterraba" data-en="Beetroot" data-fr="Betterave"><span>Beterraba</span><span>3,50€</span></div>
    <div class="item" data-pt="Cenoura" data-en="Carrot" data-fr="Carotte"><span>Cenoura</span><span>3,50€</span></div>
    <div class="item" data-pt="Laranja" data-en="Orange" data-fr="Orange"><span>Laranja</span><span>3,50€</span></div>
    <div class="item" data-pt="Maçã" data-en="Apple" data-fr="Pomme"><span>Maçã</span><span>3,50€</span></div>
    <div class="item" data-pt="Melancia" data-en="Watermelon" data-fr="Pastèque"><span>Melancia</span><span>3,50€</span></div>
    <div class="item" data-pt="Morango" data-en="Strawberry" data-fr="Fraise"><span>Morango</span><span>3,50€</span></div>

    <h3>2 Frutas - 4,00€</h3>
    <div class="item" data-pt="Beterraba e Laranja" data-en="Beetroot and Orange" data-fr="Betterave et Orange">
      <span>Beterraba e Laranja</span><span>4,00€</span>
    </div>
    <div class="item" data-pt="Laranja e Cenoura" data-en="Orange and Carrot" data-fr="Orange et Carotte">
      <span>Laranja e Cenoura</span><span>4,00€</span>
    </div>
    <div class="item" data-pt="Melancia e Morango" data-en="Watermelon and Strawberry" data-fr="Pastèque et Fraise">
      <span>Melancia e Morango</span><span>4,00€</span>
    </div>
    <div class="item" data-pt="Morango e Laranja" data-en="Strawberry and Orange" data-fr="Fraise et Orange">
      <span>Morango e Laranja</span><span>4,00€</span>
    </div>
  </div>

  <!-- Seção de Sumos Especiais -->
  <div class="menu-section" id="sumos-especiais-section">
    <h2>Sumos Especiais</h2>
    <img class="illustration" src="./FOTOS/Sumos detox são uma opção realmente saudável_.jpg" alt="Sumos Especiais" />
    <div class="item" data-pt="Açaí" data-en="Açaí" data-fr="Açaí"><span>Açaí</span><span>4,50€</span></div>
    <div class="item" data-pt="Açaí com Laranja" data-en="Açaí with Orange" data-fr="Açaí avec Orange">
      <span>Açaí com Laranja</span><span>5,00€</span>
    </div>
  </div>

  <!-- Seção de Bebidas -->
  <div class="menu-section" id="bebidas-section">
    <h2>Bebidas</h2>
    <img class="illustration" src="./FOTOS/Agua tonica bebidas - Benefícios.jpg" alt="Bebidas" />
    <div class="item" data-pt="Água 0,50L" data-en="Water 0,50L" data-fr="Eau 0,50L"><span>Água 0,50L</span><span>1,50€</span></div>
    <div class="item" data-pt="Água Tónica" data-en="Tonic Water" data-fr="Eau Tonic"><span>Água Tónica</span><span>2,00€</span></div>
    <div class="item" data-pt="Água com Gás" data-en="Sparkling Water" data-fr="Eau Gazeuse"><span>Água com Gás</span><span>2,00€</span></div>
    <div class="item" data-pt="Água com Gás sabor Limão" data-en="Sparkling Water with Lemon" data-fr="Eau Gazeuse au Citron">
      <span>Água com Gás sabor Limão</span><span>2,20€</span>
    </div>
    <div class="item" data-pt="Refrigerante Lata" data-en="Soda Can" data-fr="Canette de Soda"><span>Refrigerante Lata</span><span>2,30€</span></div>
    <div class="item" data-pt="Imperial" data-en="Imperial" data-fr="Imperial"><span>Imperial</span><span>2,00€</span></div>
    <div class="item" data-pt="Tulipa 0,35L" data-en="Tulip 0,35L" data-fr="Tulipe 0,35L"><span>Tulipa 0,35L</span><span>2,50€</span></div>
    <div class="item" data-pt="Tulipa 0,40L" data-en="Tulip 0,40L" data-fr="Tulipe 0,40L"><span>Tulipa 0,40L</span><span>3,00€</span></div>
    <div class="item" data-pt="Caneca 0,50L" data-en="Mug 0,50L" data-fr="Chope 0,50L"><span>Caneca 0,50L</span><span>3,50€</span></div>
    <div class="item" data-pt="Somersby 0,33L" data-en="Somersby 0,33L" data-fr="Somersby 0,33L"><span>Somersby 0,33L</span><span>3,00€</span></div>
    <div class="item" data-pt="Caneca Somersby 0,50L" data-en="Somersby Mug 0,50L" data-fr="Chope Somersby 0,50L">
      <span>Caneca Somersby 0,50L</span><span>4,00€</span>
    </div>
    <div class="item" data-pt="Copo Sangria" data-en="Sangria Glass" data-fr="Verre de Sangria"><span>Copo Sangria</span><span>3,20€</span></div>
    <div class="item" data-pt="Caneca Sangria" data-en="Sangria Mug" data-fr="Chope de Sangria"><span>Caneca Sangria</span><span>4,00€</span></div>
    <div class="item" data-pt="Caipirinha" data-en="Caipirinha" data-fr="Caipirinha"><span>Caipirinha</span><span>6,50€</span></div>
    <div class="item" data-pt="Caipiroska" data-en="Caipiroska" data-fr="Caipiroska"><span>Caipiroska</span><span>7,00€</span></div>
    <div class="item" data-pt="Montijo" data-en="Montijo" data-fr="Montijo"><span>Montijo</span><span>7,50€</span></div>
    <div class="item" data-pt="Gin Tónica" data-en="Gin and Tonic" data-fr="Gin Tonic"><span>Gin Tónica</span><span>7,00€</span></div>
    <div class="item" data-pt="Piña Colada" data-en="Piña Colada" data-fr="Piña Colada"><span>Piña Colada</span><span>7,50€</span></div>
    <div class="item" data-pt="Daiquiri" data-en="Daiquiri" data-fr="Daiquiri"><span>Daiquiri</span><span>7,50€</span></div>
  </div>

  <!-- Seção de Bebidas Quentes -->
  <div class="menu-section" id="bebidas-quentes-section">
    <h2>Bebidas Quentes</h2>
    <img class="illustration" src="./FOTOS/Vai um choconhaque ai_!.jpg" alt="Bebidas Quentes" />
    <div class="item" data-pt="Café" data-en="Coffee" data-fr="Café"><span>Café</span><span>1,20€</span></div>
    <div class="item" data-pt="Descafeinado" data-en="Decaf Coffee" data-fr="Café Décaféiné"><span>Descafeinado</span><span>1,30€</span></div>
    <div class="item" data-pt="Abatanado" data-en="Abatanado" data-fr="Abatanado"><span>Abatanado</span><span>1,30€</span></div>
    <div class="item" data-pt="Abatanado Descafeinado" data-en="Decaf Abatanado" data-fr="Abatanado Décaféiné">
      <span>Abatanado Descafeinado</span><span>1,40€</span>
    </div>
    <div class="item" data-pt="Carioca de Limão Pequeno" data-en="Small Lemon Carioca" data-fr="Petit Carioca au Citron">
      <span>Carioca de Limão Pequeno</span><span>1,00€</span>
    </div>
    <div class="item" data-pt="Carioca de Limão Grande" data-en="Large Lemon Carioca" data-fr="Grand Carioca au Citron">
      <span>Carioca de Limão Grande</span><span>1,30€</span>
    </div>
    <div class="item" data-pt="Copo de Leite" data-en="Glass of Milk" data-fr="Verre de Lait"><span>Copo de Leite</span><span>1,20€</span></div>
    <div class="item" data-pt="Meia de Leite" data-en="Half Milk" data-fr="Demi Lait"><span>Meia de Leite</span><span>1,80€</span></div>
    <div class="item" data-pt="Chocolate Quente (borda com doce de leite ou nutella)" data-en="Hot Chocolate (rim with dulce de leche or nutella)" data-fr="Chocolat Chaud (bordure avec confiture de lait ou nutella)">
      <span>Chocolate Quente (borda com doce de leite ou nutella)</span><span>5,50€</span>
    </div>
    <div class="item" data-pt="Chá" data-en="Tea" data-fr="Thé"><span>Chá</span><span>1,80€</span></div>
  </div>

  <!-- Mensagem Final -->
  <div class="footer-message">
    <p>A PARTIR DAS 19H AS BEBIDAS ACRESCEM UM VALOR DE 0,50€</p>
    <p>EMBALAGENS TAKE AWAY: SACOS 0,10€, SACO PAPEL 0,20€, COPO 0,10€</p>
    <p>IVA INCLUÍDO À TAXA LEGAL EM VIGOR</p>
    <p>CONHEÇA A LOJA MATRIZ NA Av. Almirante Reis, 231C, Lisboa 1000-049 Portugal</p>
  </div>

  <div class="qr-code">
    <h2>Acesse o Cardápio Online</h2>
    <img src="https://via.placeholder.com/200x200.png?text=QR+Code" alt="QR Code para o cardápio" />
  </div>

  <script>
    function setLanguage(lang) {
      const items = document.querySelectorAll('.item');
      items.forEach(item => {
        const span = item.querySelector('span:first-child');
        span.textContent = item.getAttribute(data-${lang});
      });
    }

    setLanguage('pt');



  </script>

<script>
    function setLanguage(lang) {
      document.querySelectorAll(".item").forEach((item) => {
        let text = item.getAttribute(`data-${lang}`);
        if (text) {
          item.children[0].textContent = text; // Atualiza o nome do item
        }
      });
    }
  </script>
  <div style="text-align: center; margin-top: 20px;">
    <a href="" target="_blank" style="text-decoration: none; font-size: 18px; background-color: #F7C948; padding: 10px 15px; border-radius: 8px; color: #5E2A84; font-weight: bold;">
      📷 Siga-nos no Instagram
    </a>
  </div>
  
  <div  style="text-align: center; margin-top: 20px;">
    <a href="https://www.instagram.com/saborizze.oficial/" target="_blank">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram" width="50">
    </a>
  </div>
  

  
  <script>
    function setLanguage(lang) {
      document.querySelectorAll(".item").forEach(item => {
        // Seleciona o texto correto baseado no idioma escolhido
        let translatedText = item.getAttribute(`data-${lang}`);
        
        // Insere o texto dentro do primeiro <span> do item
        item.querySelector("span:first-child").textContent = translatedText;
      });
    }
  
    // Define o idioma padrão (português) ao carregar a página
    document.addEventListener("DOMContentLoaded", () => {
      setLanguage('pt');
    });
  </script>
  


</body>
</html>
