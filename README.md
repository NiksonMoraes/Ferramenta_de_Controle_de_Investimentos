📊 Projeto: Controle de Investimentos em Excel
Visão Geral

Este projeto consiste em uma planilha em Microsoft Excel desenvolvida para apoiar a gestão de investimentos, com foco em:

Planejamento financeiro de longo prazo;
Simulação de crescimento patrimonial com juros compostos;
Apoio à tomada de decisão de investimento visando a organização e controle de Fundos Imobiliários (FIIs);
Classificação do perfil do investidor;

A solução foi estruturada para ser intuitiva, automatizada e visual, utilizando recursos nativos do Excel.

Estrutura da Planilha

O arquivo é composto pelas seguintes abas:
Perguntas de Negócio;
Dashboard;
FIIs Controls;
Tabelas de Apoio.

Cada aba possui uma função específica dentro do projeto.

Aba: Perguntas de Negócio
🎯 Centralizar as principais perguntas estratégicas do investidor, servindo como base para os cálculos e análises do projeto.

🔧 Características Técnicas

Organização lógica das perguntas de negócio;
Base conceitual para os cálculos automáticos;
Facilita entendimento do problema de negócio.

Aba: Dashboard
🎯 Apresentar os resultados do projeto de forma visual, clara e executiva.

🔧 Características Técnicas Utilizadas

Gráficos dinâmicos;
Referência a células calculadas em outras abas;
Estrutura preparada para atualização automática conforme os dados de entrada.

Aba: FIIs Controls
🎯 Controlar e organizar a alocação de investimentos em Fundos Imobiliários (FIIs) de acordo com o perfil do investidor.

📌 Funcionalidades

Classificação dos FIIs por:
Tipo (Papel, Tijolo, Híbrido);
Perfil do investidor (Conservador, Moderado, etc.);
Definição de percentuais de alocação;
Criação de uma chave de controle (Perfil + Tipo de FII).

Aba: Tabelas de Apoio
🎯 Fornecer dados auxiliares para sustentar os cálculos, classificações e automações da planilha.

📌 Funcionalidades

Tabelas de referência para:
Perfis de investidor;
Tipos de FIIs;
Percentuais padrão de alocação.

🔧 Características Técnicas

Separação entre dados operacionais e dados de apoio para facilita manutenção e escalabilidade do projeto e reduzir o risco de erros em fórmulas.

Forma de Utilização da Planilha
🧭 Passo a Passo de Uso
1️⃣ Aba FIIs Controls (Gestão e Alocação)
Esta é a aba inicial e principal para o usuário.

No campo de Configurações:
O usuário deve informar sua renda mensal em "Salario" e o rendimento da carteira.

No campo de Investimento Mensal:
O usuário deve informar o valor do investimento mensal, Período de investimento (em anos) e a Taxa de rendimento mensal (%)

Essas informações servem como base para todos os cálculos do projeto.

Nesta aba de FIIs Controls o usuário também pode:
Analisar a distribuição de investimentos em FIIs;
Ver a classificação por tipo de FII por Perfil do investidor

➡️ Basta preencher os campos indicados, sem alterar células de cálculo.

2️⃣ Processamento Automático dos Cálculos

Com base nos dados informados, o Excel calcula automaticamente:
Patrimônio acumulado ao final do período com o crescimento do capital com juros compostos mensais e a estimativa de dividendos mensais

3️⃣ Aba Dashboard (Visualização dos Resultados)

Após o preenchimento dos dados o Dashboard é atualizado automaticamente e o usuário pode visualizar:

Apoio visual para tomada de decisão

Essa aba é indicada para análise rápida e apresentações.

4️⃣ Aba Tabelas de Apoio (Base Técnica)

Esta aba não exige interação direta do usuário.

Ela contém:
Tabelas auxiliares; Classificações e Parâmetros usados nas fórmulas

⚠️ Recomenda-se não alterar esta aba sem conhecimento técnico.

Funcionalidades Gerais do Projeto

📈 Cálculos Financeiros
Simulação de juros compostos mensais;
Projeção de patrimônio acumulado ao longo do tempo;
Estimativa de dividendos mensais;

⚙️ Recursos do Excel Utilizados

Fórmulas financeiras;
Referências entre abas;
Tabelas estruturadas;
Gráficos;
Organização por camadas (entrada, cálculo e visualização).
Variaveis Globais;
Nomeação de Intervalos.
Uniformidade Visual;

Conclusão

Este projeto em Excel oferece uma solução prática e robusta para o controle e planejamento de investimentos, unindo conceitos financeiros, organização de dados e visualização estratégica, sendo ideal tanto para uso pessoal quanto acadêmico ou profissional.
