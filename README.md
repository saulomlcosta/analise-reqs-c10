# mc10-engenharia-requisitos-ia

Atividade pratica da unidade sobre uso de IA Generativa no apoio a especificacao de requisitos. O ponto de partida foi o documento de elicitacao do **Sistema de Gestao de Eventos** apresentado no material da disciplina.

## Objetivo

Transformar o texto de elicitacao em artefatos de especificacao mais claros, rastreaveis e revisaveis, usando IA como apoio para:

- identificar requisitos funcionais, nao funcionais e regras de negocio;
- explicitar ambiguidades e pendencias;
- sugerir artefatos de especificacao adequados;
- acelerar a redacao inicial dos artefatos, com revisao humana posterior.

## Estrutura do repositorio

```text
.
|-- README.md
|-- discussion-post.md
`-- especificacao
    |-- 01-analise-do-documento.md
    |-- 02-catalogo-de-requisitos.md
    |-- 03-historias-de-usuario.md
    `-- 04-questoes-em-aberto.md
```

## Artefatos escolhidos

Os artefatos selecionados para este projeto foram:

- **analise do documento de elicitacao**, para separar fatos levantados, lacunas e pontos de risco;
- **catalogo de requisitos**, para consolidar requisitos funcionais, nao funcionais e regras de negocio com identificadores;
- **historias de usuario com criterios de aceitacao**, para tornar os requisitos mais claros e verificaveis;
- **lista de questoes em aberto**, para registrar o que ainda precisa ser validado com stakeholders.

Considerei esse conjunto mais adequado porque o material apresenta necessidades claras do negocio, mas tambem varias indefinicoes importantes. Antes de pensar em prototipos ou modelagens mais detalhadas, fez mais sentido organizar o entendimento do problema, tornar os requisitos rastreaveis e destacar tudo o que ainda nao pode ser decidido com seguranca.

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
