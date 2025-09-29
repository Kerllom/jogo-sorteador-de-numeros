![Status ](https://img.shields.io/badge/Status-Em%20desenvolvimento-brightgreen)


---

# 🎲✨ Jogo do Número Secreto

Um jogo divertido em **JavaScript**, onde o desafio é adivinhar um número secreto entre **1 e 50**.
Receba dicas, conte suas tentativas e reinicie quando vencer.

---

## 📌 Funcionalidades

✅ Sorteia um número entre **1 e 50**
✅ Garante que o mesmo número não se repita até todos terem sido sorteados
✅ Conta e exibe o número de tentativas
✅ Dá dicas: “maior” ou “menor”
✅ Feedback em **voz** usando a API **ResponsiveVoice**
✅ Botão para reiniciar o jogo

---

## 🛠️ Estrutura do Código

### 🔹 Variáveis principais

```js
let listaDeNumerosSorteados = []; // Guarda os números já usados
let numeroLimite = 50;           // Limite do sorteio
let numeroSecreto = gerarNumeroAleatorio(); 
let tentativas = 1;              // Contador de tentativas
```

---

### 🔹 Principais Funções

📢 **exibirTextoNaTela(tag, texto)**
Exibe mensagens em elementos HTML e as lê em voz alta.

🎯 **verificarChute()**

* Confere se o número digitado é o secreto.
* Mostra mensagens de acerto/erro.
* Dá dicas se o número secreto é maior ou menor.
* Incrementa tentativas.

🎲 **gerarNumeroAleatorio()**

* Sorteia um número entre `1` e `numeroLimite`.
* Garante que não haja repetições.
* Reinicia a lista quando todos já foram sorteados.

🧹 **limparCampo()**
Limpa o campo de input.

🔄 **reiniciarJogo()**
Reseta as variáveis, sorteia um novo número e reexibe a mensagem inicial.

---

## 🎮 Fluxo do Jogo

1️⃣ Página inicial mostra:

* **Título:** “Jogo do número secreto”
* **Mensagem:** “Escolha um número entre 1 e 50”

2️⃣ Jogador digita um número no input.

3️⃣ O sistema responde:

* 🔼 “O número secreto é maior”
* 🔽 “O número secreto é menor”

4️⃣ Ao acertar:

* 🎉 “Acertou!”
* Mostra a quantidade de tentativas
* Botão de reinício é habilitado

---

## 🧰 Tecnologias

* **JavaScript (ES6+)** → lógica do jogo
* **HTML/CSS** → interface
* **ResponsiveVoice** → narração das mensagens

---

## ▶️ Como Executar

1. Crie um arquivo **index.html** e adicione:

   * Um campo `<input>` para o chute
   * Um botão “Chutar” (chama `verificarChute()`)
   * Um botão “Reiniciar” (chama `reiniciarJogo()`, inicialmente `disabled`)
2. Inclua o script JavaScript.
3. Abra o arquivo no navegador.

---

## 🌟 Exemplo Visual de Estrutura HTML

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Jogo do Número Secreto</title>
  <script src="script.js" defer></script>
</head>
<body>
  <h1>Jogo do número secreto</h1>
  <p>Escolha um número entre 1 e 50</p>
  <input type="number" min="1" max="50">
  <button onclick="verificarChute()">Chutar</button>
  <button id="reiniciar" onclick="reiniciarJogo()" disabled>Reiniciar</button>
</body>
</html>
```

---

## 🚀 Demonstração

🔢 Tente adivinhar o número secreto!
Cada erro dá uma dica até você acertar.
Quando vencer, reinicie e jogue novamente! 🎉

---


