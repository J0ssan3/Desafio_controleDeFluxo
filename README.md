# Desafio Controle de Fluxo em Java
Este projeto foi desenvolvido como parte da **Trilha Java Básico** da [DIO - Digital Innovation One](https://www.dio.me/), no qual fui desafiada a aplicar conceitos de controle de fluxo, exceções personalizadas e entrada de dados via terminal.

---

## 📝Descrição do Desafio

O sistema deve receber dois números inteiros como entrada. Com base nesses dois valores:

- Se o **primeiro número for menor que o segundo**, o sistema irá imprimir a quantidade de interações (diferença entre eles) com mensagens como:
```
Imprimindo o número 1
Imprimindo o número 2
```
- Se o **primeiro número for maior que o segundo**, o sistema deve lançar uma **exceção personalizada** chamada `ParametrosInvalidosException`, com a mensagem:

O segundo parâmetro deve ser maior que o primeiro

---

## 📌 Exemplo de Execução

```
Digite o primeiro parâmetro
5
Digite o segundo parâmetro
9

Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
```
---

## 💻 Tecnologias Utilizadas

- Java 8 ou superior
- Scanner (`java.util.Scanner`)
- Estrutura de repetição `for`
- Exceções personalizadas (`extends Exception`)
- Console (entrada e saída via terminal)
---

## 🗂 Estrutura do Projeto

DesafioControleFluxo/
├── Contador.java
└── ParametrosInvalidosException.java

## ⚙️ Como Executar

1. Clone este repositório:

```
git clone https://github.com/seu-usuario/desafio-controle-fluxo-java.git

cd desafio-controle-fluxo-java

git add README.md
git commit -m "Adiciona README com explicações do desafio"

git branch -M main
git push -u origin main

```

## 📚 Aprendizados

Neste desafio, apliquei os seguintes conhecimentos:

- Leitura de dados via terminal com `Scanner`
- Validação de condições com `if`
- Uso da estrutura `for` para iteração controlada
- Criação e uso de exceções personalizadas
- Tratamento de exceções com `try/catch`
- Impressão de mensagens dinâmicas no console
---

## ✍️ Autora

Desenvolvido por Jossane Cardoso
Graduanda em Análise e Desenvolvimento de Sistemas
👩‍💻 GitHub: @J0ssan3
📘 DIO: Aluna da Trilha Java 
