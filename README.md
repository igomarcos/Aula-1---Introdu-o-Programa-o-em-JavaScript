<h1> Aula 1 -  Introdução à Programação em JavaScript 💻</h1>


Seja bem-vindo à nossa aula de introdução à programação em JavaScript! Nesta jornada, exploraremos os conceitos fundamentais que tornam o JavaScript uma das linguagens de programação mais poderosas e amplamente utilizadas no mundo do desenvolvimento web.

JavaScript é uma linguagem de programação versátil e dinâmica que é executada no navegador web dos usuários. Com ela, podemos criar páginas web interativas, aplicativos web complexos e até mesmo servidores de back-end usando frameworks como Node.js.

Ao longo desta aula, vamos mergulhar nos conceitos essenciais que formam a base da programação em JavaScript. Desde operadores lógicos e estruturas condicionais até arrays e matrizes, estruturas de repetição, variáveis e entrada e saída de dados, você aprenderá como escrever código JavaScript eficiente e poderoso.

Prepare-se para uma jornada emocionante no mundo da programação! Vamos começar a explorar os principais conceitos que tornam o JavaScript uma ferramenta indispensável para desenvolvedores web em todo o mundo..

-----

<h2>Topicos </h2>

- ***Operadores Lógicos***
- ***Condicionais em JavaScript***
- ***Arrays e Matrizes***
- ***Estrutura de Repetição***
- ***declarar e atribuir valores a variáveis***
- ***Entrada e Saída de Dados***

-----

<h2>AGORA, VAMOS PARA A AÇÃO! 🕵🏻</h2>

### Operadores Lógicos
Operadores Lógicos em JavaScript: Uma Explicação Simples

Em programação, os operadores lógicos são ferramentas essenciais para realizar operações que envolvem avaliação de expressões booleanas. Esses operadores permitem combinar ou modificar o resultado de expressões booleanas, o que é fundamental para tomada de decisões e controle de fluxo em um programa.

Em JavaScript, existem três principais operadores lógicos: AND (&&), OR (||) e NOT (!). Vamos explicar cada um deles com exemplos práticos:

1. Operador AND (&&):
O operador AND retorna true apenas se ambas as expressões que ele conecta forem verdadeiras.

Exemplo Pratico:
 
   ```javascript
 let idade = 25;
 let possuiCarteiraDeMotorista = true;
 
 if (idade >= 18 && possuiCarteiraDeMotorista) {
     console.log("Você pode dirigir.");
 } else {
     console.log("Você não pode dirigir.");
 }
 
 ```

Neste exemplo, a mensagem "Você pode dirigir." será exibida apenas se a idade for maior ou igual a 18 e a variável possuiCarteiraDeMotorista for true.
-----

2. Operador OR (||):
O operador OR retorna true se pelo menos uma das expressões que ele conecta for verdadeira.

Exemplo pratico:

  ```javascript
 let diaSemana = "Sábado";
let estaChovendo = false;

if (diaSemana === "Sábado" || diaSemana === "Domingo") {
    console.log("É fim de semana!");
} else {
    console.log("É dia de semana.");
}
 ```
Neste exemplo, a mensagem "É fim de semana!" será exibida se o valor da variável diaSemana for "Sábado" ou "Domingo".
-----
3. Operador NOT (!):
O operador NOT inverte o valor de uma expressão booleana. Se a expressão for true, o operador NOT a transforma em false, e vice-versa.

Exemplo pratico:

```javascript
 let solBrilhando = true;

if (!solBrilhando) {
    console.log("Está nublado.");
} else {
    console.log("O sol está brilhando.");
}

 ```
Neste exemplo, a mensagem "O sol está brilhando." será exibida apenas se a variável solBrilhando for true. O operador ! inverte o valor, então o bloco de código dentro do if será executado apenas se o sol não estiver brilhando.

