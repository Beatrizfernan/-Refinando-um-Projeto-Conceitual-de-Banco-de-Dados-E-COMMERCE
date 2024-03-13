

Modelo Conceitual de Banco de Dados para E-commerce Refinado
Este repositório contém um modelo conceitual de banco de dados para um sistema de e-commerce, que foi refinado com base em requisitos específicos do projeto. As adições incluem a introdução de entidades para representar clientes Pessoa Jurídica (PJ) e Pessoa Física (PF), múltiplas formas de pagamento e informações de entrega expandidas.

Alterações Realizadas
Entidades Adicionadas:
ClientePJ e ClientePF: Representam clientes registrados no sistema, distinguindo entre Pessoa Jurídica e Pessoa Física. Uma conta de cliente pode ser associada apenas a um tipo de cliente (PJ ou PF), mas não ambos.

Pagamento: Representa as diferentes formas de pagamento disponíveis para os clientes. Um cliente pode ter cadastrado mais de uma forma de pagamento.

Entrega: Representa informações relacionadas à entrega de pedidos, incluindo status e código de rastreamento.

Relacionamentos Adicionados:
Cliente-Pagamento: Relacionamento muitos-para-muitos entre cliente e formas de pagamento, permitindo que um cliente tenha múltiplas formas de pagamento cadastradas.

Pedido-Entrega: Relacionamento um-para-um entre pedido e informações de entrega, permitindo que cada pedido tenha informações específicas de entrega associadas.

Diagrama de Banco de Dados At
