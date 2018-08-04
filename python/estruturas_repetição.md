
### Atenção
```python
É sempre necessário usar o comando # -*- coding: utf-8 -*- ou # -*- coding: utf-8 -*- para funcionar o programa.
```
### Contador com "While"
```python
# Tipo de codificação binária
# -*- coding: utf-8 -*-
# Criando uma variavel
contador = 0
# Aqui ele vai contar quantas vezes vai repetir o script
while contador < 11:
  print "A posição é", contador
  contador += 1
Saída:
A posição é 0
A posição é 1
A posição é 2
A posição é 3
A posição é 4
A posição é 5
A posição é 6
A posição é 7
A posição é 8
A posição é 9
A posição é 10
```
### Contador com "For"
```python
# Esse é a mesma coisa que o de cima, mas é bem mais aconselhável usar o for como contador do que while.
# -*- coding: utf-8 -*-
# Aqui se usa o range( que em tradução segnifica, alcance),
for contador in range(1,11):
  print "A posição é", contador
```