Esses exemplos ilustram como os operadores lógicos são utilizados em JavaScript para tomar decisões com base em condições específicas. Dominar esses operadores é essencial para escrever código claro, eficiente e preciso.
-----

###Estruturas de Condição em JavaScript: Uma Visão Abrangente

As estruturas de condição são fundamentais em programação, pois permitem que um programa execute diferentes ações com base em condições específicas. Em JavaScript, existem várias formas de implementar estruturas de condição, sendo as mais comuns o if, else if e else. Vamos explorar cada uma delas com exemplos práticos:


1. if - Se:
A estrutura if é utilizada para executar um bloco de código se uma condição especificada for verdadeira.

Exemplo pratico:

```javascript
let idade = 18;

if (idade >= 18) {
    console.log("Você é maior de idade.");
}

 ```
Neste exemplo, a mensagem "Você é maior de idade." será exibida apenas se a idade for maior ou igual a 18.
-----

2. else if - Se Não, Se:
A estrutura else if é utilizada para especificar uma nova condição se a condição anterior do if for falsa.

Exemplo pratico:

```javascript
let hora = 15;

if (hora < 12) {
    console.log("Bom dia!");
} else if (hora < 18) {
    console.log("Boa tarde!");
} else {
    console.log("Boa noite!");
}

 ```
Neste exemplo, a mensagem "Bom dia!" será exibida se a hora for menor que 12, "Boa tarde!" será exibida se a hora for menor que 18, e "Boa noite!" será exibida em todos os outros casos.
-----
3. else - Senão:
A estrutura else é utilizada para executar um bloco de código se nenhuma das condições anteriores for verdadeira.

Exemplo pratico:

```javascript
let idade = 15;

if (idade >= 18) {
    console.log("Você é maior de idade.");
} else {
    console.log("Você é menor de idade.");
}
 ```
Neste exemplo, a mensagem "Você é menor de idade." será exibida se a idade for menor que 18.

Esses exemplos ilustram como as estruturas de condição são utilizadas em JavaScript para controlar o fluxo de execução do código com base em condições específicas. Dominar essas estruturas é essencial para escrever programas que sejam capazes de tomar decisões e se adaptar a diferentes situações.
-----

###Arrays e Matrizes em JavaScript: Uma Visão Completa

Em JavaScript, arrays são estruturas de dados fundamentais que nos permitem armazenar e acessar múltiplos valores em uma única variável. Uma matriz é um tipo específico de array que possui duas ou mais dimensões, permitindo armazenar valores em linhas e colunas. Vamos explorar mais sobre arrays e matrizes com exemplos práticos:

1. Arrays:
Um array em JavaScript é uma coleção ordenada de valores, onde cada valor é identificado por um índice numérico.

Exemplo de array:

```javascript
let frutas = ["Maçã", "Banana", "Morango"];

 ```

Para acessar os elementos de um array, usamos seus índices. É importante lembrar que os índices em JavaScript começam em 0.

Exemplo de acesso a elementos de um array:

```javascript
console.log(frutas[0]); // Saída: Maçã
console.log(frutas[1]); // Saída: Banana
console.log(frutas[2]); // Saída: Morango
 ```

Podemos também modificar os elementos de um array ou adicionar novos elementos a ele.

Exemplo de modificação de elementos e adição de novos elementos:

```javascript
frutas[1] = "Pera"; // Modificação do segundo elemento
frutas.push("Abacaxi"); // Adição de um novo elemento ao final do array
console.log(frutas); // Saída: ["Maçã", "Pera", "Morango", "Abacaxi"]

 ```
-----
2. Matrizes:
Uma matriz em JavaScript é um tipo especial de array que possui duas ou mais dimensões. Em uma matriz, os elementos são organizados em linhas e colunas.

Exemplo de matriz:

```javascript
let matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
];
 ```

Para acessar os elementos de uma matriz, usamos os índices da linha e da coluna.

Exemplo de acesso a elementos de uma matriz:

