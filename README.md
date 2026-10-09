 Auto Center Veloz: Veloz Chat

Canal de comunicação por veículo entre a oficina e o cliente, no estilo de um chat, para informar o status do conserto, enviar fotos das peças e aprovar orçamentos sem depender de ligações.

---

. Briefing do problema

A Auto Center Veloz é uma oficina mecânica de manutenção preventiva e corretiva de veículos de passeio. Ela é liderada pelos irmãos Eduardo (gerente de oficina) e Henrique (financeiro e compras), e conta com 5 elevadores, 6 mecânicos e 2 recepcionistas. Tem excelente reputação técnica na cidade.

**A dor:** a comunicação com o cliente ainda é manual (orçamento impresso e ligações). Com a frota de clientes crescendo, isso gera:

- Telefone da recepção sempre ocupado com clientes perguntando o status do conserto.
- Mecânicos interrompendo o serviço para responder à recepção.
- Clientes levando horas para aprovar orçamentos.
- Pátio lotado de carros parados aguardando resposta.
- Risco de avaliações negativas na internet por falha de comunicação.

**A oportunidade:** a concorrência é formada por concessionárias (caras, mas com relatórios digitais) e oficinas pequenas e informais. A Veloz pode unir a confiança técnica que já tem a um canal de comunicação rápido e transparente.

. Objetivo

Reduzir o tempo de permanência do veículo no pátio e aliviar a recepção e os mecânicos, oferecendo ao cliente um canal único para acompanhar o serviço e aprovar orçamentos.

. Funcionalidades

| Funcionalidade | O que resolve |
|---|---|
| Canal de conversa por veículo / ordem de serviço | Centraliza toda a comunicação em um só lugar |
| Status do conserto em tempo real | O cliente deixa de ligar para saber se o carro está pronto |
| Envio de fotos das peças com defeito | Transparência e confiança, sem interromper o mecânico para explicar por telefone |
| Aprovação ou recusa de orçamento com um clique | Elimina a espera por ligação e libera o carro mais rápido |
| Histórico por veículo | Tudo fica registrado, sem depender de papel |

. Justificativa da solução

Optei por um **módulo de comunicação em formato de chat (web app)**, e não por um site institucional ou um dashboard interno, pelos motivos abaixo:

- A dor está na **comunicação**, e não na falta de divulgação da oficina. Por isso um site institucional não resolveria.
- O cliente já está acostumado a conversar por mensagens, então a adoção é natural e dispensa treinamento.
- Funciona direto no navegador do celular, sem instalar nada.
- A conversa fica ligada a cada veículo, o que dá contexto e histórico.


. Arquitetura

Nesta entrega o projeto é um **protótipo front-end estático**, sem back-end e sem banco de dados, que demonstra o fluxo de comunicação e as telas.

- **HTML5:** estrutura das telas.
- **CSS3:** estilo e layout responsivo.

**Evolução prevista (fora do escopo desta entrega):** back-end com API e banco de dados, autenticação de clientes e equipe, upload de fotos e notificações (WhatsApp ou e-mail) quando houver atualização de status.
