# Gestão de Documentos na Administração Pública Brasileira  
**Caderno Temático criado com NotebookLM**

## Contexto e Objetivos

A gestão de documentos é um pilar da administração pública brasileira, regulada principalmente pela **Lei nº 8.159/1991** (Lei de Arquivos). Ela garante eficiência, transparência, preservação da memória institucional e o direito à informação.

**Objetivos do caderno**:
- Entender os conceitos básicos e o ciclo de vida dos documentos.
- Conhecer as principais normas e instrumentos (CPAD, tabela de temporalidade, e-ARQ Brasil).
- Identificar boas práticas para produção, tramitação e destinação de documentos (em papel e digitais).
- Criar um material prático e reutilizável para estudos ou aplicação no serviço público.

## Curadoria de Fontes (4 fontes oficiais)

Todas as fontes são abertas e oficiais do Governo Federal:

1. **Lei nº 8.159, de 8 de janeiro de 1991** (Lei de Arquivos)  
   Link: https://www.planalto.gov.br/ccivil_03/leis/l8159.htm

2. **Gestão de Documentos: Curso de capacitação para os integrantes do Sistema de Gestão de Documentos de Arquivo – SIGA, da administração pública federal
   Link: https://www.gov.br/arquivonacional/pt-br/servicos/gestao-de-documentos/orientacao-tecnica-1/publicacoes-tecnicas-de-referencia/gestao_de_documentos.pdf
 
3. **Guia de Gestão de Documentos para os Órgãos e Entidades do Poder Executivo Federal** (Arquivo Nacional, 2025)  
   Link: https://www.gov.br/arquivonacional/pt-br/servicos/publicacoes/Guiadegestaodedocumentos.pdf

4. **e-ARQ Brasil – Modelo de Requisitos para Sistemas Informatizados de Gestão Arquivística de Documentos (Versão 2, 2022)**  
   Link: https://www.gov.br/conarq/pt-br/centrais-de-conteudo/publicacoes/EARQV203MAI2022.pdf

*(3 fontes foram carregadas diretamente no NotebookLM via URL, enquanto a lei foi copiada e colada)*

## Engenharia de Prompts e Cicatrizes (meu processo)

Testei vários prompts para extrair o melhor do NotebookLM. Aqui os principais:

**Prompt 1 (base)**:  
“Usando apenas as fontes carregadas, explique o conceito de gestão de documentos segundo a Lei 8.159/1991 e liste as três fases do ciclo de vida dos documentos.”

**Prompt 2 (resumo prático)**:  
“Crie um resumo estruturado das principais etapas de um Programa de Gestão de Documentos, destacando o papel da CPAD.”

**Prompt 3 (glossário)**:  
“Extraia e organize em formato de glossário os 10 conceitos mais importantes: documento de arquivo, fase corrente, tabela de temporalidade, CPAD, e-ARQ Brasil etc.”

**Dificuldades encontradas (cicatrizes)**:  
- No início o NotebookLM dava respostas muito genéricas → resolvi adicionando sempre “usando apenas as fontes carregadas”.  
- O Guia de 2025 trouxe atualizações importantes sobre documentos digitais que não estavam na lei antiga.  
- Precisei refinar os prompts para o modelo não misturar conceitos de papel e digital.

EX:

<img width="792" height="816" alt="image" src="https://github.com/user-attachments/assets/940d43b6-ca04-4d32-a70d-cfe0afd1e413" />


P: **Usando apenas as fontes carregadas, explique o conceito de gestão de documentos segundo a Lei 8.159/1991 e liste as três fases do ciclo de vida dos documentos com suas características principais.**

R: Segundo a **Lei 8.159/1991 (Lei de Arquivos)**, em seu artigo 3º, a **gestão de documentos** é definida como o **conjunto de procedimentos e operações técnicas** referentes à sua **produção, tramitação, uso, avaliação e arquivamento** em fase corrente e intermediária,,. O objetivo central dessas atividades é visar a **eliminação** dos documentos ou o seu **recolhimento para guarda permanente**,,.

O **ciclo de vida dos documentos** refere-se às sucessivas fases pelas quais os documentos passam, desde a sua produção até a sua destinação final,,. As três fases e suas principais características são:

1.  **Produção**: Esta fase corresponde à **elaboração e recebimento** de documentos em razão da execução das atividades de um órgão ou entidade,,. Suas características principais incluem o **controle e a otimização da criação documental**, visando evitar a proliferação de documentos não essenciais e garantir o uso adequado de recursos tecnológicos e modelos padronizados,,.
2.  **Utilização**: Refere-se ao **fluxo percorrido pelos documentos** (tramitação) para o cumprimento de suas funções administrativas, bem como à sua **guarda e conservação** após cessar o trâmite imediato,,. Esta fase envolve atividades de **protocolo**, técnicas de **classificação**, organização e a gestão de arquivos nas fases corrente e intermediária para facilitar a recuperação da informação,.
3.  **Destinação**: É a fase em que se decide, após um processo de **avaliação**, quais documentos possuem valor histórico ou probatório e devem ser preservados definitivamente (**guarda permanente**) e quais não possuem mais utilidade administrativa, legal ou fiscal e podem ser **eliminados**,,. Suas características principais são a análise, a seleção e a **fixação de prazos de guarda**, garantindo que nenhum documento seja preservado por tempo superior ao necessário, a menos que tenha valor secundário para pesquisa ou como testemunho do passado,,.

## Miniguia de Estudo (Entrega Final)

### Resumos estruturados
- **Definição**: Gestão de documentos = conjunto de procedimentos técnicos para produção, tramitação, uso, avaliação e arquivamento (Lei 8.159/91, Art. 3º).  
- **Ciclo de vida**: Fase corrente → Fase intermediária → Fase permanente.  
- **Instrumentos principais**: Código de Classificação, Tabela de Temporalidade, CPAD e e-ARQ Brasil (para sistemas digitais).

### Glossário
- **Documento de arquivo**: Documento produzido ou recebido no exercício de atividades específicas.  
- **CPAD**: Comissão Permanente de Avaliação de Documentos – responsável pela avaliação e destinação.  
- **Tabela de Temporalidade**: Define prazos de guarda e destinação final.  
- **e-ARQ Brasil**: Modelo de requisitos para sistemas informatizados de gestão arquivística.

### Prompts reutilizáveis (copie e use no seu NotebookLM)
1. “Resuma o papel da CPAD nas fontes carregadas.”  
2. “Compare gestão de documentos em papel x digitais segundo o e-ARQ Brasil.”  
3. “Crie um fluxograma textual das etapas de avaliação de documentos.”  
4. “Liste boas práticas para [tema específico] segundo o Guia 2025.”

**Notebook criado com NotebookLM + fontes oficiais do Arquivo Nacional.**
