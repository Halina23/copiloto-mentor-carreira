# 🚀 AI Career Advisor | Copiloto Especialista em Carreiras Tech
Este projeto foi desenvolvido como parte do curso CI&T - Do Prompt ao Agente, oferecido pela plataforma DIO (Digital Innovation One)
O objetivo do projeto é utilizar a Engenharia de Prompts para configurar um agente inteligente (Copiloto) capaz de atuar como um entrevistador especializado em descobrir e direcionar o perfil profissional de pessoas interessadas em ingressar ou migrar para a área de tecnologia.

### 🎯 O Problema
Muitos profissionais têm interesse em entrar na área de tecnologia, mas se sentem perdidos diante da imensa variedade de trilhas (Front-end, Back-end, Dados, IA, Cloud, etc.). Este agente resolve esse problema automatizando o processo de triagem e orientação inicial de forma personalizada e interativa.

### ⚙️ Como Funciona (O Fluxo do Agente)
O sistema foi desenhado para assumir a persona de um recrutador/mentor sênior. O fluxo de interação ocorre em 3 etapas principais:

1. A Entrevista Estruturada
O agente conduz uma entrevista interativa composta por 7 perguntas estratégicas, focadas em extrair o máximo de informações sobre o candidato em 5 pilares fundamentais:

### 💡 Interesses e motivações: O que atrai o candidato na tecnologia?
### 🛠️ Experiência prévia: Background técnico ou de outras áreas.
### 📚 Disponibilidade de estudo: Tempo diário/semanal dedicado ao aprendizado.
### 🏢 Preferências de trabalho: Trabalho em equipe, foco em lógica, design, etc.
### 🎯 Objetivos profissionais: Onde o candidato deseja chegar a médio/longo prazo.

2. Análise e Sugestão de Carreira
Após coletar e processar as informações da entrevista, o agente cruza os dados com as demandas do mercado de tecnologia e gera como saída (Output):
Uma lista ranqueada com as 3 carreiras mais adequadas ao perfil do usuário, com uma breve justificativa para cada escolha.
3. Transferência de Contexto (Handoff)
Finalizada a recomendação, o agente encerra o seu escopo e realiza o roteamento, transferindo o contexto do candidato de forma estruturada para o Agent 2 (que pode assumir a função de traçar o plano de estudos ou buscar vagas, por exemplo).
### 🛠️ Tecnologias e Conceitos Aplicados
Prompt Engineering (Engenharia de Prompts): Construção de instruções claras, definição de persona, restrições e formatação de saída.


Inteligência Artificial Generativa (LLMs): Uso do Copilot para simular raciocínio e conversação natural.


Arquitetura de Múltiplos Agentes: Divisão de tarefas complexas entre agentes especialistas
(Agente 1: Entrevistador -> Agente 2: Próxima etapa).
