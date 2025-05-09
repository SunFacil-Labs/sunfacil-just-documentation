---
title: Produtos
layout: home
nav_order: 4
parent: Funcionalidades
has_toc: false
---

## **Tela de Produtos**

### **Requisitos de Acesso**
- **Somente administradores** têm permissão para acessar esta tela.

A tela de Produtos permite gerenciar os produtos cadastrados no sistema. Abaixo, segue o fluxo detalhado:

---

### **Adicionar Novo Produto**
Para adicionar um novo produto, preencha os seguintes campos:

1. **Imagem**:  
   - Clique no botão **Enviar** para adicionar uma imagem do produto.

2. **Informações do Produto**:  
   - **Nome**: Nome do produto.  
   - **Código**: Código identificador do produto.  
   - **Marca**: Marca do produto.  
   - **Modelo**: Modelo do produto.  
   - **Estrutura**: Selecione a estrutura do produto.  
   - **Unidade de Medida**: Selecione a unidade de medida.  
   - **Potência do Kit**: Informe a potência do kit, se aplicável.  
   - **Potência do Módulo**: Informe a potência do módulo, se aplicável.  
   - **Descrição**: Descrição detalhada do produto.  
   - **Observação**: Observações adicionais sobre o produto.  
   - **Valor de Compra**: Preço de compra do produto.  
   - **Valor de Venda**: Preço de venda do produto.  

3. Após preencher todos os campos, clique no botão **Salvar** para adicionar o produto ao sistema.

---

### **Adicionar Produtos em Lotes**
- É possível adicionar produtos em lote utilizando uma planilha.  
- Para isso, siga os passos abaixo:
  1. Baixe o modelo de planilha disponível na tela.  
  2. Preencha a planilha com as informações dos produtos.  
  3. Faça o upload da planilha no sistema para cadastrar os produtos em lote.

---

### **Tabela de Produtos**
Os produtos cadastrados são exibidos em uma tabela com as seguintes colunas:

- **ID**: Identificador único do produto.  
- **Nome**: Nome do produto.  
- **Código do Produto**: Código identificador do produto.  
- **Marca**: Marca do produto.  
- **Modelo**: Modelo do produto.  
- **Preço de Venda**: Valor de venda do produto.  
- **Preço de Compra**: Valor de compra do produto.  
- **Status**: Status atual do produto (ex.: Ativo, Inativo).  
- **Ações**: Botões para gerenciar o produto.

---

### **Editar Produto**
- Na tabela, clique nos **três pontinhos** na coluna de ações para editar um produto.  
- Será aberta uma tela onde é possível alterar as informações do produto cadastrado.

---

### Observação
Certifique-se de preencher todos os campos obrigatórios ao adicionar ou editar um produto. Para o cadastro em lote, utilize exclusivamente o modelo de planilha fornecido pelo sistema.

---

### Exemplos Visuais
- **Adicionar Produto**:  
  ![Imagem do formulário de adicionar produto]({{"/assets/images/products/image.png" | relative_url }})

- **Tabela de Produtos**:  
  ![Imagem da tabela de produtos]({{"/assets/images/products/image1.png" | relative_url }})

- **Editar Produto**:  
  ![Imagem da tela de edição de produto]({{"/assets/images/products/image2.png" | relative_url }})