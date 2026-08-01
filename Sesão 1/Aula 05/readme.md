# Aula 05

## Nesta aula nos mesclamos HTML com JavaScript usando o navegador em vez do Node JS

#### para fazermos isso é necessario criar um arquivo HTML e outro arquivo JS EX:

```HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Titulo da pagina</title>
</head>
<body> 
  

<script src="main.js"></script> <!-- Essa Linha importa o codigo do arquivo main.js para essa pagina html-->
</body>
</html>
```

### Codigo do arquivo main.js :

```JavaScript
// Aqui vai ficar todo comando que eu quero que seja execultado quando o usuario estiver na pagina index.html

let nome = prompt("Digite seu nome : "); // Comando que pede pro usuario digitar um valor em uma caixa padrão do navegador esse comando não funciona no Node JS só no navegador

alert(`Sejá bem vindo ${nome}`); // Mostra um alerta com uma mensagem em uma caixa padrão do navegador; -- Esse cimando não funciona no Node JS só no navegador
```