```javascript
console.log(matriz[0][0]); // Saída: 1 (primeiro elemento da primeira linha)
console.log(matriz[1][2]); // Saída: 6 (terceiro elemento da segunda linha)
console.log(matriz[2][1]); // Saída: 8 (segundo elemento da terceira linha)
 ```

Assim como em arrays, podemos modificar os elementos de uma matriz e adicionar novos elementos a ela.

Exemplo de modificação de elementos e adição de novos elementos em uma matriz:

matriz[0][0] = 10; // Modificação do primeiro elemento da primeira linha
matriz[1].push(7); // Adição de um novo elemento ao final da segunda linha
console.log(matriz); // Saída: [[10, 2, 3], [4, 5, 6, 7], [7, 8, 9]]

Arrays e matrizes são ferramentas poderosas que nos permitem manipular e organizar dados de forma eficiente em JavaScript. Ao entender como trabalhar com essas estruturas, podemos criar programas mais robustos e dinâmicos.

-----
###Estruturas de Repetição em JavaScript: Uma Visão Abrangente

As estruturas de repetição, também conhecidas como loops, são utilizadas em programação para executar um bloco de código repetidamente enquanto uma condição específica for verdadeira. Em JavaScript, existem várias formas de implementar estruturas de repetição, sendo as mais comuns o for, while e do...while. Vamos explorar cada uma delas com exemplos práticos:

1. for - Para:
A estrutura for é utilizada para iterar sobre uma sequência de valores (como um array) ou para executar um bloco de código um número específico de vezes.

Exemplo pratico:

```javascript
for (let i = 0; i < 5; i++) {
    console.log(i);
}
 ```
Neste exemplo, o bloco de código dentro do for será executado 5 vezes, e o valor de i será incrementado a cada iteração.
-----

2. while - Enquanto:
A estrutura while é utilizada para executar um bloco de código enquanto uma condição específica for verdadeira.

Exemplo pratico:

```javascript
let contador = 0;
while (contador < 5) {
    console.log(contador);
    contador++;
}
 ```
Neste exemplo, o bloco de código dentro do while será executado enquanto o valor do contador for menor que 5.
-----

3. do...while - Faça Enquanto:
A estrutura do...while é semelhante ao while, mas garante que o bloco de código seja executado pelo menos uma vez, mesmo se a condição inicial for falsa.

Exemplo pratico:

```javascript
let numero = 0;
do {
    console.log(numero);
    numero++;
} while (numero < 5);
 ```
Neste exemplo, o bloco de código dentro do do...while será executado pelo menos uma vez, e continuará sendo executado enquanto o valor de numero for menor que 5.

Esses exemplos ilustram como as estruturas de repetição são utilizadas em JavaScript para executar blocos de código repetidamente com base em condições específicas. Dominar essas estruturas é essencial para escrever programas eficientes e flexíveis.
-----

###Declaração e Atribuição de Valores a Variáveis em JavaScript: Uma Abordagem Prática

Em JavaScript, variáveis são utilizadas para armazenar e manipular dados durante a execução de um programa. Declaração e atribuição são duas etapas fundamentais para utilizar variáveis. Vamos entender melhor cada uma delas e fornecer exemplos práticos:

1. Declaração de Variáveis:
A declaração de variáveis é o processo de reservar um espaço na memória para armazenar um valor. Em JavaScript, você pode declarar uma variável usando as palavras-chave let, const ou var (embora var seja menos utilizada atualmente devido a diferenças de escopo).

Exemplo pratico de declaração de variável:
```javascript
let nome;
 ```
Neste exemplo, declaramos uma variável chamada nome usando a palavra-chave let. A variável nome está inicialmente indefinida e não tem um valor atribuído.

-----

2. Atribuição de Valores a Variáveis:
A atribuição de valores é o processo de associar um valor a uma variável previamente declarada. Em JavaScript, você pode atribuir valores a variáveis usando o operador de atribuição =.

Exemplo de atribuição de valor a uma variável:
```javascript
nome = "João";
 ```
