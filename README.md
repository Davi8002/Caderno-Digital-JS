https://codepen.io/collection/ZMdeBV Caderno virtual - Lógica da Programação e Algoritmos
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


**, * // Mulplica valores**


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




~~~

## Atividades desenvolvidas

Vídeo Sobre Variáveis https://drive.google.com/file/d/1E96mEjGoIMgXJLhCbbwK_3HNau0fomNO/view?usp=drive_link

Atividades no Codepen
https://codepen.io/collection/ZMdeBV



