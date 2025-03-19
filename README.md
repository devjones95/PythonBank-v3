<h2>A versão final do nosso sistema bancário Python, dessa vez, com as funções, e a Programação Orientada à Objetos foi adicionada.</h2><br>

<h3>Explicando como o sistema funciona:</h3><br>

<h4>1. Classes principais</h4><br>
<ul>
  <li>Cliente: Representa um cliente do banco, com endereço e uma lista de contas associadas.</li>
  <li>PessoaFisica: Herda de Cliente e adiciona atributos específicos como nome, data de nascimento e CPF.</li>
  <li>Conta: Representa uma conta bancária, com saldo, número, agência, cliente associado e um histórico de transações.</li>
  <li>ContaCorrente: Especialização de Conta, adicionando um limite de saque e um número máximo de saques permitidos.</li>
  <li>Historico: Guarda as transações feitas na conta.</li>
  <li>Transacao (ABC): Classe abstrata para operações bancárias (Saque e Depósito).</li>
  <li>Saque: Implementa a operação de saque.</li>
  <li>Deposito: Implementa a operação de depósito.</li>
</ul><br>

<h4>2. Funcionalidades do sistema</h4><br>

<ul>
  <li>menu(): Exibe as opções disponíveis para o usuário.</li>
  <li>filtrar_cliente(): Busca um cliente pelo CPF.</li>
  <li>recuperar_conta_cliente(): Retorna a primeira conta associada ao cliente.</li>
  <li>depositar(): Realiza um depósito na conta do cliente.</li>
  <li>sacar(): Realiza um saque, verificando saldo e limites da conta.</li>
  <li>exibir_extrato(): Exibe as transações realizadas na conta.</li>
  <li>criar_cliente(): Cadastra um novo cliente.</li>
  <li>criar_conta(): Cria uma nova conta corrente associada a um cliente.</li>
  <li>listar_contas(): Lista todas as contas registradas no sistema.</li>
</ul><br>

<h4>3. main()</h4><br>
<p>Controla o loop do programa, permitindo que o usuário escolha opções no menu até decidir sair (q).</p>
