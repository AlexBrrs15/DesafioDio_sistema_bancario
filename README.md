# Sistema Bancário com Python

Este programa na linguagem Python simula um sistema bancário simples, permitindo realizar operações de depósito, saque e extrato.

## Funcionalidades

-   **Depósito:** Permite depositar valores positivos na conta.
-   **Saque:** Permite sacar valores da conta, com as seguintes restrições:
    -   O valor do saque não pode exceder o saldo disponível.
    -   O valor do saque não pode exceder o limite de R$ 500 por saque.
    -   O número máximo de saques diários é 3.
-   **Extrato:** Exibe o histórico de depósitos e saques, juntamente com o saldo atual.
-   **Sair:** Encerra o programa.
  
## Detalhes Técnicos

-   O programa utiliza um loop `while True` para manter o menu principal em execução até que o usuário escolha a opção de sair.
-   A variável `saldo` armazena o saldo atual da conta.
-   A variável `limite` define o limite máximo de saque por operação (R$ 500).
-   A variável `extrato` armazena o histórico de depósitos e saques.
-   A variável `numero_saques` controla o número de saques realizados no dia.
-   A constante `LIMITE_SAQUES` define o número máximo de saques diários (3).
-   O programa utiliza condicionais `if`, `elif` e `else` para validar as operações e exibir mensagens apropriadas.
-   O extrato exibe as movimentações formatadas com duas casas decimais (R$ XX.XX).
