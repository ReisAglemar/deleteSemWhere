# 🧪 Desafio de Fluxo Git/GitHub (Main Sagrada)

Este repositório não é sobre corrigir um bug simples.  

**O bug existe de propósito.**

O foco é avaliar o fluxo de trabalho com Git e GitHub em um cenário realista, simulando um ambiente profissional onde a integridade do código e o histórico são prioridades.

## 🎯 Objetivo

Simular um ambiente próximo do mundo real, onde:

- A branch main é sagrada: Ninguém trabalha diretamente nela.
- Acesso Controlado: Alterações só entram via Pull Request (PR).
- Histórico Limpo: Uso obrigatório de rebase para manter a linearidade.


## 🐞 O Bug (Contexto)

```js
    const nome = "Aglemar Reis";
    const idade = 34;
    console.log(`Olá ${idade}! Sua idade é ${nome}. :/`);

```
❌ Mas atenção: O desafio NÃO é o bug. O desafio é o processo.


## 📋 Regras do Jogo
1️⃣ Commit direto na main

❌ Bloqueado. Pode tentar quantas vezes quiser, as proteções do repositório não permitirão o push.

2️⃣ Merge direto / Fetch na main

❌ Bloqueado. Fluxos que tentarem burlar a revisão via merge manual serão rejeitados.

3️⃣ Clone obrigatório

Para resolver o problema, você deve utilizar o fluxo padrão:
Bash

git clone <url-do-repositorio>

Nada de download ZIP ou edições diretas na interface do GitHub.

4️⃣ A main não é tocada

❌ Trabalhos na main não serão aceitos. A main representa o ambiente de Produção. Produção não se mexe direto.

5️⃣ Nome da Branch

Sua branch de trabalho deve conter o seu nome. Use a criatividade, contanto que seja identificável. Exemplos:

    reisDev

    lucasMatadorDeBug

    ana-fix-logic

6️⃣ Pull Request obrigatório

Ao finalizar a correção:

    Abra um Pull Request.

    Utilize a estratégia de Rebase.

    Descreva brevemente o que foi feito.

## 🧠 Importante

Se você achou que era “só trocar a ordem das variáveis”, você entendeu o bug, **mas não entendeu o desafio.**

O foco aqui é processo e disciplina, não apenas sintaxe.

### 🔓 Repositório Público
- Qualquer pessoa pode tentar.

- Não há risco de quebrar a versão estável.

- O histórico de PRs servirá como vitrine do seu fluxo de trabalho.


**Boa sorte, jovem matador(a) de bugs! 🐛🔥**
