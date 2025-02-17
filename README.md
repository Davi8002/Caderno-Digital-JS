
Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico

### Declaração de Variaveis

var: Permite redeclarar a variável e alterar seu valor a qualquer momento.

let: Permite declarar a variável apenas uma vez, mas você pode modificar seu valor depois.

const: Não permite redeclarar a variável nem mudar seu valor após a declaração.

### Tipos de Variaveis


~~~javascript
// "String" e usado para declarar variaveis como Textos 
let string = "caractere"
~~~


~~~javascript
// Number: Number e usado para declarar variaveis como Numeros 
let number = 10
~~~


~~~javascript
// Boolean: Boolean e usado para declarar variaveis como False Ou True
let boolean = false
~~~


### Operadores Logicos 

**== // Compara se certos valores são iguais porem não compara os seus tipos.**


~~~javascript
let comparar = "1" == 1 
// Comparar vai ter o valor boolean de true


let comparar = 1 == 1 
// Comparar vai ter o valor boolean de true
~~~


**=== // Compara se certos valores são iguais em valor e tipo.**


~~~javascript
let comparar = "1" === 1 
// Comparar vai ter o valor boolean de false


let comparar = 1 === 1 //
// Comparar vai ter o valor boolean de true
~~~


**+ // Soma dois valores ou mais**

~~~javascript
let teste1 = "Batata" 

let teste2 = "Frita"  
    
let teste3 = teste1 + teste2 

// teste3 vai ser igual a BatataFrita

~~~


~~~javascript                    
let teste1 = 1 

let teste2 = 2 
     
let teste3 = teste1 + teste2 
     
// teste3 vai ser igual 3 ja que ele e a soma dos outros dois valores 
~~~


**> ou < // Compara 2 valores**


~~~javascript     
let teste = 10 >= 1

// Teste vai ser igual a true ja que 10 e maior ou igual a 1



let teste = 10 <= 1

// Teste vai ser igual a false ja que 1 não e maior ou igual a 10
~~~


**- // Subtrai valores**


~~~javascript     
let teste = 10 - 1 

// Teste vai ser igual a 9
~~~


**.*. // Mulplica valores**


~~~javascript     
let teste = 5 * 5 

//teste vai ser 25
~~~


**/  //Divide valores**


~~~javascript     
let teste = 10 / 2

//Teste vai ser 5 
~~~



### IF // ELSE // ELSE IF

~~~javascript

// O If usa essa estrutura:
If(Condição)
 {Ação}

// O if coloca uma condição para algo acontecer por exemplo:

if(2 > 1)
 {console.log("heh")}

// Nesse comando o if usa o operador logico de maior que e percebe que 2 e maior que 1 e por isso executa o comando 
~~~

~~~javascript
// O Else serve para executar algo caso a condição do if não seja atendida

if(1 > 2)
 {console.log("heh")} else{console.log("hehehehe")}

~~~

~~~javascript
// O Else If serve para executar algo caso a condição do if não seja atendida e a nova condição do Else if seja atendida 

if(1 > 2)
 {console.log("heh")
} else if(1 == 1){console.log("hehehehe")}

~~~

~~~javascript
// Para transformar valores em numeros pode-se usar o parseInt()

let numero1 = "1";
let numero2 = 1;

let calculo1 = numero1 + numero2

//Nesse caso o calculo1 vai ser igual a 11 porquê quando tem um calculo entre strings e numbers, os numbers se
//transformam em string então para evitar isso e nescessário que os dois valores sejam numbers e para isso ou
//você pode mudar o valor da variavel quando ela foi declarada ou usar parseInt() para transformar ela em number.

let numero1 = "1";
let numero2 = 1;
parseInt(numero1)

let calculo1 = numero1 + numero2

//Agora calculo 1 vai ser igual a 2 ja que numero1 virou um number


~~~



### Switch Case

~~~javascript
// O Switch Case e um jeito mais otimizado de  escrever um código que precise de muitos else If

let fruta = prompt("Qual Fruta Você Deseja?")


switch(fruta) {
   case "Maçã":
     console.log("Não Temos essa fruta");
       break;
   case "Banana":
     console.log("O cacho custa 10R$")
       break;
   case "Kiwi":
     console.log("Custa 14R$ o Kg")
       break;
     default:
}

//Nesse caso ele vai analisar qual fruta o usuário colocou no prompt e mandar uma mensagem dependendo de qual fruta ele colocou 
~~~

### Console.log e Alert

~~~javascript
//O console.log imprime uma mensagem no console e alert mostra uma mensagem em um bloco na tela mas basicamente funciona
//da mesma forma que o console.log

