---
title: Aprovar Recibos
layout: home
nav_order: 5
parent: Negócios
has_toc: false
---

## **Tela de Aprovar Recibos**

## Requisitos de Acesso
- **Somente administradores** têm permissão para acessar esta tela.

A tela de Aprovar Recibos permite gerenciar os pagamentos realizados, exibindo os recibos pendentes para aprovação. Abaixo, segue o fluxo detalhado:

---

### **Fluxo de Aprovação de Recibos**
1. Quando um pagamento é realizado, ele aparece na tela de Aprovar Recibos com o status **Pendente**.
2. As ações disponíveis para cada recibo são:
   - **Aprovar**: Aceita o recibo, alterando o status para **Aprovado**.
   - **Rejeitar**: Recusa o recibo, alterando o status para **Recusado**.
   - **Visualizar**: Permite visualizar o comprovante de pagamento.

---

### **Comportamento por Status**
- **Recibos Recusados**:
  - Apenas a opção de **Visualizar Comprovante** estará disponível.
- **Recibos Aprovados**:
  - Será possível **Visualizar o Comprovante** e **Visualizar o Recibo**.

---

### **Colunas da Tabela**
A tabela de recibos exibe as seguintes informações:

- **Código do Recibo**: Identificador único do recibo.
- **Nome do Cliente**: Nome do cliente associado ao recibo.
- **Data de Solicitação**: Data em que o recibo foi solicitado.
- **Total**: Valor total da negociação.
- **Total Pago**: Valor total pago pelo cliente.
- **Valor do Recibo**: Valor específico do recibo.
- **Responsável**: Nome do responsável por criar o recibo.
- **Status**: Status atual do recibo (Pendente, Aprovado, Recusado).
- **Ações**: Botões para aprovar, rejeitar ou visualizar o recibo.

---

### **Detalhes do Recibo e Cliente**
- Ao clicar no **Nome do Cliente**, será exibida uma página com as informações detalhadas do recibo e do cliente, incluindo:
  - Dados do cliente.
  - Informações do recibo.
  - Histórico de pagamentos relacionados.

---

### Observação
Certifique-se de revisar todas as informações antes de aprovar ou rejeitar um recibo. Recibos aprovados ou rejeitados não podem ser editados posteriormente.

---

### Exemplos Visuais
- **Tabela de Recibos**:

  ![Imagem da tabela de recibos]({{"/assets/images/approveReceipt/image.png" | relative_url }})

- **Ações Disponíveis**:

  ![Imagem das ações de aprovação e rejeição]({{"/assets/images/approveReceipt/image1.png" | relative_url }})

- **Detalhes do Recibo e Cliente**:

  ![Imagem dos detalhes do recibo e cliente]({{"/assets/images/approveReceipt/image2.png" | relative_url }})