Neste exemplo, atribuímos o valor "João" à variável nome. Agora, a variável nome contém o valor "João" e pode ser usada em outras partes do código.
-----

3. Declaração e Atribuição em uma Única Linha:
Em JavaScript, você também pode declarar e atribuir um valor a uma variável em uma única linha de código.

Exemplo de declaração e atribuição em uma única linha:
```javascript
let idade = 30;
 ```
Neste exemplo, declaramos a variável idade e atribuímos o valor 30 a ela na mesma linha de código.
-----

4. Exemplo Prático:

```javascript
let nome; // Declaração de variável
nome = "Maria"; // Atribuição de valor à variável

let idade = 25; // Declaração e atribuição em uma única linha

console.log("Nome:", nome); // Saída: Nome: Maria
console.log("Idade:", idade); // Saída: Idade: 25
 ```

Neste exemplo, declaramos a variável nome, atribuímos o valor "Maria" a ela e declaramos e atribuímos o valor 25 à variável idade. Em seguida, usamos console.log() para exibir os valores das variáveis no console.

Esses são os conceitos básicos de declaração e atribuição de valores a variáveis em JavaScript. Entender esses conceitos é fundamental para escrever código JavaScript eficiente e claro.
-----

###Entrada e Saída de Dados em JavaScript: Uma Abordagem Prática

Em programação, entrada e saída de dados (também conhecidas como E/S de dados) referem-se ao processo de receber informações de um usuário (entrada) e exibir resultados para o usuário (saída). Em JavaScript, existem várias maneiras de realizar entrada e saída de dados, sendo as mais comuns a utilização dos métodos prompt() e console.log(). Vamos explorar cada um deles com exemplos práticos:

1. Entrada de Dados:
A entrada de dados em JavaScript geralmente envolve a obtenção de informações do usuário através de um formulário ou caixa de diálogo. O método prompt() é frequentemente usado para solicitar entrada do usuário.

Exemplo de entrada de dados usando prompt():
```javascript
let nome = prompt("Digite seu nome:");
console.log("Olá, " + nome + "! Bem-vindo ao nosso site.");
 ```
Neste exemplo, o método prompt() exibe uma caixa de diálogo solicitando ao usuário que digite seu nome. O valor digitado pelo usuário é armazenado na variável nome, que é então exibida na tela usando console.log().
-----

2. Saída de Dados:
A saída de dados em JavaScript envolve exibir informações para o usuário, geralmente usando o método console.log(). Isso é útil para depuração (debugging) ou para fornecer feedback ao usuário.

Exemplo de saída de dados usando console.log():
```javascript
let resultado = "Parabéns, você concluiu a tarefa com sucesso!";
console.log(resultado);
 ```
Neste exemplo, a mensagem "Parabéns, você concluiu a tarefa com sucesso!" é exibida no console do navegador.
-----

3. Exemplo Prático:

```javascript
let idade = prompt("Digite sua idade:");
console.log("Sua idade é:", idade);
 ```
Neste exemplo, usamos prompt() para solicitar ao usuário que digite sua idade. O valor digitado é armazenado na variável idade, que é então exibida no console usando console.log().

Esses são os conceitos básicos de entrada e saída de dados em JavaScript. Entender como receber e exibir informações é essencial para criar aplicativos interativos e úteis.
-----


- Use o conhecimento com prudência !!!!
- ***Este treinamento tem todo um intuinto educativo, afim de propagar conhecimento e apredizado***
-----

 <div align="center">
      <img src="https://user-images.githubusercontent.com/78884474/211343329-a8718daf-0953-4563-83f5-20901019202f.png" width="100px"  />
   </div>

</br>
</br>
</br>

<div align="center"> 
 	<a href="https://instagram.com/creative.agenciaofl" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
 <a href="https://discord.gg/pDbY76q8Qf" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a> 
  <a href = "mailto:igo.dev2023@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/igomarcos/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
 </div>

