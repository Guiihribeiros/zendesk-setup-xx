# 01 - Caixas do Zendesk

Esta pasta documenta as caixas criadas no Zendesk, detalhando fluxos de atendimento, campos de tickets, grupos, níveis de suporte e SLAs.

---

## 📂 Caixas Criadas

### 1️⃣ Help Desk
- **Finalidade:** Suporte técnico interno para funcionários e colaboradores.
- **E-mail de entrada:** helpdesk@empresa.com.br
- **Fluxo de atendimento:**
  - Todo e-mail enviado para o endereço acima é transformado automaticamente em ticket e atribuído ao **grupo Help Desk**.
  - Dentro do grupo, os tickets são organizados por **categorias de atendimento**:
    - N1
    - N2 - Front Office
    - N2 - Back Office
    - N3
- **Campos de preenchimento do ticket:**
  - Assunto
  - Atribuído para
  - Categoria
  - Descrição
  - Grupo
  - Impacto
  - Nível de suporte
  - Prioridade
  - Tipo
- **SLA por nível de atendimento:**  
  - Baixo, Normal, Alta, Urgente

- **Visualizações de tickets criadas:**
  - Meus tickets (tickets atribuídos ao atendente)
  - Tickets do Help Desk
  - Tickets pendentes Help Desk
  - Tickets sem atribuição
  - SLA próximo do vencimento
  - SLA vencido

---

### 2️⃣ Ouvidoria
- **Finalidade:** Atendimento externo para feedbacks, sugestões e reclamações.
- **E-mail de entrada:** ouvidoria@empresa.com.br
- **Fluxo de atendimento:**
  - Todo e-mail enviado para ouvidoria@empresa.com.br é transformado em ticket e atribuído ao **grupo Ouvidoria**.
- **Campos de preenchimento do ticket:**
  - Assunto
  - Nome do solicitante
  - Descrição da solicitação
  - E-mail de contato
  - Prioridade
  - Deseja retorno
- **SLA por nível de atendimento:**  
  - Baixo, Normal, Alta, Urgente

- **Visualizações de tickets criadas:**  
  - Mesmo padrão do Help Desk: Meus tickets, Tickets do grupo, Pendentes, Sem atribuição, SLA próximo do vencimento e SLA vencido.

---

## ⚡ Observações
- Cada caixa possui regras de SLA específicas conforme prioridade e nível de atendimento.
- Visualizações são segmentadas para que cada grupo veja apenas os tickets relevantes.
- Revisar periodicamente campos, fluxos e automações para garantir eficiência.
