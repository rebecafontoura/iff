### Estrutura de Repetição Usando FOR

```Python
for contador in range (0,10):
  print (contador)
 ```
 
 ### Estrutura de Repetição Usando WHILE
 
 ```Python
 contador = 0
 while contador < 10:
  print contador
  contador += contador
```

  ### Estrutura de Repetição Usando FOR para percorrer um array.

```Python
vetor = ['a', 'b', 'c']
for elemento in vetor:
  print (elemento)
 ```
 
  ### Estrutura de Repetição Usando FOR para percorrer um array, com acesso ao índice desse elemento.

```Python
vetor = ['a', 'b', 'c']
for indice,elemento in enumerate(vetor):
  print (elemento, indice)
```
