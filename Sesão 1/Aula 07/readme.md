# Aula 07

### Nesta aula vimos os tipos primitivos de dados que o JavaScript possui

#### Strings As strings no JavaScript são basicamente textos

### EX :

```JavaScript
let nome = "Nome"; // Isso é uma variavel chamada nome que armazena uma string chamada Nome

// Temos 3 formas de declarar uma string com aspas ' , " e ` :
let nome2 = 'Nome2';
let nome3 = `Nome3`;

// Tambem conseguimos utilizar variaveis dentro de strings esse processo que troca variaveis pelos seus respectivos valores se chama interpolação:

let nomeAluno = "Fulano";
console.log(`O aluno ${nomeAluno} Foi matriculado no Curso de JavaScript Com sucesso!`);


```

#### Numbers : São o tipo de dados numericos inteiros e decimais

### EX :

```JavaScript
let idadeAluno = 17; // A variavel idadeAluno está recebendo um valor do tipo Number que é um numero inteiro

let alturaAluno = 1.80; // A variavel alturaAluno está recebendo um valor do tipo Number que é um numero decimal ou na programação de ponto flutuante

// Tambem é possivel utilizar a interpolação com variaveis do tipo Number EX :

let pesoAluno = 85; // Variavel que armazena o pesso do aluno

let imcAluno = pesoAluno / (alturaAluno ** 2); // Variavel que armazena o IMC do aluno
console.log(`O aluno possui ${idadeAluno} anos, pesa ${pesoAluno} Kg e tem uma altura de ${alturaAluno} m e tem o imc de : ${imcAluno}`);

```

#### Undefined e null : são tipos de dados que indica que uma variavel está vazia ou ausencia de valor

### EX :

```JavaScript

let nomeProfessor; // Uma variavel recebe o valor undefined quando não definimos um valor a ela e isso significa que a variavel não possui nenhum valor armazenado na memoria;

let pesoProfessor = null; // Uma variavel recebe o valor null quando nos definimos isso no codigo ou seja o null e usado propositalmente para indicar que a variavel não possui um valor e está vazia



```

#### Bolean : é um tipo de dado logico que usamos incocientimente ele está presente em toda a programação e é muito ussado para tomar diferentes fluxos de ações em um codigo , fazer verificações etc.

### EX :

```JavaScript

// O tipo boleano possui dois valores : true - > verdadeiro e false -> falso

let alunoAprovado = true; // Geralmente o tipo boleano é utilizado para verificação de condições e tomada de decisão no fluxo do nosso codigo.

if (alunoAprovado){
  console.log("Parabéns você está aprovado!");
}

```

#### Esses são os principais tipos de dados do JavaScript e os fundamentais de toda a programação chamados de tipos primitivos.
