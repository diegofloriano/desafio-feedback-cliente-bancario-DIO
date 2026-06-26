# Desafio Técnico: Extraindo Insights do Feedback de Clientes Bancários

Este repositório contém a entrega do Desafio Criativo proposto na plataforma DIO, aplicando engenharia de prompts para estruturar uma análise qualitativa de dados de clientes do setor bancário.

---

### 🧱 Passo 1: Definição da Intenção

Quero que a IA analise reclamações de clientes em lojas de aplicativos (App Store e Google Play) sobre lentidão no Pix para identificar os principais erros operacionais informados pelos usuários.

O resultado será usado pela equipe de produtos digitais para apoiar a priorização de correções no aplicativo e melhorias na infraestrutura de pagamentos.

A entrega deve conter uma lista direta com os 3 problemas mais recorrentes e recomendações práticas para o time de desenvolvimento.

O resultado será considerado bom se for objetivo, focado em melhorias de usabilidade e livre de termos técnicos excessivamente complexos.

---

### 🧱 Passo 2: Adicione contexto e restrições

Contexto: Estou trabalhando com feedbacks de clientes bancários relacionados a transações via Pix, falhas de envio e lentidão no carregamento do saldo.

Dados disponíveis: A base contém o texto bruto do comentário, sistema operacional (Android/iOS), data da ocorrência e nota da avaliação (1 a 5).

Critérios de análise: A IA deve classificar os feedbacks por gravidade do erro e tipo de falha (como timeout na transação, erro de biometria ou atraso na notificação).

Cuidados e restrições:
* Use apenas os dados fornecidos.
* Não invente números, causas ou conclusões.
* Não exponha dados pessoais ou sensíveis.
* Se houver informação insuficiente, indique a limitação.
* Use linguagem executiva e focada em melhoria de produto.

---

### 🧱 Passo 3: Prompt Final Estruturado

Atue como analista de experiência do cliente focado em produtos financeiros.

Sua tarefa é analisar relatos de usuários nas lojas de aplicativos sobre instabilidade no Pix para identificar os principais bugs sistêmicos e dores na jornada de pagamento.

Contexto: Tivemos um pico de reclamações após a última atualização do aplicativo. O time de engenharia precisa mapear os relatos para entender se o problema está isolado em algum sistema operacional e agir rápido na correção.

Dados disponíveis: Planilha contendo o texto da reclamação, data da postagem, nota da avaliação e versão do aplicativo utilizada pelo cliente.

Instruções de análise:
* Classifique os feedbacks por tipo de erro técnico relatado e por sistema operacional.
* Identifique os principais padrões, problemas, elogios e oportunidades.
* Aponte evidências nos dados fornecidos.
* Sugira ações práticas para a equipe de desenvolvimento de software e UX.

Formato da resposta: Um sumário em tópicos curtos dividido pelos tipos de falhas encontrados e uma lista final de prioridades para correção.

Restrições:
* Use apenas os dados fornecidos.
* Não invente números, causas ou conclusões.
* Não exponha dados pessoais ou sensíveis.
* Informe limitações quando os dados não forem suficientes.
* Use linguagem direta, profissional e focada em tomada de decisão.
