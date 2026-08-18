# Histórias de Usuário

## Participantes

### US-01

Como participante, quero visualizar todos os eventos disponíveis em um único lugar para comparar opções e decidir em quais me inscrever.

Critérios de aceitação:

- Dado que existam eventos cadastrados, quando eu acessar a listagem, então o sistema deve exibir os eventos disponíveis.
- Dado que um evento possua vagas e período de inscrição ativo, quando eu selecionar esse evento, então o sistema deve permitir iniciar a inscrição.

### US-02

Como participante, quero receber um comprovante após a inscrição para ter confirmação do registro realizado.

Critérios de aceitação:

- Dado que a inscrição tenha sido concluída com sucesso, quando o processo for finalizado, então o sistema deve gerar uma confirmação da inscrição.
- Dado que existam canais de notificação definidos pelo negócio, quando a inscrição for confirmada, então o sistema deve enviar ou disponibilizar o comprovante pelo canal configurado.

### US-03

Como participante, quero cancelar minha inscrição sem precisar entrar em contato com a organização para ganhar autonomia no processo.

Critérios de aceitação:

- Dado que o evento permita cancelamento, quando eu solicitar o cancelamento dentro das regras vigentes, então o sistema deve registrar a solicitação.
- Dado que o evento não permita cancelamento, quando eu tentar cancelar, então o sistema deve informar a restrição aplicável.

### US-04

Como participante, quero emitir meu certificado após o evento para comprovar minha participação.

Critérios de aceitação:

- Dado que eu cumpra as condições definidas para certificação, quando eu solicitar o certificado, então o sistema deve disponibilizar a emissão.
- Dado que eu não cumpra as condições exigidas, quando eu tentar emitir o certificado, então o sistema deve informar o motivo da indisponibilidade.

## Organizadores

### US-05

Como organizador, quero cadastrar eventos e controlar vagas automaticamente para reduzir falhas operacionais.

Critérios de aceitação:

- Dado que eu tenha permissão de organizador, quando eu cadastrar um evento, então o sistema deve permitir definir capacidade e dados básicos do evento.
- Dado que participantes realizem inscrições válidas, quando novas vagas forem ocupadas, então o sistema deve atualizar a quantidade disponível.

### US-06

Como organizador, quero acompanhar a quantidade de inscritos em tempo real para monitorar a ocupação dos eventos.

Critérios de aceitação:

- Dado que existam inscrições registradas, quando eu consultar um evento, então o sistema deve exibir a quantidade atual de inscritos.
- Dado que ocorram novas inscrições ou cancelamentos, quando eu atualizar a consulta, então o sistema deve refletir o estado mais recente disponível.

### US-07

Como organizador, quero ter uma lista de espera para eventos lotados para aproveitar melhor a demanda.

Critérios de aceitação:

- Dado que um evento esteja lotado, quando um participante tentar se inscrever, então o sistema deve permitir ingresso em lista de espera, se essa política estiver habilitada.
- Dado que uma vaga seja liberada, quando houver regra definida para convocação, então o sistema deve aplicar a regra configurada para a lista de espera.

## Equipe Financeira

### US-08

Como integrante da equipe financeira, quero confirmar pagamentos para liberar inscrições dependentes dessa validação.

Critérios de aceitação:

- Dado que um evento exija pagamento, quando o pagamento for confirmado, então o sistema deve permitir a liberação da inscrição vinculada.
- Dado que o pagamento ainda não tenha sido confirmado, quando a regra do evento exigir validação prévia, então a inscrição não deve ser considerada liberada.

## Palestrantes

### US-09

Como palestrante, quero consultar a programação e as informações autorizadas dos participantes das minhas atividades para me preparar melhor.

Critérios de aceitação:

- Dado que eu esteja vinculado a uma atividade, quando eu acessar minha área, então o sistema deve exibir a programação correspondente.
- Dado que existam regras de privacidade definidas, quando eu consultar participantes, então o sistema deve mostrar apenas os dados permitidos.

