Exercicios de tratamento de exceções em Java. Base de Estudos - DevSuperior

Roteiro
* Estudo de caso: Saque em conta bancária
* Conceito
* Delegação das Exceções
* Manutenção / código limpo
* Soluções
*   1 - Tudo no progama principal
*   2 - Função "Gambiarra"
*   3 - Exceções - Foco principal
  
------------------------  EXERCÍCIO ------------------------
Fazer um programa para ler os dados de uma conta bancária e depois
realizar um saque nesta conta bancária, mostrando o novo saldo. Um
saque não pode ocorrer ou se não houver saldo na conta, ou se o valor
do saque for superior ao limite de saque da conta. Implemente a conta
bancária conforme projeto abaixo.

------------------------------------------------
                    ACCOUNT
------------------------------------------------
- number: Integer
- holder: String
- balance: Double
- withdrawLimit: Double
------------------------------------------------
+ deposit(amount: Double) : void
+ withdraw(amount: Double) : void
------------------------------------------------

#JAVA 
