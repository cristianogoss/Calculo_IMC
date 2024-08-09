# Calculadora de IMC

Este é um projeto simples de uma calculadora de Índice de Massa Corporal (IMC) com uma interface gráfica desenvolvida em Python usando a biblioteca Pyautogui.

## Funcionalidades

- **Interface Gráfica:**
  - Janela principal.
  - Campos de entrada para o peso (em kg) e altura (em metros).
  - Botão para calcular o IMC.
  - Campo para exibir o resultado do IMC.
  - Campo para exibir a categoria do IMC com cores diferentes para cada nível:
    - Muito abaixo do peso
    - Abaixo do peso
    - Peso normal
    - Acima do peso
    - Obesidade I
    - Obesidade II
    - Obesidade III

## Como Usar

1. Certifique-se de ter o Python instalado em seu sistema.
2. Clone este repositório ou baixe os arquivos.
3. Execute o arquivo `calculadora_imc.py` para iniciar a aplicação.
4. Insira seu peso em quilogramas e altura em metros nos campos apropriados.
5. Clique no botão "Calcular IMC" para ver o resultado e a categoria correspondente.

## Exemplo de Uso

- **Peso:** 70 kg
- **Altura:** 1.80 m
- **Resultado:** IMC = 21.60 (Peso normal)

## Requisitos

- Python 3.x
- Pyautogui

## Como Funciona

O IMC é calculado usando a fórmula:

\[ \text{IMC} = \frac{\text{peso}}{\text{altura}^2} \]

Com base no valor do IMC, a categoria é determinada da seguinte forma:

- **Muito abaixo do peso:** IMC < 16
- **Abaixo do peso:** 16 <= IMC < 18.5
- **Peso normal:** 18.5 <= IMC < 25
- **Acima do peso:** 25 <= IMC < 30
- **Obesidade I:** 30 <= IMC < 35
- **Obesidade II:** 35 <= IMC < 40
- **Obesidade III:** IMC >= 40
