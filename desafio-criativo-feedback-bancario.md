# 🎯 Desafio Criativo: Extraindo Insights do Feedback de Clientes Bancários

Neste desafio, construí um prompt em três etapas para orientar uma IA a analisar feedbacks de clientes bancários, com contexto, critérios de análise e cuidados com dados sensíveis.

---

## 🧱 Passo 1: Defina a intenção

Quero que a IA analise comentários de clientes sobre o Internet Banking e o aplicativo de um banco para identificar os problemas mais citados, os pontos elogiados e as oportunidades de melhoria.

O resultado será usado pela equipe de experiência do cliente e pelo time de produtos digitais para apoiar a priorização de correções e melhorias nos canais digitais.

A entrega deve conter um resumo executivo, uma tabela com os principais temas, exemplos de comentários que sustentem cada tema e recomendações práticas.

O resultado será considerado bom se for claro, bem organizado, baseado somente nos comentários fornecidos e útil para decidir o que resolver primeiro.

---

## 🧱 Passo 2: Adicione contexto e restrições

**Contexto:** Estou trabalhando com feedbacks de clientes bancários relacionados ao aplicativo, ao Pix, ao cartão de crédito e ao atendimento por chat.

**Dados disponíveis:** A base contém data do comentário, canal de atendimento, texto do feedback, produto citado e nota de satisfação de 1 a 5.

**Critérios de análise:** A IA deve classificar os feedbacks por tema, sentimento (positivo, neutro ou negativo), urgência (baixa, média ou alta) e produto citado.

**Cuidados e restrições:**

- Use apenas os dados fornecidos.
- Não invente números, causas ou conclusões.
- Não exponha dados pessoais ou sensíveis (nome, CPF, número de conta ou cartão, telefone, e-mail).
- Não ignore os comentários negativos.
- Se houver informação insuficiente, indique a limitação.
- Use linguagem simples, direta e voltada para a tomada de decisão.

---

## 🧱 Passo 3: Prompt final

```text
Atue como analista de dados e de experiência do cliente em um banco.

Sua tarefa é analisar feedbacks de clientes sobre o aplicativo bancário, o Pix, o cartão de crédito e o atendimento por chat para identificar temas recorrentes, o sentimento dos clientes e oportunidades de melhoria.

Contexto: A análise será usada pela equipe de experiência do cliente e pelo time de produtos digitais para priorizar melhorias nos canais digitais e reduzir atritos no atendimento. O objetivo é transformar comentários soltos em insights claros e acionáveis.

Dados disponíveis: Serão fornecidos comentários com data, canal de atendimento, texto do feedback, produto citado e nota de satisfação de 1 a 5.

Instruções de análise:
1. Classifique os feedbacks por tema, sentimento (positivo, neutro ou negativo), urgência (baixa, média ou alta) e produto citado.
2. Identifique os principais padrões, problemas, elogios e oportunidades de melhoria.
3. Aponte evidências nos dados fornecidos, usando trechos curtos dos comentários.
4. Relacione, quando os dados permitirem, os temas com as notas de satisfação.
5. Sugira ações práticas para a equipe de experiência do cliente e para o time responsável pelos canais digitais.

Formato da resposta:
- Resumo executivo com até 5 linhas.
- Tabela com as colunas: tema, sentimento, urgência, evidência e ação sugerida.
- Lista final com as 3 prioridades mais importantes e a justificativa de cada uma.

Restrições:
- Use apenas os dados fornecidos.
- Não invente números, causas ou conclusões.
- Não exponha dados pessoais ou sensíveis. Se algum comentário os contiver, omita ou anonimize essas informações.
- Não ignore comentários negativos nem destaque só os elogios.
- Informe limitações quando os dados não forem suficientes.
- Use linguagem simples, direta e voltada para a tomada de decisão.
```

---

## ✅ Revisão final

- **A tarefa está clara?** Sim: analisar feedbacks e entregar insights acionáveis.
- **O formato foi definido?** Sim: resumo executivo, tabela e 3 prioridades.
- **A IA sabe o que evitar?** Sim: inventar dados, expor informações pessoais e ignorar comentários negativos.
