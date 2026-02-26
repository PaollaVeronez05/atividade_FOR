

# 📘 Painel de Tabuadas Dinâmico – JavaScript

Projeto educacional desenvolvido para demonstrar, de forma prática e visual, a utilização de **laços de repetição aninhados (`for` dentro de `for`) em JavaScript**, combinados com HTML e CSS para organização em formato de cards.

O sistema gera automaticamente as tabuadas do 1 ao 10 com apenas um clique.

---

## 🎯 Objetivo

Este projeto tem como finalidade:

* Demonstrar o uso de **laço externo e laço interno**
* Trabalhar com **estrutura de repetição aninhada**
* Praticar **concatenação de strings**
* Aplicar **manipulação do DOM**
* Organizar conteúdo dinamicamente com **CSS**
* Desenvolver lógica estruturada

---

## 🧠 Conceito Principal: Laços Aninhados

O sistema utiliza dois laços `for`:

### ✔ Laço Externo

Responsável por definir qual tabuada será gerada (de 1 até 10).

```javascript
for (let base = 1; base <= 10; base++) {
```

---

### ✔ Laço Interno

Responsável por calcular as multiplicações de 1 até 10 para cada tabuada.

```javascript
for (let multiplicador = 1; multiplicador <= 10; multiplicador++) {
```

---

## 💻 Funcionamento do Sistema

1. O usuário clica no botão "Gerar Tabuadas"
2. O JavaScript executa a função
3. O laço externo define a tabuada atual
4. O laço interno calcula as multiplicações
5. Os resultados são armazenados em uma string
6. O conteúdo é exibido no painel usando `.innerHTML`

---

## 🔎 Estrutura do Projeto

```
📁 painel-tabuadas/
│
├── index.html   → Estrutura da página
├── style.css    → Estilização dos cards
└── script.js    → Lógica das tabuadas
```

---

## 🖥️ Estrutura HTML

O sistema contém:

* Um botão para gerar as tabuadas
* Uma `<div>` vazia onde os resultados são inseridos dinamicamente

Exemplo:

```html
<button onclick="gerarTabuadas()">Gerar Tabuadas</button>
<div id="painel"></div>
```

---

## 🧮 Exemplo de Resultado Gerado

Tabuada do 3:

```
3 x 1 = 3
3 x 2 = 6
3 x 3 = 9
...
3 x 10 = 30
```

Cada tabuada é exibida dentro de um **card visual**, alinhado lado a lado com as demais.

---

## 🎨 Estilização com CSS

As tabuadas não ficam uma abaixo da outra.

Cada uma é organizada dentro de um bloco visual (card), utilizando propriedades como:

* `display: flex`
* `flex-wrap`
* `gap`
* `padding`
* `border`
* `box-shadow`

Isso melhora a organização e a experiência visual do usuário.

---

## 🛠️ Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* Estrutura de repetição `for`
* Manipulação do DOM
* Concatenação de strings

---

## 📚 Conceitos Trabalhados

* Laço de repetição simples
* Laço de repetição aninhado
* Controle de fluxo
* Organização lógica em camadas
* Acúmulo de string com `+=`
* Uso de `.innerHTML`
* Separação entre estrutura, estilo e lógica


---


## 🧩 Lógica do Exercício

O laço de fora "manda" na tabuada atual.

O laço de dentro "preenche" os valores de 1 a 10 daquela tabuada.

Essa estrutura permite gerar 100 operações matemáticas automaticamente com poucas linhas de código.

---

## 👩‍💻 Autora

Paolla Paula Veronez

Estudante de desenvolvimento de sistemas
---


