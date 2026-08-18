# Catálogo de Requisitos

## Requisitos funcionais

| ID | Requisito |
| --- | --- |
| RF-01 | O sistema deve permitir visualizar todos os eventos disponíveis em um único lugar. |
| RF-02 | O sistema deve permitir que participantes se inscrevam em eventos e workshops. |
| RF-03 | O sistema deve fornecer comprovante de inscrição após o registro da inscrição. |
| RF-04 | O sistema deve permitir o cancelamento da inscrição, quando essa operação for permitida para o evento. |
| RF-05 | O sistema deve permitir a emissão de certificado após a participação no evento. |
| RF-06 | O sistema deve permitir que organizadores criem e gerenciem eventos. |
| RF-07 | O sistema deve controlar automaticamente a quantidade de vagas por evento ou atividade. |
| RF-08 | O sistema deve permitir a formação de lista de espera quando um evento estiver lotado. |
| RF-09 | O sistema deve permitir acompanhar a quantidade de inscritos em tempo real. |
| RF-10 | O sistema deve tratar eventos gratuitos e eventos pagos. |
| RF-11 | O sistema deve permitir confirmar pagamentos antes da liberação de inscrições que dependam dessa validação. |
| RF-12 | O sistema deve permitir que palestrantes consultem a programação de suas atividades. |
| RF-13 | O sistema deve permitir que palestrantes consultem informações autorizadas sobre participantes de suas atividades. |

## Requisitos não funcionais

Estes requisitos foram propostos a partir das lacunas identificadas no documento original e devem ser validados com stakeholders.

| ID | Requisito |
| --- | --- |
| RNF-01 | O sistema deve exigir autenticação para acesso a funcionalidades restritas por perfil de usuário. |
| RNF-02 | O sistema deve proteger dados pessoais dos participantes de acordo com políticas de privacidade aplicáveis. |
| RNF-03 | O sistema deve registrar operações relevantes de inscrição, cancelamento e confirmação de pagamento para fins de auditoria. |
| RNF-04 | O sistema deve responder às consultas principais de eventos e inscrições com desempenho adequado ao uso operacional. |
| RNF-05 | O sistema deve manter disponibilidade compatível com períodos de inscrição e realização de eventos. |
| RNF-06 | O sistema deve oferecer interface com critérios mínimos de acessibilidade. |

## Regras de negócio

| ID | Regra |
| --- | --- |
| RN-01 | Nem todo evento permite cancelamento de inscrição. |
| RN-02 | Alguns eventos são gratuitos e outros são pagos. |
| RN-03 | Em alguns cenários há direito a reembolso e em outros não. |
| RN-04 | Determinadas inscrições só podem ser liberadas após confirmação do pagamento. |
| RN-05 | Eventos ou workshops podem ocorrer simultaneamente no mesmo horário. |

## Observações de especificação

- `RF-04` depende da definição da política de cancelamento por evento.
- `RF-05` depende da definição do critério de emissão do certificado.
- `RF-08` depende da regra de funcionamento da lista de espera.
- `RF-11` depende da definição de quando a vaga fica reservada no fluxo de pagamento.
- `RF-13` depende da definição de quais dados dos participantes poderão ser exibidos aos palestrantes.

