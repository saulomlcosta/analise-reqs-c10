# Sistema de Gestao de Eventos - Eventus

> Exercicio da pos-graduacao em **Engenharia de Software com IA - UFG**.
> Trabalho academico de especificacao de requisitos com apoio de IA Generativa.

Este repositorio apresenta a atividade pratica da unidade a partir do documento de elicitacao do **Sistema de Gestao de Eventos (Eventus)**. O objetivo foi transformar o material inicial em artefatos de especificacao mais organizados, rastreaveis e revisaveis, mantendo explicitas as ambiguidades e pendencias do problema.

## Objetivo

Organizar o conteudo levantado na elicitacao em artefatos que apoiem melhor a analise e a especificacao do sistema, usando IA como apoio para:

- identificar requisitos funcionais, nao funcionais e regras de negocio;
- explicitar ambiguidades e pendencias;
- sugerir artefatos de especificacao adequados;
- acelerar a redacao inicial dos artefatos, com revisao humana posterior.

## Escopo da entrega

Este projeto foi desenvolvido como **exercicio academico**, com foco em engenharia de requisitos. Diferentemente de um repositorio mais amplo de produto, aqui o foco esta em produzir artefatos de especificacao claros a partir da elicitacao fornecida pela disciplina.

Os artefatos escolhidos foram:

- **analise do documento de elicitacao**, para separar fatos levantados, lacunas e pontos de risco;
- **catalogo de requisitos**, para consolidar requisitos funcionais, nao funcionais e regras de negocio com identificadores;
- **historias de usuario com criterios de aceitacao**, para tornar os requisitos mais claros e verificaveis;
- **lista de questoes em aberto**, para registrar o que ainda precisa ser validado com stakeholders.

## Estrutura do repositorio

```text
.
|-- README.md
|-- decisoes
|   `-- 01-decisoes-de-especificacao.md
`-- especificacao
    |-- 01-analise-do-documento.md
    |-- 02-catalogo-de-requisitos.md
    |-- 03-historias-de-usuario.md
    `-- 04-questoes-em-aberto.md
```

## Contexto do problema

A empresa ficticia **Eventus** organiza congressos, workshops e eventos corporativos. O processo atual depende de formularios on-line e planilhas, o que dificulta o controle de vagas, confirmacao de pagamentos, cancelamentos e emissao de certificados.

Com base nisso, a proposta do exercicio foi analisar o documento de elicitacao e estruturar uma especificacao inicial que deixasse claro:

- o que ja esta definido;
- o que ainda esta ambiguo;
- o que depende de validacao com stakeholders;
- e quais requisitos adicionais, especialmente nao funcionais, precisam ser considerados.

## Como a IA foi utilizada

Ferramenta utilizada: **ChatGPT / IA Generativa**.

A IA apoiou principalmente em quatro frentes:

- leitura e organizacao do conteudo do documento de elicitacao;
- identificacao inicial de requisitos, regras e ambiguidades;
- sugestao de artefatos de especificacao compativeis com o contexto do projeto;
- geracao de rascunhos textuais para os artefatos, depois revisados e ajustados manualmente.

## O que foi aceito

As sugestoes da IA mais aproveitadas foram:

- separar o conteudo em requisitos funcionais, nao funcionais, regras de negocio e pendencias;
- usar identificadores estaveis como `RF-01`, `RNF-01` e `RN-01`;
- complementar as historias de usuario com criterios de aceitacao objetivos;
- registrar explicitamente os pontos nao definidos pelo documento, em vez de assumir respostas.

## O que foi modificado ou descartado

Algumas sugestoes precisaram ser ajustadas:

- a IA poderia levar a uma quantidade maior de artefatos, como prototipos, diagramas e casos de uso completos; optei por um conjunto mais enxuto, suficiente para a atividade;
- os requisitos nao funcionais nao estavam levantados no documento original, entao eles foram registrados como **recomendacoes de especificacao** e nao como fatos ja confirmados;
- regras como prazo de cancelamento, politica de reembolso, comportamento da lista de espera e reserva de vaga durante pagamento **nao foram inventadas**, porque o material indica que ainda dependem de esclarecimento com stakeholders.

## Por que estes artefatos foram considerados os mais adequados

O documento de elicitacao mostra um problema real de negocio, mas com lacunas relevantes. Por isso, os artefatos escolhidos ajudam primeiro a **estruturar o entendimento**, **evitar ambiguidade** e **preservar rastreabilidade**. Em um contexto como esse, uma boa especificacao inicial precisa deixar claro tanto o que ja se sabe quanto o que ainda precisa ser decidido.

## Rastreabilidade

O repositorio organiza os artefatos de forma encadeada:

- a analise inicial identifica fatos, lacunas e riscos do documento de elicitacao;
- o catalogo consolida requisitos, regras de negocio e RNFs com identificadores estaveis;
- as historias de usuario detalham parte desses requisitos com criterios de aceitacao;
- as questoes em aberto mostram o que ainda bloqueia definicoes mais precisas;
- o registro em [decisoes/01-decisoes-de-especificacao.md](/C:/Users/saulo/WWW/AKCITPROJECTS/analise-reqs-c10/decisoes/01-decisoes-de-especificacao.md) documenta por que esse formato de entrega foi adotado.
