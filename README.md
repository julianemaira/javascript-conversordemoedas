# 💱 Conversor de Moedas

Este é um projeto simples de conversor de moedas feito com **HTML**, **CSS** e **JavaScript**. A aplicação permite converter valores de **Real (BRL)** para **Dólar (USD)** ou **Euro (EUR)** com base em valores fixos definidos no código.

---


## 🚀 Funcionalidades

- Conversão de valores de Real (BRL) para Dólar (USD) ou Euro (EUR)
- Atualização da bandeira e nome da moeda ao trocar a opção no seletor
- Interface simples e responsiva
- Utilização da API `Intl.NumberFormat` para formatação dos valores conforme a moeda

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS
- JavaScript 

---

## 🧠 Lógica do Código

### 1. Seletores

```javascript
const convertButton = document.querySelector(".convert-button")
const currencySelect = document.querySelector(".currency-select")
```
Seleciona os elementos do HTML que o JavaScript irá manipular.

### 2. Função `convertValues`

Essa função é chamada quando o botão "Converter" é clicado. Ela:

- Lê o valor digitado em Real
- Converte para Dólar ou Euro, dependendo da opção escolhida
- Atualiza os valores convertidos no HTML

### 3. Função `changeCurrency`

Atualiza o nome e imagem da moeda quando o usuário troca a opção no seletor.

```javascript
currencySelect.addEventListener('change', changeCurrency)
convertButton.addEventListener("click",convertValues)
```

---

## ⚙️ Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/conversor-de-moedas.git
   ```
2. Abra o arquivo `index.html` em seu navegador.
