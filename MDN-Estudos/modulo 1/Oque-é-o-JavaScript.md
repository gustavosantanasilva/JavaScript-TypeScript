# Oque é o JavaScript

Olá todo esse repositorio é focado em armazenar material de estudos e por isso uso muitos conteudos de terceiros para a elaboração do repositorio entretando eu criei o repositorio com o intuito de aprender e tambem ajudar pessoas como eu que está iniciando na area então lembrando que todo conteudo estudado neste portifolio está disponivel em **[MDN](https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/Scripting/What_is_JavaScript#defini%C3%A7%C3%A3o_de_alto_n%C3%ADvel)**

## Definição de alto nível

**JavaScript** é uma linguagem de programação que nos permite implementar itens complexos em páginas web. toda vez que uma página da web faz mais do que simplesmente mostrar textos e imagens de forma estática. O javaScript nos possibilita mostrar conteúdo que se atualiza em um intervalo de tempo, mapas interativos, gráficos 2D/3D animados etc.

O JavaScript é a terceira camada do bolo das tecnologias padrões da web, duas das quais (HTML e CSS).

![foto-camadas-web](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/What_is_JavaScript/cake.png)

- **HTML** é a linguagem de marcação de texto que nós usamos para estruturar paginas web, definindo paragrafos, titulos, imagens, videos etc.

- **CSS** é a linguagem de regras de estilos que nós usamos para aplicar estilo a todo o conteudo da nossa pagina como alterar cores, fontes, tamanhos, fundos, posicionamento etc.

- **JavaScript** é uma linguagem de programação que permite a você criar conteúdo que se atualiza dinamicamente, controlar multimidias, imagens animadas, e varias outras coisas interessantes.

As três camadas se encaixa muito bem umas as outras. Um exemplo simples :

```HTML
<p>Jogador 1 : Chris</p>
```

Nós podemos adicionar um pouco de CSS no nosso elemento p para deixa mais atraente :

```CSS
p {
  font-family: "helvetica neue", helvetica, sans-serif;
  letter-spacing: 1px;
  text-transform: uppercase;
  text-align: center;
  border: 2px solid rgba(0, 0, 200, 0.6);
  background: rgba(0, 0, 200, 0.3);
  color: rgba(0, 0, 200, 0.6);
  box-shadow: 1px 1px 2px rgba(0, 0, 200, 0.4);
  border-radius: 10px;
  padding: 3px 10px;
  display: inline-block;
  cursor: pointer;
}
```

E finalmente , nós podemos adicionar JavaScript para implementar um componente dinâmico :

```JavaScript

const paragrafo = document.querySelector("p");

paragrafo.addEventListener("click", atualizarNome);
function atualizarNome(){
  let nome = prompt("Insira um novo nome");
  paragrafo.textContent = "Jogador 1: "+ nome;
}
```
