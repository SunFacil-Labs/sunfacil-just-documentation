---
title: Agendas
layout: home
nav_order: 6
parent: Funcionalidades
has_toc: false
---

## **Tela de Agendas**

A tela de Agendas permite gerenciar os agendamentos de usuários, com funcionalidades específicas para administradores, pré-vendas e pós-vendas. Abaixo, segue o fluxo detalhado:

---

### **Agenda do Administrador**
Usuários com perfil de **Administrador** ou **Pré-venda** possuem acesso à agenda administrativa, onde é possível adicionar agendamentos para outros usuários.

#### **Adicionar Novo Agendamento**
Para adicionar um novo agendamento, preencha os seguintes campos:

1. **Data**: Informe a data do agendamento.  
2. **Horário**: Informe o horário do agendamento.  
3. **Código de Negócio**: Insira o código da negociação.  
   - **Regras**:  
     - O código de negócio não pode já estar associado a outro agendamento.  
     - A negociação deve pertencer ao usuário para quem o agendamento será adicionado.  
4. **Tipo**: Selecione o tipo de agendamento.  
5. **Descrição**: Insira uma descrição detalhada do agendamento.  

Após preencher os campos, clique no botão **Salvar** para criar o agendamento.

---

### **Dashboard de Agendas**
A tela exibe um painel com as seguintes informações:

- **Agendamentos**:  
  - **Em Aberto**: Total de agendamentos pendentes.  
  - **Concluídos**: Total de agendamentos finalizados.  
  - **Atrasados**: Total de agendamentos atrasados.  
  - **Perdidos**: Total de agendamentos perdidos.  

- **Calendário**:  
  - Exibe os agendamentos no formato de calendário.  
  - Ao clicar em um dia, são exibidos os agendamentos do dia e os detalhes do evento.  

- **Próximos Agendamentos**:  
  - Lista os próximos agendamentos com informações resumidas.  

- **Tabela de Agendamentos**:  
  - Exibe todos os agendamentos, incluindo:  
    - **Próximos Agendamentos**  
    - **Histórico de Agendamentos**  
    - **Agendamentos Atrasados**  

---

### **Agenda do Vendedor e Pós-vendas**
Usuários com perfil de **Vendedor** ou **Pós-vendas** possuem acesso à sua própria agenda, com as seguintes funcionalidades:

#### **Calendário Pessoal**
- Exibe apenas os agendamentos do próprio usuário.  
- Ao clicar em um dia no calendário, são exibidos os agendamentos do dia com detalhes, como:  
  - **Exemplo**:  
    - **Visita** - Agendado para o cliente **Socorro Queiroz**  
      - **Data**: 09/05/2025  
      - **Horário**: 08:30  
      - **Responsável**: LiLian Maria 
      - **Status**: Atrasado  
      - Botão **Ver Detalhes**: Permite visualizar mais informações e marcar o agendamento como **Concluído**.

#### **Próximos Agendamentos**
- Lista os próximos agendamentos do usuário, com status e botão para **Ver Detalhes**.

#### **Horários Bloqueados**
- Exibe os bloqueios de horários do usuário, divididos em:  
  - **Bloqueios de Hoje**  
  - **Próximos Bloqueios**  

#### **Gerenciar Bloqueios**
- Permite adicionar novos bloqueios de horário.  
- Para criar um bloqueio, preencha os seguintes campos:  
  1. **Data**: Informe a data do bloqueio.  
  2. **Intervalo de Horário**: Informe o intervalo de horário a ser bloqueado.  
  3. **Motivo**: Selecione o motivo do bloqueio.  
  4. **Descrição**: Insira uma descrição detalhada do bloqueio.  

Após criar o bloqueio, ele será listado em **Próximos Bloqueios** dentro do mesmo bloco, onde também será possível excluir o bloqueio.

---

### Observação
Certifique-se de seguir as regras de agendamento e bloqueio para evitar conflitos. Apenas administradores e pré-vendas podem adicionar agendamentos para outros usuários.

---

### Exemplos Visuais
- **Adicionar Novo Agendamento**:  
  ![Imagem do formulário de adicionar agendamento]({{"/assets/images/scheduler/image.png" | relative_url }})

- **Dashboard de Agendas**:  
  ![Imagem do dashboard de agendas]({{"/assets/images/scheduler/image1.png" | relative_url }})

- **Gerenciar Bloqueios**:  
  ![Imagem do modal de gerenciar bloqueios]({{"/assets/images/scheduler/image2.png" | relative_url }})
    ![Imagem do modal de gerenciar bloqueios]({{"/assets/images/scheduler/image3.png" | relative_url }})

    - **Tela de Usuário Comum**

    ![Imagem do modal de gerenciar bloqueios]({{"/assets/images/scheduler/image4.png" | relative_url }})
