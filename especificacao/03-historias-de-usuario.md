# Historias de Usuario

## Participantes

### US-01

Relacionada a: `RF-01`, `RF-02`

Como participante, quero visualizar todos os eventos disponiveis em um unico lugar para comparar opcoes e decidir em quais me inscrever.

Criterios de aceitacao:

- Dado que existam eventos cadastrados, quando eu acessar a listagem, entao o sistema deve exibir os eventos disponiveis.
- Dado que um evento possua vagas e periodo de inscricao ativo, quando eu selecionar esse evento, entao o sistema deve permitir iniciar a inscricao.

### US-02

Relacionada a: `RF-03`

Como participante, quero receber um comprovante apos a inscricao para ter confirmacao do registro realizado.

Criterios de aceitacao:

- Dado que a inscricao tenha sido concluida com sucesso, quando o processo for finalizado, entao o sistema deve gerar uma confirmacao da inscricao.
- Dado que existam canais de notificacao definidos pelo negocio, quando a inscricao for confirmada, entao o sistema deve enviar ou disponibilizar o comprovante pelo canal configurado.

### US-03

Relacionada a: `RF-04`, `RN-01`

Como participante, quero cancelar minha inscricao sem precisar entrar em contato com a organizacao para ganhar autonomia no processo.

Criterios de aceitacao:

- Dado que o evento permita cancelamento, quando eu solicitar o cancelamento dentro das regras vigentes, entao o sistema deve registrar a solicitacao.
- Dado que o evento nao permita cancelamento, quando eu tentar cancelar, entao o sistema deve informar a restricao aplicavel.

### US-04

Relacionada a: `RF-05`

Como participante, quero emitir meu certificado apos o evento para comprovar minha participacao.

Criterios de aceitacao:

- Dado que eu cumpra as condicoes definidas para certificacao, quando eu solicitar o certificado, entao o sistema deve disponibilizar a emissao.
- Dado que eu nao cumpra as condicoes exigidas, quando eu tentar emitir o certificado, entao o sistema deve informar o motivo da indisponibilidade.

## Organizadores

### US-05

Relacionada a: `RF-06`, `RF-07`

Como organizador, quero cadastrar eventos e controlar vagas automaticamente para reduzir falhas operacionais.

Criterios de aceitacao:

- Dado que eu tenha permissao de organizador, quando eu cadastrar um evento, entao o sistema deve permitir definir capacidade e dados basicos do evento.
- Dado que participantes realizem inscricoes validas, quando novas vagas forem ocupadas, entao o sistema deve atualizar a quantidade disponivel.

### US-06

Relacionada a: `RF-09`

Como organizador, quero acompanhar a quantidade de inscritos em tempo real para monitorar a ocupacao dos eventos.

Criterios de aceitacao:

- Dado que existam inscricoes registradas, quando eu consultar um evento, entao o sistema deve exibir a quantidade atual de inscritos.
- Dado que ocorram novas inscricoes ou cancelamentos, quando eu atualizar a consulta, entao o sistema deve refletir o estado mais recente disponivel.

### US-07

Relacionada a: `RF-08`

Como organizador, quero ter uma lista de espera para eventos lotados para aproveitar melhor a demanda.

Criterios de aceitacao:

- Dado que um evento esteja lotado, quando um participante tentar se inscrever, entao o sistema deve permitir ingresso em lista de espera, se essa politica estiver habilitada.
- Dado que uma vaga seja liberada, quando houver regra definida para convocacao, entao o sistema deve aplicar a regra configurada para a lista de espera.

## Equipe Financeira

### US-08

Relacionada a: `RF-10`, `RF-11`, `RN-02`, `RN-04`

Como integrante da equipe financeira, quero confirmar pagamentos para liberar inscricoes dependentes dessa validacao.

Criterios de aceitacao:

- Dado que um evento exija pagamento, quando o pagamento for confirmado, entao o sistema deve permitir a liberacao da inscricao vinculada.
- Dado que o pagamento ainda nao tenha sido confirmado, quando a regra do evento exigir validacao previa, entao a inscricao nao deve ser considerada liberada.

## Palestrantes

### US-09

Relacionada a: `RF-12`, `RF-13`

Como palestrante, quero consultar a programacao e as informacoes autorizadas dos participantes das minhas atividades para me preparar melhor.

Criterios de aceitacao:

- Dado que eu esteja vinculado a uma atividade, quando eu acessar minha area, entao o sistema deve exibir a programacao correspondente.
- Dado que existam regras de privacidade definidas, quando eu consultar participantes, entao o sistema deve mostrar apenas os dados permitidos.
