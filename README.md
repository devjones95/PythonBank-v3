1. Classes principais
Cliente: Representa um cliente do banco, com endereço e uma lista de contas associadas.
PessoaFisica: Herda de Cliente e adiciona atributos específicos como nome, data de nascimento e CPF.
Conta: Representa uma conta bancária, com saldo, número, agência, cliente associado e um histórico de transações.
ContaCorrente: Especialização de Conta, adicionando um limite de saque e um número máximo de saques permitidos.
Historico: Guarda as transações feitas na conta.
Transacao (ABC): Classe abstrata para operações bancárias (Saque e Depósito).
Saque: Implementa a operação de saque.
Deposito: Implementa a operação de depósito.
2. Funcionalidades do sistema
menu(): Exibe as opções disponíveis para o usuário.
filtrar_cliente(): Busca um cliente pelo CPF.
recuperar_conta_cliente(): Retorna a primeira conta associada ao cliente.
depositar(): Realiza um depósito na conta do cliente.
sacar(): Realiza um saque, verificando saldo e limites da conta.
exibir_extrato(): Exibe as transações realizadas na conta.
criar_cliente(): Cadastra um novo cliente.
criar_conta(): Cria uma nova conta corrente associada a um cliente.
listar_contas(): Lista todas as contas registradas no sistema.
3. main()
Controla o loop do programa, permitindo que o usuário escolha opções no menu até decidir sair (q).
