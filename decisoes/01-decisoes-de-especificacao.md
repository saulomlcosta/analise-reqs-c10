# Decisoes de Especificacao

## Objetivo

Registrar as principais decisoes tomadas durante a transformacao do documento de elicitacao em artefatos de especificacao, deixando explicito o racional adotado no exercicio.

## DEC-01 - Escolha de um conjunto enxuto de artefatos

**Decisao:** adotar um conjunto reduzido de artefatos composto por analise do documento, catalogo de requisitos, historias de usuario e questoes em aberto.

**Justificativa:** o material de origem oferece uma boa visao do dominio, mas ainda apresenta lacunas importantes. Antes de expandir para modelos mais detalhados, fez mais sentido consolidar entendimento, organizar requisitos e destacar pendencias.

**Impacto:** a entrega fica objetiva, alinhada ao exercicio e mais facil de revisar, embora menos abrangente do que um repositorio de produto completo.

## DEC-02 - Tratar requisitos nao funcionais como recomendacoes a validar

**Decisao:** registrar requisitos nao funcionais como necessidades de especificacao, e nao como fatos confirmados do negocio.

**Justificativa:** o documento original informa que seguranca, desempenho, disponibilidade, acessibilidade e privacidade nao foram levantados nas entrevistas. Ainda assim, esses temas sao relevantes para a especificacao e nao deveriam ser ignorados.

**Impacto:** o projeto reconhece a importancia dos RNFs sem inventar requisitos fechados em nome dos stakeholders.

## DEC-03 - Nao assumir regras de negocio ausentes

**Decisao:** manter cancelamento, reembolso, lista de espera, certificacao, notificacoes e reserva de vaga como pontos em aberto quando o material nao define comportamento suficiente.

**Justificativa:** assumir respostas nesses casos reduziria a confiabilidade da especificacao e misturaria hipotese com fato.

**Impacto:** a especificacao preserva rastreabilidade e transparencia sobre o que ainda depende de validacao.
