![Status ](https://img.shields.io/badge/Status-Em%20desenvolvimento-brightgreen)

---

# 🎰 Sorteador de Números Aleatórios

Uma aplicação simples, dinâmica e eficiente para **sortear números aleatórios sem repetições**, dentro de um intervalo personalizado. Ideal para **sorteios, rifas, jogos, atividades educacionais**, entre outras situações que exigem imparcialidade e aleatoriedade.

---

## ✨ Funcionalidades

🔢 **Sorteio Personalizado**
Escolha quantos números deseja sortear e defina o intervalo (de X até Y). O sistema garante que não haverá números repetidos.

⚠️ **Validação Inteligente**
Evita erros comuns, como:

* Intervalo inválido (ex: número inicial maior que o final).
* Quantidade maior que o total de números possíveis.

♻️ **Reinício Instantâneo**
Com um clique, limpe os campos, zere os resultados e prepare-se para um novo sorteio.

🧠 **Algoritmo Eficiente**
Os números são gerados aleatoriamente e verificados para garantir exclusividade, mesmo em sorteios com grandes quantidades.

🧼 **Interface Limpa e Didática**
Exibição clara dos números sorteados e mensagens informativas durante o processo.

---

## 🧾 Descrição do Processo

1. ✍️ O usuário informa:

   * A **quantidade** de números desejados.
   * O número **mínimo** (início do intervalo).
   * O número **máximo** (fim do intervalo).

2. 🧪 O sistema valida os dados para evitar inconsistências.

3. 🔄 Os números são sorteados **aleatoriamente e sem repetição**.

4. 🎉 O resultado é exibido na tela, com visual amigável.

5. 🔁 O botão de reinício é ativado para permitir novos sorteios rapidamente.

---

## 🛡️ Regras de Validação

❌ O campo "**Do número**" deve ser **menor** que o campo "**Até o número**".

❌ A **quantidade** deve ser **menor ou igual ao total de números disponíveis** no intervalo escolhido.

🔄 Caso um número sorteado já tenha saído, o sistema tenta novamente até encontrar um número inédito.

---

## 📌 Exemplo de Uso

Imagine que você quer sortear **5 números entre 1 e 50**:

```plaintext
Quantidade: 5
De: 1
Até: 50

✅ Números sorteados: 8, 17, 34, 22, 41
```

Com um clique em **"Reiniciar"**, o sistema volta ao estado inicial, pronto para um novo sorteio.

---

## 🛠️ Possíveis Melhorias Futuras

🌈 Exibição animada dos números sorteados

📊 Histórico dos sorteios anteriores

📁 Exportação de resultados (TXT, CSV, PDF)

📱 Versão mobile com interface adaptativa

🎨 Personalização de tema e estilo visual

---

## 📃 Licença

Este projeto é de **código aberto** e pode ser utilizado para fins **educacionais, pessoais ou não comerciais**.

---

