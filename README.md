# Java-SE-8-Programmer

*_O resumo do guia para a nossa certificação Oracle Certified Associate_*

## Certificação
- As certificações java são bastante reconhecidas no mercado, e a certificação buscada neste repositorio é a **Java SE 8 Programmer I (1Z0-808)**.

## Links relavantes
- Este conteudo tem como objetivo resumir o livro da certificação java, tendo em vista que foi publicado pela casa do codigo, deixarei os devidos links abaixo.
-  http://www.guj.com.br
-  http://www.twitter.com/casadocodigo
-  http://www.facebook.com/casadocodigo

## Assuntos

<details> 
  <summary>  Basico do java </summary>
  <br>
  
-  Defina o escopo de variáveis

 O escopo é o que determina em que ponto do código uma variavel pode ser usada.

  ### Variáveis Locais
  As variáveis locais, são as variaveis dentro de blocos de codigo _(Um bloco é um trecho de código entre chaves. Que pode ser um método ou um construtor)_, assim como dentro de construtores. <br>
  
 **_Regra basica: O ciclo de vida de uma variavel local vai do ponto onde ela foi declarada até o fim do bloco onde ela foi declarada._**

```
public void m1() { // abertura do método

int x = 10; // method local variable

} // Fechamento do método
```

Ou no corpo de um  `if`, de um  `for` etc.:

```
public void m1() { // abertura do método

  int x = 10; // variavel local do metodo

  if (x >= 10) { // if - abertura

    int y = 50; // variavel local do IF

    System.out.print(y);

  } // if - fechamento

} // Fechamento do método
```

 
 
 
   
- Defina a estrutura de uma classe Java 
- Crie aplicações Java executáveis com um método `main`, rode um programa Java na linha de comando 
- Importe outros pacotes Java e deixe-os acessíveis ao seu código 
   
</details>

<details> 
  <summary>Trabalhando com tipos de dados Java</summary>
  
 - Declare e inicialize variáveis 
  - Diferença entre variáveis de referências a objetos e tipos primitivos 
  - Leia ou escreva para campos de objetos 
  - Explique o ciclo de vida de um objeto (criação, "de referência" e garbage collection) 
  - Chame métodos em objetos 
  - Manipule dados usando a classe `StringBuilder` e seus métodos 
  - Crie e manipule Strings 
   
</details>

<details> 
  <summary>Usando operadores e construções de decisão</summary>
  
 - Use operadores Java 
  - Use parênteses para sobrescrever a precedência de operadores 
  - Teste a igualdade entre Strings e outros objetos usando `==` e `equals()` 
  - Utilize o `if` e `if/else` 
  - Utilize o `switch` 
   
</details>

<details> 
  <summary>Criando e usando Arrays</summary>
  
  - Declare, instancie, inicialize e use um array unidimensional 
  - Declare, instancie, inicialize e use um array multidimensional 
  - Declare e use uma `ArrayList` 
   
</details>

<details> 
  <summary>Usando laços de repetição</summary>
  
- Crie e use laços do tipo `while` 
  - Crie e use laços do tipo `for`, incluindo o `enhanced for` 
  - Crie e use laços do tipo `do/while` 
  - Compare os tipos de laços 
  - Use `break` e `continue` 
   
</details>

<details> 
  <summary>Trabalhando com Métodos e Encapsulamento</summary>
  
 - Crie métodos com argumentos e valores de retorno 
  - Aplique a palavra-chave `static` a métodos e campos 
  - Crie métodos sobrecarregados 
  - Diferencie o construtor padrão e construtores definidos pelo usuário 
  - Crie e sobrecarregue construtores 
  - Aplique modificadores de acesso 
  - Aplique princípios de encapsulamento a uma classe 
  - Determine o efeito que ocorre com referências a objetos e a tipos primitivos quando são passados a outros métodos e seus valores mudam 
   
</details>

<details> 
  <summary>Trabalhando com herança e polimorfismo</summary>
  
  - Implemente herança 
  - Desenvolva código que mostra o uso de polimorfismo 
  - Diferencie entre o tipo de uma referência e o tipo de um objeto 
  - Determine quando é necessário fazer casting 
  - Use `super` e `this` para acessar objetos e construtores 
  - Use classes abstratas e interfaces 
  
</details>

<details> 
  <summary>Lidando com exceções</summary>
  
  - Diferencie entre exceções do tipo `checked`, `runtime` e erros 
  - Descreva o que são exceções e para que são utilizadas em Java 
  - Crie um bloco `try-catch` e determine como exceções alteram o fluxo normal de um programa 
  - Invoque um método que joga uma exceção 
  - Reconheça classes de exceções comuns e suas categorias 
  
</details>

<details> 
  <summary>Java 8 - Java Basics</summary>
  
  - Rode um programa Java a partir da linha de comando 
  - Trabalhe com saída no console 
  - Compare e contraste as funcionalidades e componentes da plataforma Java, como: independência de plataforma, orientação a objeto, encapsulamento etc. 
  
</details>

<details> 
  <summary>Java 8 - Trabalhando com tipos de dados em Java</summary>
  
  - Desenvolva código que usa classes wrappers como `Boolean`, `Double` e `Integer` 
  
</details>

<details> 
  <summary>Java 8 - Trabalhando com algumas classes da Java API</summary>
  
  - Crie e manipule dados de calendários usando as classes `java.time.LocalDateTime`, `java.time.LocalDate`, `java.time.LocalTime`, `java.time.format.DateTimeFormatter`, `java.time.Period` 
  - Escreva uma expressão Lambda simples que consuma uma expressão Lambda `Predicate` 
  
</details>
