# aula-curso-Guanabara-
Sexta aula do curso do Guanabara em JS > Java script 
```
<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>aula 006 do Guanabara</title>
</head>
<style>
  div#teste{
    background: black;
    font: arial;
    left: 80px;
    color: blue;
    width: 200px;
    height: 200px;
    text-align: center;
    line-height: 200px;
  }
  
</style>

<body>
  
 
<div id="teste" onclick="clica()" onmouseover="entra()" onmouseout="sair()"
   interagem comigo
 </div>
<script>
var clickp = window.document.getElementById("teste")
/*/####### jeito mais fácil ###$$$$$//

clickp.addEventListener("click" , clica)
clickp.addEventListener("onmouseover",entra)
clickp.addEventListener("onmouseout" , sair)

//########## jeito mais fácil ########/*/

  function clica (){
    clickp.style.color = "red"
    clickp.innerText = "clicou ✅"
  
    clickp.style.background = "blue"
  }
  function entra(){
    clickp.innerText = "pasou o cursor "
    clickp.style.background = "yellow"
  }
  function sair(){
    clickp.style.color = "pink"
    clickp.innerText = "tirou o cursor"
    clickp.style.background = "white "
    
  }
</script>
  
</body>

</html>

```
