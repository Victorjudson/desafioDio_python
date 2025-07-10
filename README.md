# Sistema Bancário Simples em Python

Um sistema bancário básico para terminal, que permite criar usuários e contas, fazer depósitos, saques, visualizar extratos e listar usuários cadastrados.

---

## Funcionalidades

- Criar usuário com CPF, nome completo, data de nascimento e endereço
- Criar conta vinculada a um usuário existente
- Depositar valores na conta
- Realizar saques com limite diário e número máximo de saques
- Exibir extrato detalhado com movimentações e saldo atual
- Listar todos os usuários cadastrados
- Sair do sistema

---

## Como usar

1. Execute o script Python:

```bash
python nome_do_arquivo.py

No menu, escolha a opção desejada digitando a sigla correspondente:

Opção	Descrição
d	Depositar
s	Sacar
e	Exibir extrato
nu	Criar novo usuário
cc	Criar nova conta
lu	Listar usuários
q	Sair do sistema

Siga as instruções que aparecerão na tela para cada operação.

Exemplo de uso
ruby
Copiar
Editar
Informe o CPF (somente números): 12345678900
Informe o nome completo: João Silva
Informe a data de nascimento (dd-mm-aaaa): 01-01-1990
Informe o endereço (logradouro, número - bairro - cidade/sigla estado): Rua A, 100 - Centro - SP/SP
Usuário criado com sucesso!

Informe o CPF do usuário: 12345678900
Usuário encontrado, criando conta...
Conta criada com sucesso! Número da conta: 1

Informe o valor do depósito: 500
Depósito realizado com sucesso! Saldo atual: R$ 500.00

Informe o valor do saque: 100
Saque realizado com sucesso! Saldo atual: R$ 400.00

================ EXTRATO ================
Depósito: R$ 500.00
Saque: R$ 100.00

Saldo: R$ 400.00
=======================================
