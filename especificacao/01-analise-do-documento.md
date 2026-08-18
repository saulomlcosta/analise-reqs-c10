# Análise do Documento de Elicitação

## Contexto do problema

A empresa **Eventus** organiza congressos, workshops e eventos corporativos. O processo atual usa formulários on-line e planilhas, o que dificulta:

- controle de vagas;
- confirmação de pagamentos;
- cancelamentos;
- emissão de certificados.

O objetivo do sistema é centralizar essas atividades, melhorar a experiência dos participantes e aumentar o controle operacional dos organizadores.

## Stakeholders identificados

| Stakeholder | Interesse principal |
| --- | --- |
| Participantes | Inscrever-se em eventos, acompanhar inscrições, cancelar participação e emitir certificados |
| Organizadores | Criar eventos, controlar vagas, acompanhar inscrições e gerenciar participantes |
| Equipe Financeira | Confirmar pagamentos e controlar reembolsos |
| Palestrantes | Consultar programação e informações sobre participantes de suas atividades |
| Equipe de TI | Desenvolver e manter o sistema |

## Requisitos funcionais identificados

- Visualização centralizada dos eventos disponíveis.
- Inscrição em eventos e workshops.
- Emissão de comprovante após inscrição.
- Cancelamento de inscrição pelo participante.
- Emissão de certificado após o evento.
- Criação e gerenciamento de eventos por organizadores.
- Controle automático de vagas.
- Lista de espera para eventos lotados.
- Acompanhamento em tempo real da quantidade de inscritos.
- Tratamento de eventos gratuitos e pagos.
- Confirmação de pagamento antes da liberação de determinadas inscrições.
- Consulta de participantes inscritos pelos palestrantes.

## Regras de negócio percebidas

- Nem todos os eventos permitem cancelamento.
- Alguns eventos são gratuitos e outros exigem pagamento.
- Em alguns casos existe reembolso, em outros não.
- Determinadas inscrições só são liberadas após confirmação do pagamento.
- Workshops no mesmo horário podem existir simultaneamente.

## Requisitos não funcionais percebidos como necessários

O documento informa explicitamente que **não foram levantados** requisitos de segurança, desempenho, disponibilidade, acessibilidade e privacidade. Ainda assim, esses temas precisam aparecer na especificação porque são relevantes para o sistema.

Foram então registrados como necessidades de especificação:

- segurança no acesso e no tratamento de dados;
- desempenho adequado nas consultas e inscrições;
- disponibilidade da plataforma em períodos de alta procura;
- acessibilidade mínima para uso por diferentes perfis de usuário;
- privacidade e proteção de dados pessoais.

## Ambiguidades e lacunas

Os seguintes pontos precisam de validação com stakeholders:

- até quando o participante poderá cancelar a inscrição;
- em quais situações haverá reembolso;
- como funcionará a lista de espera;
- se o certificado será automático ou condicionado à confirmação de presença;
- como serão enviados comprovantes e notificações;
- se a vaga será reservada no início do pagamento ou apenas após confirmação;
- como tratar inscrição em atividades com horários conflitantes;
- quais dados dos participantes poderão ser visualizados pelos palestrantes.

## Leitura crítica

O documento de elicitação já oferece boa visão do domínio, mas ainda está mais próximo de um levantamento inicial do que de uma especificação pronta para desenvolvimento. Por isso, faz sentido complementar o material com artefatos que:

- consolidem os requisitos de forma rastreável;
- separem fatos de hipóteses;
- registrem claramente tudo o que ainda depende de decisão.