let teste = "Hello World"

console.log(teste)
alert(teste)

//O console e o alert vão mostrar Hello World
~~~

~~~javascript

let nome = prompt("Qual e seu nome?")

//Prompt mostra na tela um bloco para o usuario colocar um texto

console.log(teste + " " + nome)
alert(teste + " " + nome)

console.log(`Hello World ${nome}`);
alert(`Hello World ${nome}`);

//Nesses 4 casos vai ser mostrado Hello World nome respondido

//(`texto ${variavel}`); esse comando e usado para facilitar imprimir variaveis e textos juntos.
~~~

### Array

~~~javascript
//Array são variaveis que armazenam varios valores por exemplo:
const hqs = ["Superman", "Batman", "Flash", "Thor"];

//Elas são declaradas da seguinte forma
//var/Ou/let/Ou/const nomeDaVariavel = ["valor 1", "valor", "valor3"]

~~~


~~~javascript
// o comando nomeDaArray.includes(valorTestado) serve para verificar
// se um um valor especifico está incluido em uma array

const hqs = ["Superman", "Batman", "Flash", "Thor"];
//INDEX          0          1         2        3
alert(hqs.includes("Flash"))

//Nesse caso o alert vai mostrar um valor true ja que flash esta na array hqs
~~~


~~~javascript
const hqs = ["Superman", "Batman", "Flash", "Thor"];
alert(hqs.indexOf("Flash");
//Vai alertar o valor de 2 ja que seria o index de "flash"
~~~


~~~javascript
const hqs = ["Superman", "Batman", "Flash", "Thor"];
console.log(hqs.pop());
//Vai remover o valor "Thor" da array hqs ja que ele e o ultimo valor da array
//também é possivel especificar o valor a ser removido o colocando no pop("valor")
console.log(hqs.push("Hehe"));
//Vai adicionar o valor "Hehe" na array Hq
~~~


~~~javascript
const hqs = ["Superman", "Batman", "Flash", "Thor"];
console.log(hqs.sort())
//Vai colocar em ordem alfabetica a array hqs
console.log(hqs.length)
//Vai contar os valores das hqs e mostrar no console.
~~~

~~~javascript
const hqs = ["Superman", "Batman"];
const hqs2 = ["Flash", "Thor"];
const hqs3 = hqs.concat(hqs2)
//o valor de hqs3 vai ser a junção de hqs1 e hqs2 ja que o comando concat soma 2 arrays
~~~

### Função

~~~javascript
//Para se declarar uma função e usado o seguinte comando
function nomeDaFuncao(valoresUsados) {
  return valores_a_serem_retornados
}
//Por exemplo para fazer um função de soma são usados os seguintes comandos
const num1 = parseFloat(prompt("Digite o Numero 1"));
const num2 = parseFloat(prompt("Digite o Numero 2"));

function soma(num1, num2) {
  return num1 + num2;
}

console.log(soma(num1, num2));
//Nesse caso primeiro o usuario diria o 1 e 2 valor e depois a função vai somar os dois e mostrar o valor no console
~~~

~~~javascript
//Tambem e possivel criar uma calculadora simples que funciona com 2 numeros usando funções
const num1 = parseFloat(prompt("Digite o Numero 1"));
const calculo = prompt("Digite o Operador");
const num2 = parseFloat(prompt("Digite o Numero 2"));

function soma(num1, num2) {
  return num1 + num2;
}

function subtr(num1, num2) {
  return num1 - num2;
}

function multi(num1, num2) {
  return num1 * num2;
}

function divi(num1, num2) {
  return num1 / num2;
}

if (calculo == "+") {
  console.log(soma(num1, num2));
} else if (calculo == "-") {
  console.log(subtr(num1, num2));
} else if (calculo == "*") {
  console.log(multi(num1, num2));
} else if (calculo == "/") {
  console.log(divi(num1, num2));
}
//Nesse codigo ele analisa os valores ditos pelo usuario e dependendo muda o operador logico 
~~~

~~~javascript
//Essa função vai inverter uma pavra dividindo ela depois a revertendo e depois a juntando novamente.
let str = prompt("Qual palavra você quer inverter");

function inverterString(str) {
  return str.split("").reverse().join("");
}
console.log(inverterString(str));
~~~

## Atividades Desenvolvidas 

Vídeo Sobre Variáveis https://drive.google.com/file/d/1E96mEjGoIMgXJLhCbbwK_3HNau0fomNO/view?usp=drive_link

Atividades no Codepen
https://codepen.io/collection/ZMdeBV



