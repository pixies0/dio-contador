# Projeto Contador

Este projeto Java simples demonstra o uso de controle de fluxo (for loop) e tratamento de exceções customizadas para um cenário de contagem de números.

# Estrutura do Projeto

A estrutura de diretórios do projeto é a seguinte:
```
Contador
├─ README.md
├─ bin/
│  └─ Desafio/
├─ lib/ 
└─ src/
   ├─ App.java
   └─ Desafio/
      ├─ Contador.java <----------- (EXECUTE ESSE PROGRAMA)
      └─ ParametrosInvalidosException.java
```

# Uso

Ao executar o programa, você será solicitado a inserir dois parâmetros (números inteiros):

    "Digite o primeiro parâmetro:"

    "Digite o segundo parâmetro:"

## Comportamento:

    Contagem Normal: Se o segundo parâmetro for maior que o primeiro parâmetro, o programa realizará uma contagem incremental, imprimindo os números de 1 até a diferença entre o segundo e o primeiro parâmetro.
    Exemplo:

    Digite o primeiro parâmetro:
    12
    Digite o segundo parâmetro:
    30
    Imprimindo o número 1
    Imprimindo o número 2
    ...
    Imprimindo o número 18

    Tratamento de Exceção: Se o primeiro parâmetro for maior que o segundo parâmetro, o programa lançará uma exceção customizada ParametrosInvalidosException e exibirá a mensagem de erro:

    O segundo parâmetro deve ser maior que o primeiro.

# Classes Principais

    Contador.java: Contém a lógica principal do programa, incluindo a leitura de entrada do usuário, a chamada do método de contagem e o tratamento da exceção.

    ParametrosInvalidosException.java: Uma exceção customizada que é lançada quando os parâmetros de entrada não atendem à condição de que o segundo parâmetro deve ser maior que o primeiro.