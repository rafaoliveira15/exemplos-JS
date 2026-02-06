# 📘 Exemplos Básicos de JavaScript

Este repositório contém **exemplos simples de JavaScript integrado ao HTML**, com o objetivo de ajudar iniciantes a entenderem conceitos fundamentais da linguagem, como saída de dados, entrada do usuário, variáveis, concatenação e operações matemáticas.

Cada arquivo HTML pode ser aberto diretamente no navegador.

---

## 📂 Estrutura do Repositório

```
ex1.html
ex2.html
ex3.html
ex4.html
ex5.html
ex6.html
README.md
```

---

## 🧪 Exemplo 1 — Olá Mundo (`ex1.html`)

### 🔎 O que faz?

Exibe a mensagem **"Olá, mundo!"** na tela do navegador.

### 📌 Conceitos abordados

* Uso da tag `<script>`
* Saída de dados com `document.write()`
* Primeiro contato com JavaScript

### 💡 Observação

Esse é o exemplo mais básico possível, tradicionalmente usado para iniciar o aprendizado em qualquer linguagem de programação.

---

## 🧪 Exemplo 2 — Boas-vindas com Nome (`ex2.html`)

### 🔎 O que faz?

Solicita o nome do usuário através de uma janela de diálogo e exibe uma mensagem de boas-vindas personalizada.

### 📌 Conceitos abordados

* Entrada de dados com `window.prompt()`
* Uso de variáveis (`var`)
* Concatenação de texto
* Saída de dados com `document.write()`

### 💡 Observação

O nome digitado pelo usuário é armazenado em uma variável e utilizado para personalizar a mensagem exibida.

---

## 🧪 Exemplo 3 — Concatenação com Formulário (`ex3.html`)

### 🔎 O que faz?

Permite que o usuário digite **nome** e **sobrenome** em um formulário. Ao clicar no botão, os dois valores são concatenados e exibidos em um alerta.

### 📌 Conceitos abordados

* Formulários HTML
* Captura de valores de campos de formulário
* Funções em JavaScript
* Concatenação de strings
* Uso de `window.alert()`

### 💡 Observação

Este exemplo mostra a interação entre **HTML e JavaScript**, utilizando eventos (clique no botão) para executar uma função.

---

## 🧪 Exemplo 4 — Soma de Dois Números (`ex4.html`)

### 🔎 O que faz?

Solicita dois números ao usuário, realiza a soma e exibe o resultado na tela.

### 📌 Conceitos abordados

* Entrada de dados com `window.prompt()`
* Conversão de texto para número com `parseInt()`
* Operações matemáticas
* Uso de variáveis

### 💡 Observação

A conversão com `parseInt()` é necessária porque o `prompt` retorna valores no formato de texto.

---

## 🧪 Exemplo 5 — Máquina de Frutas (Suco Personalizado) (`ex5.html`)

### 🔎 O que faz?

Simula uma **máquina de sucos interativa**, onde o usuário pode escolher uma ou mais frutas, o tipo de líquido (água ou leite) e se deseja açúcar. Ao final, uma mensagem personalizada mostra como ficou o suco.

### 📌 Conceitos abordados

* `<select multiple>` para seleção múltipla
* Botões de rádio (`radio`) e caixas de seleção (`checkbox`)
* Manipulação do DOM com `getElementById` e `querySelector`
* Uso de arrays (`Array.from`, `map`, `join`)
* Funções em JavaScript
* Validação de entrada do usuário
* Uso de `alert()`

### 💡 Observação

Este exemplo é mais avançado e demonstra **interação completa com o usuário**, lógica condicional e manipulação de vários tipos de campos HTML ao mesmo tempo.

---

## 🧪 Exemplo 6 — Calculadora de Intervalo entre Datas (ex6.html)

### 🔎 O que faz?

Calcula o intervalo entre duas datas informadas pelo usuário, exibindo a diferença em dias, meses (aproximado) e anos (aproximado).

### 📌 Conceitos abordados

Campos de data (input type="date")

Validação de formulário

Manipulação do DOM (getElementById, innerHTML)

Uso do objeto Date em JavaScript

Cálculo de diferença entre datas em milissegundos

Funções e eventos de clique

Template literals (`texto ${variavel}`)

### 💡 Observação

Os cálculos de meses e anos são aproximados (30 dias por mês e 12 meses por ano), adequados para fins didáticos. O exemplo também inclui estilização com CSS interno e boas práticas de organização do código.

---

## 🚀 Objetivo do Repositório

Este material é ideal para:

* Estudantes iniciantes em JavaScript
* Aulas introdutórias de programação web
* Revisão de conceitos básicos

---

## 👩‍💻 Autora

**Rafaela Oliveira** 💙
Estudante de Desenvolvimento de Sistemas
