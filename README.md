# 🏦 Desafio Criativo — Extraindo Insights do Feedback de Clientes Bancários

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio criativo de engenharia de prompts, com o objetivo de construir, de forma estruturada, um comando capaz de orientar uma inteligência artificial na análise de feedbacks de clientes bancários.

A proposta do desafio é demonstrar como um prompt pode ser aprimorado a partir da definição clara de uma intenção, da inclusão de contexto, do estabelecimento de critérios de análise e da definição de cuidados e restrições relacionados ao tratamento de dados.

O projeto utiliza como cenário a análise de feedbacks de clientes sobre produtos e serviços bancários, buscando transformar comentários em informações úteis para apoiar decisões relacionadas à experiência do cliente.

---

## 🎯 Objetivo

O objetivo principal é desenvolver um prompt estruturado capaz de orientar uma IA na análise de feedbacks de clientes bancários.

A análise deve permitir identificar:

* Temas recorrentes;
* Reclamações;
* Elogios;
* Sugestões;
* Sentimentos dos clientes;
* Problemas recorrentes;
* Oportunidades de melhoria;
* Possíveis prioridades de ação.

O resultado esperado deve ser útil para equipes responsáveis pela experiência do cliente e pela melhoria de produtos e serviços bancários.

---

## 🧩 Construção do Prompt

A construção do prompt foi realizada de forma incremental, seguindo as etapas propostas pelo desafio.

### Etapa 1 — Definição da intenção

Nesta etapa foi definido:

* O tipo de feedback analisado;
* O objetivo da análise;
* O público que utilizará os resultados;
* A finalidade da análise;
* O formato esperado da entrega;
* Os critérios utilizados para avaliar a qualidade do resultado.

📄 [Ver Passo 1 — Definição da Intenção](./etapas/passo-1-intencao.md)

---

### Etapa 2 — Contexto e Restrições

Nesta etapa foram adicionadas informações para orientar a IA sobre:

* O contexto dos feedbacks;
* Os dados disponíveis;
* Os critérios de classificação;
* Os cuidados com dados pessoais e sensíveis;
* As limitações da análise;
* As informações que não devem ser inventadas.

📄 [Ver Passo 2 — Contexto e Restrições](./etapas/passo-2-contexto-restricoes.md)

---

## 🔐 Cuidados com Dados Sensíveis

Por se tratar de um cenário relacionado ao setor bancário, é importante considerar a proteção das informações dos clientes.

O prompt desenvolvido estabelece que a IA deve:

* Utilizar somente os dados fornecidos;
* Não inventar informações;
* Não expor dados pessoais;
* Não expor informações bancárias sensíveis;
* Anonimizar informações que possam identificar clientes;
* Não realizar inferências indevidas sobre características pessoais;
* Informar quando os dados disponíveis forem insuficientes;
* Diferenciar fatos observados de interpretações e hipóteses.

Esses cuidados têm como objetivo reduzir riscos relacionados à privacidade e evitar conclusões sem evidências.

---

## 🚀 Prompt Final

Após a construção das etapas iniciais, as informações foram consolidadas em um único prompt estruturado.

📄 [Ver Prompt Final](./prompt-final.md)

---

## 📂 Estrutura do Projeto

```text
desafio-feedback-clientes-bancarios/
│
├── README.md
│
├── etapas/
│   ├── passo-1-intencao.md
│   └── passo-2-contexto-restricoes.md
│
└── prompt-final.md
```

---

## 💡 Principais Aprendizados

Durante o desenvolvimento do desafio, foi possível compreender a importância de fornecer contexto e instruções claras para obter respostas mais úteis de uma inteligência artificial.

Entre os principais aprendizados estão:

* Um bom prompt deve possuir uma intenção clara;
* O contexto influencia diretamente a qualidade da resposta;
* Critérios de análise ajudam a orientar o comportamento da IA;
* Restrições reduzem o risco de respostas inadequadas;
* A IA não deve inventar informações que não estejam presentes nos dados;
* Dados sensíveis devem ser tratados com cuidado;
* É importante informar as limitações dos dados disponíveis;
* A estrutura da resposta deve ser definida de acordo com o objetivo da análise.

---

## 📌 Conclusão

O projeto demonstra um processo estruturado de construção de prompts, partindo de uma intenção inicial e adicionando contexto, critérios e restrições para orientar uma inteligência artificial na análise de feedbacks de clientes bancários.

A abordagem utilizada busca transformar dados textuais em insights organizados e úteis para a tomada de decisão, mantendo cuidados relacionados à privacidade, segurança e confiabilidade das informações.

---

## 👨‍💻 Autor

Projeto desenvolvido como atividade de aprendizagem sobre engenharia de prompts, análise de dados e utilização responsável de inteligência artificial.
