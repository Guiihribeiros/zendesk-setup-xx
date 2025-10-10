# 03 - Macros e Automações do Zendesk

Esta pasta documenta as macros, triggers e automações configuradas no Zendesk, detalhando seus objetivos, regras e funcionamento.

---

## 📂 Macros
Macros são respostas ou ações automáticas aplicadas manualmente em tickets, para agilizar o atendimento.

**Exemplos:**
- **Macro: Resposta inicial Help Desk**
  - Mensagem padrão para tickets recebidos
  - Inclui saudação, instruções iniciais e prazo de resposta
  - Aplicável a tickets N1, N2 e N3
- **Macro: Confirmação de Recebimento Ouvidoria**
  - Mensagem automática de agradecimento
  - Confirma recebimento da solicitação e informa prazo de retorno
- **Macro: Encerramento de ticket**
  - Mensagem padrão para finalizar atendimento
  - Inclui solicitação de feedback (quando aplicável)

---

## 📂 Triggers
Triggers são ações automáticas executadas com base em condições de tickets.

**Exemplos:**
- **Trigger: Atribuição automática**
  - Condição: Ticket recebido em helpdesk@empresa.com.br
  - Ação: Atribuir automaticamente ao grupo Help Desk
- **Trigger: Notificação de SLA**
  - Condição: SLA próximo do vencimento
  - Ação: Enviar alerta para atendente e supervisor
- **Trigger: Prioridade urgente**
  - Condição: Prioridade = Urgente
  - Ação: Notificar administradores e equipe de N3

---

## 📂 Automações
Automações são ações periódicas baseadas em tempo ou status do ticket.

**Exemplos:**
- **Automação: Fechamento automático de tickets inativos**
  - Condição: Ticket sem atualização por X dias
  - Ação: Fechar o ticket e enviar mensagem de encerramento
- **Automação: Lembrete de tickets pendentes**
  - Condição: Ticket em pendência por Y dias
  - Ação: Enviar alerta ao grupo responsável
- **Automação: Escalonamento**
  - Condição: SLA expirado ou prioridade crítica
  - Ação: Escalonar ticket para N2 ou N3

---

## ⚡ Observações
- É importante revisar periodicamente macros, triggers e automações para garantir que estejam alinhadas ao fluxo atual de atendimento.
- Triggers e automações devem ser testadas antes da aplicação em produção para evitar duplicidade ou conflitos de regras.
