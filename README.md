<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>nyckzadas</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body id="body">
<header>
  <h1><em>bem vindo ao formulario</em></h1>
  
  <button onclick="fun ()">mudar fundo</button>

  <script>
let fundo = true;
let fundo1 = document.getElementById("body");

    
    function fun() {
      if (fundo == true) {
        
        fundo1.style.backgroundColor = "white";
        fundo1.style.color = "black";
        fundo = false;
        
      } else {
        
        fundo1.style.backgroundColor = "black";
        fundo1.style.color = "white";
        fundo = true;
        
      }
    }
  </script>
</header>

<br>
  
<section>
  
<form action="https://formspree.io/f/xldnljlg" method="POST">

<fieldset>
  
  <label>qual seu nome?</label>

<br>
  <br>
  
  <input name="nome" type="text" placeholder="seu nome">
</fieldset>

  <br>
   <br>

  <fieldset>
<label><em>qual sua idade? (não fará diferença)</em</label>

    <br>
    <br>
    
<input name="idade" type="number" placeholder="sua idade">
  </fieldset>

<br>
<br>

<fieldset>
<label><em>por que você quer fazer parte da administração?</em></label>

  <br>
  <br>
  
  <input name="motivo" type="text" placeholder="seu motivo">
</fieldset>

<br>
  <br>

  <fieldset>
<label><em>seu número do WhatsApp</em></label>

    <br>
    <br>
    
    <input name="numero" type="number" placeholder="seu número">
  </fieldset>

  <br>
  <br>

  <fieldset>
<label><em>tem experiência com programação? se sim, em quais linguagens?</em></label>
    <br>
    <br>
    
    <input name="experiência" type="text" placeholder="sua experiência">
  </fieldset>

  <br>
  <br>

  <fieldset>
<label><em>quanto tempo você tem para se dedicar?</em></label>

    <br>
    <br>

    <input name="tempo" type="text" placeholder="seu tempo">
  </fieldset>

  <br>
  <br>

  <fieldset>
<label><em>tem experiência com administrativo? (tenho certeza que sim)</em></label>

    <br>
    <br>
    <input name="experiência administrativo" type="checkbox">
  </fieldset>
</section>

<footer>
  <br>
  
<button class="but" type="submit">Enviar tudo</button>

<br>
  <br>
  
  <h3><em>site feito pelo braço direito (nyckzadas) do criador.</em></h3>
  <br>
  
  <h4>ajudanyc@gmail.com</h4>
  <h5>+55 53 99982-4100</h5>
</footer>
  <script src="script.js"></script>
</body>
</html>
