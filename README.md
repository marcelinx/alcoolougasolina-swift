# Calculadora de Combustível (Alcool vs. Gasolina) em Swift

Esta é uma calculadora simples em Swift para ajudar os usuários a determinar se é mais vantajoso usar álcool ou gasolina com base nos preços dos combustíveis. A decisão é baseada na relação entre o preço do álcool e o preço da gasolina, conhecida como "razão de custo". O aplicativo calcula essa razão e fornece uma recomendação sobre qual combustível usar.

## Requisitos do Projeto

- Xcode instalado (versão XX ou superior)
- Conhecimento básico de Swift

## Funcionalidades

- Os usuários podem inserir o preço do álcool por litro.
- Os usuários podem inserir o preço da gasolina por litro.
- Com base nos preços inseridos, o aplicativo calcula a razão de custo (preço do álcool / preço da gasolina).
- O aplicativo exibe uma recomendação clara sobre qual combustível é mais vantajoso com base na razão de custo.

## Como Usar

1. Abra o projeto no Xcode.
2. Navegue até o arquivo `MainViewController.swift`.
3. Localize a função `calcularMelhorOpcao(alcoolPrice:gasolinaPrice:)`.
4. Preencha os parâmetros `alcoolPrice` e `gasolinaPrice` com os preços dos respectivos combustíveis.
5. Execute o aplicativo no simulador ou em um dispositivo real.
6. O aplicativo exibirá a recomendação sobre qual combustível é mais vantajoso com base na razão de custo calculada.

## Exemplo de Uso

Suponha que o preço do álcool seja R$ 3,50 por litro e o preço da gasolina seja R$ 5,00 por litro.

```swift
let alcoolPrice = 3.50
let gasolinaPrice = 5.00

calcularMelhorOpcao(alcoolPrice: alcoolPrice, gasolinaPrice: gasolinaPrice)
```

O aplicativo calculará a razão de custo (3.50 / 5.00 = 0.70) e, como o valor é menor que 0.70, recomendará o uso do álcool como a opção mais vantajosa.

## Notas

- Este é um projeto simples destinado a fins educacionais e de demonstração.
- Os preços dos combustíveis podem variar, e a decisão de usar álcool ou gasolina deve considerar fatores adicionais, como o consumo de combustível do veículo.
- Esta calculadora pode ser expandida com recursos adicionais, como histórico de preços e dados de consumo de veículos.

## Conclusão

Este projeto fornece uma introdução básica ao desenvolvimento de aplicativos iOS usando Swift e Xcode. Ele demonstra como criar uma calculadora simples para ajudar os usuários a tomarem decisões informadas sobre o uso de álcool ou gasolina com base nos preços atuais.
