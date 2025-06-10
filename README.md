# Calculadora Virtual 🔢

Uma calculadora simples feita em Shell Script e Python, com entrada de dois números e um operador.


## 🟢 Como Executar o Script `calculadora.sh`

1. Abra o terminal.
2. Navegue até a pasta onde está o arquivo `calculadora.sh`.
3. Execute os comandos abaixo, **um de cada vez**:

```bash
chmod +x calculadora.sh  #(pressione Enter)
./calculadora.sh	 #(pressione Enter)
```

- O primeiro comando dá permissão de execução ao script.
- O segundo comando executa o script no terminal.

## 🟢 Instruções de Uso da Calculadora:

1. Digite o primeiro número.

2. Digite o segundo número.

3. Digite o operador desejado: +, -, *, /.

## ➕ Operadores Disponíveis:

(+) Soma                  ->(Python + sh.)

(-) Subtração             ->(Python + sh.)

(*) Multiplicação         ->(Python + sh.)

(/) Divisão               ->(Python + sh.)

(**) Exponenciação        ->(Python)

(%) Resto da divisão      ->(Python)

## 🐍 Explicação do código Python (calculadora.py)

O código em Python é responsável por realizar os cálculos com base nos valores fornecidos pelo usuário.

## 📚 Estrutura Geral:

```bash
nome = input('Como podemos te chamar? 🤔 ')
print('Olá, ' + nome + ', seja bem vindo a nossa calculadora virtual 😁')
while True:
  inicio = input('Deseja seguir com os calculos? (sim/não)')
  if inicio.lower() != 'sim':
    break
  primeiro_valor = float(input('Digite aqui o primeiro valor desejado:'))
  operador = input('Agora digite um dos operador desejado (+,-,*,/,**,%):')
  segundo_valor = float(input('Por fim o ultimo valor desejado:'))
  if operador == '+':
    print(primeiro_valor + segundo_valor)
  elif operador == '-':
    print(primeiro_valor - segundo_valor)
  elif operador == '*':
    print(primeiro_valor * segundo_valor)
  elif operador == '/':
    print(primeiro_valor / segundo_valor)
  elif operador == '**':
    print(primeiro_valor ** segundo_valor)
  elif operador == '%':
    print(primeiro_valor % segundo_valor)
  else:
    print('Operador inválido')
```

## ⁉ O que o código faz:

- Recebe três argumentos: número 1, número 2 e operador.

- Converte os valores em números reais (float).

- Verifica qual operação realizar com base no operador fornecido.

- Imprime o resultado diretamente no terminal.
