# Sistema Bancário

---

## Desafio:

Desenvolver um sistema bancário contendo apenas 3 operações: depósito, saque e extrato.

- *Operação de depósito:* Deve ser possível depositar valores positivos. A v1 do projeto trabalha apenas com 1 usuário, dessa forma não precisamos nos precupar em identificar qual é o número da agência e conta bancária. Todos os depósitos devem ser armazenados em uma variável e exibidos na operação de extrato.

- *Operação de Saque:* O sistema deve permitir 3 saques diários com limite máximo de R$ 500,00 por saque. Caso o usuário não tenha saldo em conta, o sistema deve exibir uma mensagem informando que não será possível sacar o dinheiro por falta de saldo. todos os saques devem ser armazenados em uma variável e exibidos na operação de extrato.

- *Operação de Extrato:* Essa operação deve listar todos os depósitos e saques realizados na conta. No fim da listagem deve ser exibido o saldo atual da conta. <br>
Os valores devem ser exibidos utilizando o formato R$ xxx.xx, exemplo: <br>
1500.45 = R$ 1500.45
