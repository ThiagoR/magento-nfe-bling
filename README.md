Módulo desenvolvido pela Lema21 para integrar com o sistema do Bling e gerar notas fiscais.

Após a instalação do módulo, serão criados os seguintes atributos de produto:

- codigo_origem (codigo de origem do produto). Ex: 0, 1, 2, etc.
- opertion_name (espécie de 'nome operacional' do produto)
- operation_unit - unidade de medida, se é "PÇ", "KG"
- codigo_ncm - Código NCM do produto

Melhorias no módulo:

- incluída opção para emissão de Nf-e em massa para pedidos;
- incluída opção para permitir a emissão de Nf-e por estado do(s) pedidos;
- validação para produtos que não possuem os atributos requeridos
- alteração das mensagens de sucesso e erro para exibir o número de incrementId do objeto order;
- inclusão automática dos atributos de nfe no grupo default do magento como não obrigatórios
- Retirado validações desnecessárias.
- Alteração na nomenclatura dos rótulos da guia Nf-e em produtos.
- Adicionado tipo de integração e numero pedido loja.
- Adição da seleção automática do serviços dos correios.
- Adicionado validação do tipo de pessoa.
- Inclusão de desconto total do pedido.
