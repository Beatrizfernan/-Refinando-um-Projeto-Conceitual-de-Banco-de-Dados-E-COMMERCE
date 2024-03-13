Este repositório apresenta um modelo conceitual de banco de dados aprimorado para um sistema de e-commerce. O modelo foi refinado com base em requisitos específicos do projeto, incorporando adições significativas para melhor representar a estrutura e funcionalidades do sistema.

**Alterações Realizadas**

**Entidades Adicionadas:**

- **ClientePJ e ClientePF:** Foram introduzidas entidades distintas para representar clientes, diferenciando entre Pessoa Jurídica e Pessoa Física. Agora, uma conta de cliente pode ser associada exclusivamente a um tipo de cliente (PJ ou PF), proporcionando uma representação mais precisa e flexível dos usuários do sistema.
- **Pagamento:** Uma nova entidade foi introduzida para abranger as diversas formas de pagamento disponíveis para os clientes. Agora, um cliente pode cadastrar múltiplos métodos de pagamento, aumentando a praticidade e adaptabilidade do sistema às preferências dos usuários.
- **Entrega:** Esta entidade foi expandida para incluir informações abrangentes relacionadas à entrega de pedidos, como status e código de rastreamento. Isso permite um controle mais detalhado e eficiente do processo de entrega, aprimorando a experiência do cliente.

**Relacionamentos Adicionados:**

- **Cliente-Pagamento:** Foi estabelecido um relacionamento muitos-para-muitos entre clientes e formas de pagamento. Agora, um cliente pode associar múltiplos métodos de pagamento à sua conta, proporcionando maior conveniência e flexibilidade nas transações.
- **Pedido-Entrega:** Foi implementado um relacionamento um-para-um entre pedidos e informações de entrega. Isso significa que cada pedido pode agora ter informações específicas de entrega associadas, facilitando o rastreamento e gerenciamento dos pedidos pelo sistema.

**Diagrama de Banco de Dados**

Um diagrama visual do banco de dados atualizado está disponível ,fornecendo uma visão geral clara da estrutura e relacionamentos entre as entidades no sistema de e-commerce.

Estas adições e refinamentos visam melhorar a eficiência, flexibilidade e usabilidade do modelo de banco de dados, contribuindo para um sistema de e-commerce mais robusto e capaz de atender às necessidades dos clientes e administradores.
