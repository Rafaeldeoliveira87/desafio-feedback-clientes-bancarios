# Passo 2 — Contexto e Restrições

## 📌 Objetivo da Etapa

Nesta etapa, foram adicionadas informações de contexto e regras para orientar a inteligência artificial durante a análise dos feedbacks.

O objetivo é fornecer informações suficientes para que a IA compreenda o cenário, os dados disponíveis, os critérios de análise e os cuidados necessários ao lidar com informações relacionadas a clientes bancários.

---

## 🏦 Contexto

Estou trabalhando com feedbacks de clientes bancários relacionados a produtos e serviços financeiros, incluindo aplicativo, Pix, cartão de crédito, transferências e canais de atendimento.

---

## 📊 Dados Disponíveis

A base contém informações como:

* Data do feedback;
* Canal de atendimento;
* Produto ou serviço relacionado;
* Texto do comentário;
* Nota de satisfação atribuída pelo cliente, quando disponível.

---

## 🔎 Critérios de Análise

A IA deve classificar os feedbacks considerando:

* Tema principal;
* Produto ou serviço relacionado;
* Sentimento: positivo, negativo ou neutro;
* Tipo de experiência: elogio, reclamação, sugestão ou dúvida;
* Nível de urgência;
* Possível impacto na experiência do cliente;
* Frequência dos temas, quando os dados disponíveis permitirem essa análise.

A IA também deve identificar padrões e problemas recorrentes, além de destacar os principais pontos positivos e negativos encontrados nos feedbacks.

---

## 🔐 Cuidados e Restrições

A IA deve seguir as seguintes regras:

1. Utilizar exclusivamente os dados fornecidos na base.

2. Não inventar números, estatísticas, causas ou conclusões que não possam ser sustentadas pelos dados.

3. Não expor dados pessoais ou informações bancárias sensíveis dos clientes.

4. Caso existam informações que possam identificar um cliente, elas devem ser anonimizadas e não devem aparecer na análise final.

5. Não realizar inferências sobre características pessoais dos clientes que não estejam explicitamente presentes nos dados.

6. Não ignorar feedbacks negativos ou positivos.

7. Diferenciar claramente fatos observados nos dados de interpretações ou hipóteses.

8. Caso os dados sejam insuficientes para sustentar uma conclusão, informar explicitamente essa limitação.

9. Ao apresentar exemplos de comentários, remover ou ocultar qualquer informação pessoal ou sensível.

10. Utilizar linguagem simples, objetiva e voltada para a tomada de decisão.

---

## 🎯 Resultado Esperado

Com a inclusão do contexto e das restrições, espera-se que a inteligência artificial produza análises mais confiáveis, organizadas e adequadas ao cenário bancário.

As restrições também têm como objetivo reduzir o risco de geração de informações sem evidências e evitar a exposição indevida de informações pessoais ou sensíveis.
