# Calculadora de IMC (Índice de Massa Corporal)

Uma aplicação web simples feita em HTML e JavaScript para calcular o IMC (Índice de Massa Corporal) com base no peso e altura informados pelo usuário.

## Sumário

- [Descrição](#descrição)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Usar](#como-usar)
- [Mensagens de Resultado](#mensagens-de-resultado)

---

## Descrição

A **Calculadora de IMC** permite que o usuário informe seu peso e altura, e, com base nesses dados, calcula o IMC e exibe uma mensagem indicativa do estado atual (abaixo do peso, peso ideal, sobrepeso ou obesidade).

Esse projeto tem como objetivo fins educacionais e de demonstração de lógica básica com JavaScript puro (sem bibliotecas externas).

---

## Tecnologias Utilizadas

- HTML5
- JavaScript (Vanilla)

---

## Como Usar

O cálculo é feito com a seguinte fórmula:

IMC = peso / (altura × altura)

O peso deve ser inserido em quilogramas (kg), sendo apenas a primeira casa decimal (ex: 85)

A altura deve ser inserida em metros (m) com ponto como separador decimal (ex: 1.75)

---

## Mensagens de Resultado

Com base no valor calculado, o sistema exibe uma mensagem de acordo com a seguinte tabela:

| Faixa de IMC        | Classificação             |
|---------------------|---------------------------|
| Abaixo de 17        | Muito abaixo do peso      |
| 17 - 18.49          | Abaixo do peso            |
| 18.5 - 24.99        | Peso ideal                |
| 25 - 29.99          | Acima do peso             |
| 30 ou mais          | Obesidade                 |

