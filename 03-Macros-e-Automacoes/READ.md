# 03 - Macros e Automações do Zendesk

Esta pasta documenta as macros, triggers e automações configuradas no Zendesk, detalhando objetivos, regras e funcionamento.

---

## 📂 Regras de Criação de Tickets via E-mail
- **Help Desk:**  
  - E-mails enviados para `helpdesk@empresa.com.br` geram tickets automaticamente no grupo **Help Desk**.
  - Tickets recebidos são atribuídos diretamente ao **N1** para triagem inicial.

- **Ouvidoria:**  
  - E-mails enviados para `ouvidoria@empresa.com.br` geram tickets automaticamente no grupo **Ouvidoria**.
  - Todos os tickets recebidos recebem **prioridade Alta** por padrão.

---

## 📂 Triggers e Alertas

- **SLA próximo do vencimento**
  - Condição: Ticket com SLA prestes a expirar
  - Ação: Enviar alerta por e-mail para o **agente responsável** pelo ticket

- **SLA vencido**
  - Condição: SLA expirado
  - Ação: Enviar alerta por e-mail para o **responsável geral**

---

## 📂 Configurações de SLA
- O **tempo de SLA** é contado apenas durante o **período de funcionamento da empresa**.
- Prioridades:
  - Tickets Help Desk: seguem SLA normal por nível de atendimento (N1, N2, N3)
  - Tickets Ouvidoria: prioridade Alta por padrão

---

## ⚡ Observações
- Atribuição automática ao N1 garante que todos os tickets passem por triagem antes de escalar para N2 ou N3.
- Alertas de SLA permitem acompanhamento proativo de tickets e prevenção de atrasos.
- Revisão periódica das automações e triggers é recomendada para manter a eficiência do atendimento.
