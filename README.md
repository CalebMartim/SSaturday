# SSaturday (18/01)

## Problemas práticos

## Strings

## Problema 1
Dado uma string A e outra string B, informe se A é uma substring de B

**Exemplo**:

a string ```bcd``` é substring da string ```abcdef```

#### Entrada
```
5
bcd
abcdef
abd
abcdef
olamundo
oimundo
ecraf
minecraft
c202
apc2025.1
```
#### Saída
```
Sim
Nao
Nao
Sim
Sim
```

## Problema 2
Dado duas strings A e B, informe o tamanho do maior prefixo em comum entre A e B

#### Entrada
```
6
abaco
abacaxi
teste
test
abc 
abcd
apple
apricot
exemplo
exposicao
banana
banan
```
#### Saída
```
4
4
3
2
2
5
```

## Problema 3
Dado uma string que contém apenas caractéres ```x``` e ```.``` informe qual é a maior 
distância entre dois caractéres ```x```, isto é, a maior quantidade de caractéres 
```.``` que está entre dois caractéres ```x```.

#### Entrada

```
5
...x.x.x..xx.....x..x
....x...x...x...x....
....x
x.x.x.x
.....
```

#### Saída
```
5
3
0
1
0
```

## Listas 

## Problema 1
Dado uma lista de números inteiros e um inteiro K, informe quantos elementos dessa lista são maiores
do que K

#### Entrada
```
5
1 5 7 5 10 3
5
1 2 3 4
5
-10 -5 0 5
-3
1 2 2 3 3 3 4
2
543 33 645 754 1 394 9 146
145
```

#### Saída
```
2
0
2
4
5
```

## Problema 2
Dado uma lista de números inteiros, verifique se a lista é uma permutação do tamanho 
desta lista, isto é, todos os números entre 1, 2, ... até o tamanho da lista aparecem exatamente uma vez
#### Entrada
```
7
1 2 3 4 5
5 4 3 2 1
1 2 2 
2 1 4 3 6 5
1
2 2
1 2 3 4 5 7
```

#### Saída
```
Sim
Sim
Nao
Sim
Sim
Nao
Nao
```

## Problema 3
Dado uma lista de números inteiros a um número inteiro X informe dois números 
nesta lista tal que a soma deles sejam igual a X ou informe que não há tal par

#### Entrada
```
5
1 2 3 4 5
6
2 7 5 1
8
7 8 13 1 
2
2 11 15 7
9
3 3 
6
```

#### Saída
```
2 4
7 1
Nao tem
2 7
3 3
```
