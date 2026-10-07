# Desafio Criativo: insights a partir de feedbacks de clientes bancários

Neste desafio montei, em três passos, um prompt para a IA analisar comentários de clientes de um banco e me entregar algo que dê para usar de verdade: os temas que mais aparecem, o que está irritando as pessoas e o que dá para melhorar primeiro.

---

## Passo 1: Intenção

Quero que a IA leia comentários de clientes sobre o aplicativo do banco, o Pix, o cartão de crédito e o atendimento por chat, e me diga quais são as reclamações mais comuns, o que as pessoas elogiam e onde há espaço para melhorar.

Quem vai usar o resultado é a equipe de experiência do cliente e o time responsável pelos canais digitais. A ideia é que eles consigam decidir o que corrigir primeiro.

Quero receber um resumo curto, uma tabela com os principais temas e exemplos de comentários que provem cada ponto, além de sugestões práticas.

Considero o resultado bom se estiver claro, bem organizado, baseado só nos comentários que eu enviei e se ajudar a priorizar as ações.

---

## Passo 2: Contexto e restrições

**Contexto:** os feedbacks são de clientes de um banco e falam do aplicativo, do Pix, do cartão de crédito e do atendimento por chat.

**Dados:** cada comentário vem com a data, o canal de atendimento, o texto do cliente, o produto citado e uma nota de satisfação de 1 a 5.

**Como analisar:** a IA deve separar os comentários por tema, sentimento (positivo, neutro ou negativo), urgência (baixa, média ou alta) e produto citado.

**Cuidados:**

- Usar só os dados que eu fornecer.
- Não inventar números, causas ou conclusões.
- Não mostrar dados pessoais, como nome, CPF, telefone, e-mail ou número de conta e de cartão.
- Não deixar de lado os comentários negativos.
- Avisar quando não houver informação suficiente para concluir algo.
- Escrever de forma simples e direta, pensando em quem vai tomar a decisão.

---

## Passo 3: Prompt final

```text
Você é um analista de dados e de experiência do cliente de um banco.

Vou te passar feedbacks de clientes sobre o aplicativo, o Pix, o cartão de crédito e o atendimento por chat. Quero que você encontre os temas que mais se repetem, entenda como os clientes estão se sentindo e aponte o que pode melhorar.

Quem vai ler sua análise é a equipe de experiência do cliente e o time dos canais digitais. Eles precisam decidir o que atacar primeiro, então transforme os comentários soltos em pontos claros e que deem para virar ação.

Cada feedback tem data, canal de atendimento, texto, produto citado e nota de satisfação de 1 a 5.

Na análise:
1. Classifique cada feedback por tema, sentimento (positivo, neutro ou negativo), urgência (baixa, média ou alta) e produto citado.
2. Identifique os padrões, os problemas, os elogios e as oportunidades de melhoria.
3. Mostre as evidências com trechos curtos dos próprios comentários.
4. Quando os dados permitirem, relacione os temas com as notas de satisfação.
5. Sugira ações práticas para cada time.

Entregue assim:
- Um resumo de até 5 linhas.
- Uma tabela com tema, sentimento, urgência, evidência e ação sugerida.
- No final, as 3 prioridades mais importantes, com o motivo de cada uma.

Regras:
- Use só os dados que eu enviei.
- Não invente números, causas ou conclusões.
- Não exponha dados pessoais ou sensíveis. Se algum comentário tiver esse tipo de informação, omita ou anonimize.
- Não ignore as reclamações nem mostre só os elogios.
- Se os dados não bastarem para uma conclusão, diga isso.
- Use linguagem simples e direta.
```
