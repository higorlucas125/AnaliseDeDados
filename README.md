---
title: "Exercicio09-09-2024"
author: "higor lucas de Araujo Freitas"
date: "2024-09-08"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Probabilidade

1 - Uma caixa contém 20 canetas pretas e 30 canetas verdes. Calcule a probabilidade de tirar uma caneta que não seja verde. 

```{r}
canetas_pretas = 20
canetas_verdes = 30

total_canetas = canetas_pretas + canetas_verdes

canetas_nao_verdes = canetas_pretas / total_canetas 

sprintf("A probabilidade de não sair canetas verdes são : %s", canetas_nao_verdes)


```
2 - Em um grupo de 200 pessoas, 80 jogam xadrez, 120 jogam damas, e 30 jogam ambos os jogos. Calcule a probabilidade de uma pessoa escolhida aleatoriamente jogar pelo menos um dos jogos (xadrez ou damas)

```{r}

pessoas_xadrez = 80
pessoas_damas = 120

uniao = (80 + 120) - 30 

total_pessoas = 200

probabilidade = uniao /  total_pessoas

sprintf("A probabilidade de sair uma pessoa que joga ambos os jogos são : %s", probabilidade)

```

3 - De todos os funcionários de uma empresa, 70% usam o transporte público, 50% participam de um programa de carona compartilhada, e 30% usam ambos. Se um funcionário é escolhido ao acaso, qual a probabilidade de que ele participe do programa de carona compartilhada, dado que já sabemos que ele usa o transporte público? 

```{r}
transporte_publico <- 0.7
transporte_compartilhado <- 0.5
ambos <- 0.3

result <- ambos / transporte_publico

sprintf("A probabilidade de sair uma pessoa que já sabemos que ele usa o transporte público é  : %s", result)



```
4 - Em um estudo clínico, um novo teste para detectar uma doença rara foi aplicado a um grupo de 1000 pessoas. Dentre estas, sabemos que 10 pessoas realmente têm a doença. O teste diagnosticou corretamente 9 dessas 10 pessoas como positivas para a doença (verdadeiro positivo) e identificou incorretamente 40 pessoas saudáveis como positivas para a doença (falso positivo). Com base nesses dados experimentais, calcule a probabilidade de uma pessoa realmente ter a doença dado que ela recebeu um resultado positivo no teste. 

Dados Observados:
Número total de pessoas testadas: 1000
Pessoas com a doença: 10
Verdadeiros positivos: 9
Falsos positivos: 40

```{r}
```
