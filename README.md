# Desafio Controle de Fluxo - DIO

Projeto desenvolvido como parte do desafio **Controle de Fluxo** da

O objetivo deste projeto é praticar conceitos fundamentais de Java,
como estruturas condicionais, estruturas de repetição e tratamento
de exceções.

## Descrição

O programa recebe dois números inteiros através do terminal.

A partir desses valores, é calculada a diferença entre o segundo e o
primeiro parâmetro.

O programa utiliza um laço `for` para imprimir a quantidade de
iterações correspondente à diferença entre os parâmetros.

### Exemplo

Entrada:

```text
12
30
```

Resultado:

```text
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
...
Imprimindo o número 18
```

Caso o primeiro parâmetro seja maior que o segundo, será lançada uma
exceção personalizada:

```text
O segundo parâmetro deve ser maior que o primeiro
```

## Estrutura do projeto

```text
src/
├── Contador.java
└── ParametrosInvalidosException.java
```

## Conceitos utilizados

`Scanner` para entrada de dados, estruturas condicionais com `if`,
laço de repetição `for`, tratamento de exceções com `try/catch`,
criação de exceções personalizadas e métodos em Java.

## Tecnologias

Java, Git e GitHub.

## Executando o projeto

Compile:

```bash
javac -d out src/*.java
```

Execute:

```bash
java -cp out Contador
```

## Autor

Desenvolvido por **HMaxZcar** como parte dos desafios da DIO.

[GitHub](https://github.com/HMaxZcar)