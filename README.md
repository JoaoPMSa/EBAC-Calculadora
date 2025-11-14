# 🧮 Calculadora em Python

Este projeto é uma calculadora simples desenvolvida em **Python** que permite ao usuário realizar operações matemáticas básicas: **adição, subtração, multiplicação e divisão**.

## 📌 Como funciona

1. O programa solicita ao usuário dois números (`num1` e `num2`).
2. Em seguida, exibe um menu com as opções de operação:
   - `1` ➝ Adição (+)  
   - `2` ➝ Subtração (-)  
   - `3` ➝ Multiplicação (*)  
   - `4` ➝ Divisão (/)
3. O usuário escolhe a operação digitando o número correspondente.
4. O programa executa a operação escolhida e mostra o resultado.

## ⚙️ Estrutura do código

- **Entrada de dados**  
  ```python
  num1 = float(input("Digite o primeiro número: "))
  num2 = float(input("Digite o segundo número: "))
  ```
  
O usuário digita dois números, que são convertidos para float para permitir cálculos com decimais.

## - Menu de operações

```python
print("Escolha a operação:")
print("1 - Adição (+)")
print("2 - Subtração (-)")
print("3 - Multiplicação (*)")
print("4 - Divisão (/)")
```

- Exibe as opções disponíveis.
- Escolha da operação:

   ```python
  operacao = input("Digite o número da operação desejada: ")
   ```

- O usuário informa qual operação deseja realizar.
  
- Execução da operação:
    - O programa usa estruturas condicionais (if, elif, else) para verificar a escolha e calcular:
    - Adição: num1 + num2
    - Subtração: num1 - num2
    - Multiplicação: num1 * num2
    - Divisão: num1 / num2 (com verificação para evitar divisão por zero)
  
- Tratamento de erros:  
     Caso o usuário escolha uma opção inválida ou tente dividir por zero,  
     o programa exibe uma mensagem de erro apropriada.  

## 🚀 Exemplo de uso:

   Digite o primeiro número: 10  
   Digite o segundo número: 5  
   
   Escolha a operação:  
   1 - Adição (+)  
   2 - Subtração (-)  
   3 - Multiplicação (*)  
   4 - Divisão (/)  
   
   Digite o número da operação desejada: 4  
   Resultado: 2.0

## 🎯 Objetivo
  Este projeto tem como objetivo demonstrar conceitos básicos de:- Entrada e saída de dados em Python
  - Estruturas condicionais (if/elif/else)
  - Operações matemáticas simples
  - Tratamento de erros (divisão por zero e opção inválida)
- Operações matemáticas simples
- Tratamento de erros (divisão por zero e opção inválida)


## 🚀 Como executar o Shell Script

1. Abra o terminal no diretório onde está o arquivo `calculadora.sh`.  
2. Digite o comando abaixo para rodar o script:
   ```bash
   ./calculadora.sh
