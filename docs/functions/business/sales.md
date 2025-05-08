---
title: Vendas
layout: home
nav_order: 4
parent: Negócios
has_toc: false
---


## **Vendas**

### Informações das Vendas
A tela de vendas exibe todas as vendas geradas a partir de propostas aceitas. A tabela de vendas contém as seguintes informações para cada linha:  
- **Código da Venda:** Identificador único da venda.  
- **Código da Negociação:** Código da negociação à qual a venda pertence.  
- **Código da Proposta:** Código da proposta que gerou a venda.  
- **Valor Total da Venda:** Exemplo: R$ 10.000,00.  
- **Valor Pago:** Valor já pago da venda.  
- **Status:** Exemplo: Pendente, Parcial, Concluído.  

![Exemplo de tabela de vendas]({{"/assets/images/salesImage/image1.png" | relative_url }})

### Detalhes da Venda
Ao clicar no código da venda, os detalhes da venda são exibidos, incluindo:

#### Produtos
- **Nome:** Nome do produto.  
- **Preço Unitário:** Valor unitário do produto.  
- **Quantidade:** Quantidade adquirida.  
- **Valor Total:** Valor total do produto (preço unitário x quantidade).  

#### Pagamentos
- **Forma de Pagamento:** Exemplo: Cartão, Boleto, Transferência.  
- **Valor:** Valor do pagamento.  
- **Data:** Data do pagamento.  
- **Data de Aprovação/Rejeição:** Exibida quando o pagamento for aprovado ou rejeitado.  
- **Status:** Exemplo: Pendente, Aprovado, Rejeitado.  

Na seção de pagamentos, há uma engrenagem que, ao ser clicada, exibe as seguintes opções:  
- **Visualizar Recibo:** Exibe o recibo do pagamento.  
- **Aprovar Pagamento:** Aprova o pagamento pendente.  
- **Rejeitar Pagamento:** Rejeita o pagamento pendente.  

![Exemplo de detalhes da venda]({{"/assets/images/salesImage/image2.png" | relative_url }})

### Ações Disponíveis
Na parte superior, logo após o título, há uma engrenagem com as seguintes opções:  
- **Visualizar Contrato:** Exibe o contrato do negócio fechado.  
- **Finalizar Venda:** Disponível apenas para o administrador, permite finalizar a venda caso o valor total seja igual ao valor pago.  
- **Adicionar Pagamento:** Disponível apenas para o vendedor responsável pela venda, permite adicionar um novo pagamento.  

![Exemplo de ações disponíveis]({{"/assets/images/salesImage/image3.png" | relative_url }})

### Informações Adicionais
Na parte inferior da tela, são exibidas as seguintes informações:  
- **Informações da Proposta:** Detalhes da proposta que gerou a venda.  
- **Informações do Cliente:** Dados do cliente relacionados à venda.  

![Exemplo de informações adicionais]({{"/assets/images/salesImage/image4.png" | relative_url }})

---

### Observação
Certifique-se de que todas as permissões estão configuradas corretamente:  
- Apenas o vendedor responsável pode adicionar pagamentos.  
- Apenas o administrador pode finalizar a venda.  
