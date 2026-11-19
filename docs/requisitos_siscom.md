Requisitos Funcionais
RF01 — Cadastrar produtos.
RF02 — Consultar produtos.
RF03 — Alterar informações dos produtos.
RF04 — Excluir ou inativar produtos.
RF05 — Cadastrar categorias.
RF06 — Cadastrar fornecedores.
RF07 — Registrar entradas e saídas de estoque.
RF08 — Consultar movimentações do estoque.

Requisitos não Funcionais
RNF01 — Os dados deverão ser armazenados em um banco MySQL.
RNF02 — O sistema deverá ser executado em computadores com Windows.
RNF03 — As mensagens de erro deverão ser compreensíveis para o usuário.
RNF04 — O código deverá ser organizado em módulos.
RNF05 — O acesso às funcionalidades administrativas deverá exigir autenticação, caso essa funcionalidade seja incluída no escopo.

Regras de Negócio
RN01 — O nome do produto não pode ficar vazio.
RN02 — O preço de venda deve ser maior que zero.
RN03 — A quantidade em estoque não pode ser negativa.
RN04 — Uma saída não pode retirar mais unidades do que existem disponíveis.
RN05 — Toda movimentação deve estar associada a um produto.
RN06 — Uma entrada deve aumentar o estoque e uma saída deve diminuí-lo.
Quem utilizará o sistema?
 
Administrador
Gerencia cadastros.
Consulta informações.
Acompanha o estoque.
Realiza atividades administrativas.

Operador
Consulta produtos.
Registra movimentações.
Atualiza informações conforme suas permissões.