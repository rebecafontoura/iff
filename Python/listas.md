### Definindo uma lista ou array

```Python
#Uma lista pode conter n elementos de diversos tipos, inclusive outras listas.
lista = ['a', 1, 1.5, ['w', 'x', 'y', 'z']]
print(lista)
#Saída
>>['a', 1, 1.5, ['w', 'x', 'y', 'z']]
 ```
 ### Acessando os elementos
 
 ```Python
#Os elementos de uma lista podem ser acessados com uma iteração ou pelo índice do elemento.
#É importante lembrar que o primeiro elemento de uma lista tem a posição 0.
lista = ['w', 'x', 'y', 'z']
print(lista[0])
#Saída
>>w
 ```
 
 ### Uma lista possui métodos próprios
 
```Python
#Descobrindo a posição de um elemento
lista = [66.25, 333, 123, 1, 1234.5]
print(lista.index(123))
#Saída
>>2

#Contando quantas vezes um determinado elemento se repete
lista = [123, 123, 123, 47]
print(lista.count(123))
#Saída
>>3
print(lista.count(47))
#Saída
>>1

#Inserindo numa posição específica
lista = ['a', 0, 'c']
lista.insert(1, 'b')
print(lista)
#Saída
>>['a', 'b', 0, 'c']
#Importante lembrar que o método insert não substitui o elemento, ele apenas insere e move os elementos para a direita.

#Inserindo na última posição da lista
lista = ['a', 'b']
lista.append('c')
print(lista)
#Saída
>>['a', 'b', 'c']

#Removendo um elemento específico
lista = ['a', 'b']
lista.remove('a')
print(lista)
#Saída
>>['b']

#Invertendo os elementos de uma lista
lista = [1, 2, 3]
lista.reverse()
print(lista)
#Saída
>>[3, 2, 1]

#Organizando os elementos da lista em ordem crescente
lista = [4, 2, 1, 3]
lista.sort()
print(lista)
#Saída
>>[1, 2, 3, 4]

#Removendo elementos
lista = ['a', 'b']
lista.pop() #pop() remove o último elemento
print(lista)
#Saída
>>['a']

#Removendo elemento de um índice específico
lista = ['a', 'b']
lista.pop(0)
print(lista)
#Saída
>>['b']
