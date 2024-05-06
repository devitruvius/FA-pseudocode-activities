# Conceitos Básicos em Pseudocódigo

Este repositório reúne pseudocódigos desenvolvidos como parte das atividades da disciplina de Fundamentos de Algoritmo no curso de Análise e Desenvolvimento de Sistemas (ADS) pela Universidade Federal do Cariri (UFCA). O objetivo principal é aplicar e consolidar conceitos básicos de lógica de programação e algoritmos através da construção de pseudocódigos.

## Estrutura do Repositório

O conteúdo está organizado em tópicos correspondentes a cada atividade, cada um contendo os pseudocódigos específicos para aquela tarefa. Essa estrutura facilita a navegação e revisão dos códigos.

## Atividades

1. **Faça um algoritmo que receba dois números e exiba o resultado da sua soma.**

   ```python
   escrever("Informe o primeiro número: ");
   ler numero1;

   escrever("Informe o segundo número: ");
   ler numero2;

   soma = numero1 + numero2;
   escrever("A soma é igual a: ", soma);
<hr>

2. **Faça um algoritmo que receba dois números e ao final mostre a soma, subtração, multiplicação e divisão dos números lidos.**

   ```python
   escrever("Informe o primeiro número: ");
   ler numero1;

   escrever("Informe o segundo número: ");
   ler numero2;

   soma = numero1 + numero2;
   escrever("A soma é igual a: ", soma");

   subtracao = numero1 - numero2;
   escrever("A subtração é igual a: ", subtracao);

   multiplicacao = numero1 * numero2;
   escrever("A multiplicação é igual a: ", multiplicacao);

   se numero2 != 0 entao{
     divisao = numero1 / numero2;
     escrever("A divisão é igual a: ", divisao);
   }
   senao{
     escrever("Não é possível dividir por zero.");
   }
<hr>

3. **Escreva um algoritmo para determinar o consumo médio de um automóvel sendo fornecida a distância total percorrida pelo automóvel e o total gasto de combustível.**

   ```python
   escrever("Informe a distância total percorrida em quilômetros: ");
   ler distanciaPercorrida;

   escrever("Informe o total gasto de combustível em litros: ");
   ler combustivelGasto;

   consumoMedio = distanciaPercorrida / combustivelGasto;

   escrever("O consumo médio do automóvel é de ", consumoMedio, " km/l");
<hr>

4. **Escreva um algoritmo que leia o nome de um vendedor, o seu salário fixo, e o total de vendas efetuadas por ele no mês (em dinheiro). Sabendo que este vendedor ganha 15% de comissão sobre suas vendas efetuadas, informar o seu nome, o salário fixo e o salário ao final do mês.**

   ```python
   escrever("Informe o nome do vendedor: ");
   ler nomeVendedor;

   escrever("Informe o salário fixo do vendedor: ");
   ler salarioFixo;

   escrever("Informe o total de vendas efetuadas pelo vendedor em dinheiro: ");
   ler vendasEfetuadas;

   comissao = 0.15 * vendasEfetuadas;

   salarioFinal = salarioFixo + comissao;

   escrever("Nome do vendedor: ", nomeVendedor);
   escrever("Salário fixo: ", salarioFixo);
   escrever("Salário final ao fim do mês: ", salarioFinal);
<hr>

5. **Escrever um algoritmo que leia o nome de um aluno e as notas das três provas que ele obteve no semestre. No final informar o nome do aluno e a sua média (aritmética).**

   ```python
   escrever("Informe o nome do aluno: ");
   ler nomeAluno;

   escrever("Informe a nota da primeira prova: ");
   ler nota1;

   escrever("Informe a nota da segunda prova: ");
   ler nota2;

   escrever("Informe a nota da terceira prova: ");
   ler nota3;

   media = (nota1 + nota2 + nota3) / 3;

   escrever("Nome do aluno: ", nomeAluno);
   escrever("Media aritmética: ", media);
<hr>
  
6. **Ler dois valores A e B, e efetuar a troca dos valores de forma que a variável A passe a possuir o valor da variável B, e a variável B passe a possuir o valor da variável A. Apresentar os valores trocados.**

   ```python
   escrever("Informe o valor de A: ");
   ler A;

   escrever("Informe o valor de B: ");
   ler B;

   valorTrocado = A;
   A = B;
   B = valorTrocado;

   escrever("Valores trocados: A = ", A, " e B = ", B);
<hr>
  
7. **Elaborar um algoritmo que efetue a apresentação do valor da conversão em real (R$) de um valor lido em dólar (US$). O algoritmo deverá solicitar o valor da cotação do dólar e também a quantidade de dólares disponíveis com o usuário.**

   ```python
   escrever("Informe a cotação do dólar: ");
   ler cotacaoDolar;

   escrever("Informe a quantidade de dólares: ");
   ler quantidadeDolares;

   valorEmReais = quantidadeDolares * cotacaoDolar;

   escrever("Valor em reais: R$ ", valorEmReais);
<hr>
  
8. **Ler uma temperatura em graus Celsius e apresentá-la convertida em graus Fahrenheit. A formula de conversão e: Fa = 9/5 * Ca + 32, sendo Fa temperatura em Fahrenheit e Ca temperatura em Celsius.**

   ```python
   escrever("Informe a temperatura em graus Celsius: ");
   ler temperaturaCelsius;

   temperaturaFahrenheit = (9/5) * temperaturaCelsius + 32;

   escrever("Temperatura em Fahrenheit: ", temperaturaFahrenheit);
<hr>

9. **Faça um algoritmo que receba o preço de custo de um produto e mostre o valor de venda. Sabe-se que o preço de custo recebera um acréscimo de acordo com um percentual informado pelo usuário.**

   ```python
   escrever("Informe o preço de custo do produto: ");
   ler precoCusto;

   escrever("Informe o percentual de acréscimo: ");
   ler percentualAcrescimo;

   acrescimo = precoCusto * (percentualAcrescimo/100);
   precoVenda = precoCusto + acrescimo;

   escrever("Preço de venda: R$ ", precoVenda);
<hr>

10. **A XPTO está vendendo seus produtos em 5 (cinco) prestações sem juros. Faça um algoritmo que receba um valor de uma compra e mostre o valor das prestações.**

    ```python
    escrever("Informe o valor total da compra: ");
    ler valorCompra;

    valorPrestacao = valorCompra / 5;

    escrever("Valor das prestações é: R$ ", valorPrestacao);
<hr>

## Fundamentos de Algoritmos
Acesse o repositório principal: https://github.com/devitruvius/ADS-fundamentos-de-algoritmos
