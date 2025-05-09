---
title: Clientes
layout: home
nav_order: 4
parent: Funcionalidades
has_toc: false
---

## **Tela de Clientes**

A tela de Clientes permite gerenciar os clientes cadastrados no sistema. Abaixo, segue o fluxo detalhado:

---

### **Adicionar Cliente**
Para adicionar um cliente, preencha os seguintes campos no modal de cadastro:

1. **Tipo de Cliente**:  
   - Selecione o tipo de cliente (ex.: Pessoa Física ou Jurídica).

2. **Informações do Cliente**:  
   - **Nome**: Nome do cliente.  
   - **Nome do Contato**: Nome do contato principal.  
   - **CPF/CNPJ**: Documento de identificação do cliente.  
   - **Telefone**: Número de telefone do cliente.  
   - **E-mail**: Endereço de e-mail do cliente.  

3. **Endereço**:  
   - **Estado**: Selecione o estado.  
   - **Cidade**: Selecione a cidade.  
   - **Bairro**: Informe o bairro.  
   - **Rua**: Informe a rua.  
   - **Número**: Número do endereço.  
   - **Complemento**: Informações adicionais sobre o endereço.  
   - **CEP**: Código postal do endereço.  

4. **Outras Informações**:  
   - **Data de Nascimento**: Informe a data de nascimento do cliente, se aplicável.  

5. Após preencher todos os campos, clique no botão **Salvar** para adicionar o cliente ao sistema.

---

### **Editar Cliente**
- O modal de edição possui os mesmos campos do modal de adicionar cliente.  
- Para editar um cliente, clique nos **três pontinhos** na coluna de ações da tabela e selecione a opção **Editar**.

---

### **Adicionar Clientes em Massa**
- É possível adicionar clientes em massa utilizando uma planilha.  
- Para isso, siga os passos abaixo:
  1. Baixe o modelo de planilha disponível na tela.  
  2. Preencha a planilha com as informações dos clientes.  
  3. Faça o upload da planilha no sistema para cadastrar os clientes em massa.  
- **Observação**: Apenas administradores têm permissão para realizar o cadastro em massa.

---

### **Tabela de Clientes**
Os clientes cadastrados são exibidos em uma tabela com as seguintes colunas:

- **Código**: Identificador único do cliente.  
- **Nome**: Nome do cliente.  
- **E-mail**: Endereço de e-mail do cliente.  
- **Telefone**: Número de telefone do cliente.  
- **Status**: Status atual do cliente (ex.: Ativo, Inativo).  
- **Status da Negociação**: Status da negociação correspondente ao cliente (ex.: Pendente, Cancelado, Finalizado, Rejeitado).  
- **Ações**: Botões para gerenciar o cliente, como editar.

---

### **Criar Negociação**
- Para perfis de **Pré-venda**, quando o **Status da Negociação** for diferente de **Pendente** (ex.: Cancelado, Finalizado, Rejeitado), será exibido o botão **Criar Negociação**.  
- Este botão que fica nos **três pontinhos** permite criar uma nova negociação para o cliente.  
- O fluxo de criação de negociação é o mesmo descrito na [página de Leads](../leads/#criar-negociação).

---

### Observação
Certifique-se de preencher todos os campos obrigatórios ao adicionar ou editar um cliente. Para o cadastro em massa, utilize exclusivamente o modelo de planilha fornecido pelo sistema.

---

### Exemplos Visuais
- **Adicionar Cliente**:  
  ![Imagem do formulário de adicionar cliente]({{"/assets/images/customers/image.png" | relative_url }})

- **Tabela de Clientes**:  
  ![Imagem da tabela de clientes]({{"/assets/images/customers/image1.png" | relative_url }})

- **Criar Negociação**:  
  ![Imagem do botão de criar negociação]({{"/assets/images/customers/image2.png" | relative_url }})
