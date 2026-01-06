# 💸 App de Organização de Finanças Pessoais Inteligente e Universal por Giovanna

PRD refinado no copilot web:

```markdown
PRD – App de Finanças Pessoais com Chat Inteligente e Funcionalidade Garantida

1. Objetivo
Criar um app de finanças pessoais com assistente conversacional que funcione sem travar, sem depender de autenticação externa complexa, e que permita ao usuário registrar ganhos e gastos, visualizar relatórios e acompanhar metas de forma simples e confiável.

2. Público-Alvo
- Pessoas que querem controlar suas finanças sem complicação.
- Usuários iniciantes que preferem conversar em vez de preencher formulários.
- Pessoas que buscam clareza, praticidade e controle emocional sobre o dinheiro.

3. Funcionalidades Principais
1. Chat funcional que entende frases livres e responde com base no conteúdo.
2. Registro de gastos e ganhos via chat, com categorização automática.
3. Visualização de ganhos e gastos mensais em telas separadas.
4. Relatórios e gráficos acessíveis com filtros por período.
5. Criação e acompanhamento de metas financeiras.
6. Lembretes e alertas amigáveis.
7. Interface simples, sem dados pré-carregados (começa do zero).
8. Login básico com persistência local (sem dependência de autenticação externa).
9. Respostas garantidas: o chat nunca trava, mesmo sem dados.
10. Aba de planner semanal com as metas atualizadas no dia de preferência do usuário, ele deve conseguir marcar as metas como feitas ou não.

4. Intenções e Exemplos

Registrar gasto:
- Frases: “comprei pão 12 reais”, “uber 23”, “gastei 50 no mercado”.
- Resposta: “Anotei: pão, R$12, categoria alimentação. Quer ajustar?”

Registrar ganho:
- Frases: “recebi salário 2500 reais”, “ganhei 300 de investimento”.
- Resposta: “Anotei: salário, R$2500, categoria ganhos. Deseja detalhar?”

Consultar extrato:
- Frases: “quero meu extrato”, “ver meus gastos”, “quanto gastei”.
- Resposta: “Seu extrato do mês: R$2.450 em gastos. Top categorias: alimentação, transporte, lazer.”

Ver ganhos:
- Frases: “quanto ganhei esse mês?”, “meus ganhos de outubro”.
- Resposta: “Ganhos de outubro: R$3.200 (salário R$2.500, investimentos R$500, extras R$200).”

Ver relatório:
- Frases: “resumo do mês”, “saldo atual”, “comparar ganhos e gastos”.
- Resposta: “Neste mês: ganhos R$3.200, gastos R$2.450, saldo positivo R$750.”

Criar meta:
- Frases: “quero juntar R$500 até março”, “meta de emergência R$1000”.
- Resposta: “Meta criada: R$500 até 30/03. Sugestão: guardar R$42 por semana.”

5. Telas do App

Login:
- Campos simples: nome ou e-mail.
- Persistência local (sem autenticação externa).

Chat:
- Campo de entrada livre.
- Botões rápidos: “Registrar gasto”, “Registrar ganho”, “Ver extrato”, “Criar meta”.

Gastos:
- Lista de transações.
- Total do mês.
- Botão “Adicionar gasto”.

Ganhos:
- Lista de entradas.
- Total do mês.
- Botão “Adicionar ganho”.

Relatórios:
- Gráfico de pizza (gastos por categoria).
- Gráfico de barras (ganhos vs gastos).
- Filtros: semana, mês, período personalizado.

Metas:
- Lista de metas.
- Progresso visual.
- Botão “Nova meta”.

6. Requisitos Técnicos

- Banco de dados local ou remoto simples (SQLite, Supabase com fallback).
- Chat com fallback: se não entender, responde com sugestão útil.
- Categorização por palavras-chave.
- Interface responsiva e acessível.
- Sem dependência de autenticação externa para funcionar.

7. Validação

- Chat responde corretamente em 100% dos testes.
- Registro de gasto e ganho funciona sem travar.
- Relatórios exibem dados reais ou mensagem amigável se não houver dados.
- Login simples permite iniciar do zero.
- NPS conversacional acima de 40.

```

Interações com o Lovable:
> Crie um app de finanças com o seguinte PRD:

Resultado final no lovable:
[https://pocket-guide-chat.lovable.app/](https://rendacontrol.lovable.app)

<img width="1285" height="829" alt="image" src="https://github.com/user-attachments/assets/9ca39e8f-7230-4360-9d00-1a027e2476d2" />

Resumo do que o App faz:
O aplicativo é um assistente financeiro inteligente que permite ao usuário organizar seus ganhos, controlar seus gastos e acompanhar seu saldo de forma simples e acessível.

Por meio de uma interface conversacional, o usuário registra transações em linguagem natural, como “comprei pão 12 reais” ou “recebi salário 2500”, e o sistema salva automaticamente com categorização inteligente.

O app apresenta um painel claro com o saldo total, ganhos e gastos do mês, além de uma lista de transações recentes com data, descrição, valor e categoria.

O usuário pode visualizar relatórios e gráficos comparativos entre ganhos e gastos, acompanhar metas financeiras, receber lembretes e dicas práticas, tudo com foco em bem-estar financeiro e progresso gradual.

O agente também responde a pedidos personalizados, como “quero economizar 500 reais até março”, e ajuda o usuário a criar metas, calcular valores semanais ou mensais, e acompanhar o progresso ao longo do tempo.

O login é funcional e seguro, com persistência de sessão, garantindo que cada usuário tenha seu histórico pessoal sem travamentos ou erros de autenticação. O sistema começa do zero, sem dados pré-carregados, permitindo uma experiência personalizada desde o início.
 
Reflexão sobre o projeto:
- O que funcionou bem?
  A estrutura do aplicativo está sólida. As funcionalidades principais, como o registro de gastos e ganhos, o desempenho geral, e o login, funcionaram com rapidez e estabilidade. A experiência de uso foi fluida e responsiva, permitindo que as ações básicas fossem realizadas com facilidade.
     
  - O que aprendeu sobre conversar com IAs?
   É essencial ser o mais específico possível ao formular os comandos e expectativas. Detalhar claramente o que se espera da resposta ou funcionalidade ajuda a evitar interpretações ambíguas. Além disso, revisar os prompts antes de aplicar garante que a IA compreenda corretamente a intenção e execute com precisão.


