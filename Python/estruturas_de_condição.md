### Estrutura de Condição Usando IF

```Python
#Primeiramente devemos atribuir um valor à variável de imediato (que seria definir um valor aleatório após a igualdade) ou deixar com que o valor seja informado enquanto o programa estiver rodando (que é o caso desse programa).
#"int" é utilizando quando a sua variável guarda um número inteiro e "input" para que um valor seja inserido enquanto o programa é rodado.
#Além do "int", há também outros tipos de dados que podem ser inseridos, como "float" para números com ponto decimal e "string", para caracteres.


idade = int(input("Informe uma idade"))

if idade > 18:
    print("Você é maior de idade")
else:
    print("Voce e menor de idade")
```
### IF com AND
```Python
#Outros comandos como "or" ou "and" também podem incrementar a funcionalidade do IF.
Exemplo:

numero = int(input("Informe um número"))

if numero > 10 and numero < 50:
    print("Esse numero esta entre 10 e 50 ")
else:
    print("Esse numero não está entre ambos")
```
### IF com OR

```Python
#Exemplo usando o comando "or":
#Note que a compra vai ser somente realizada se os dois itens estiverem abaixo do valor "5".

precobananas = int(input("Digite o preço das bananas"))
precolaranjas = int(input("Digite o preço das laranjas"))

if precobananas > 5 or precolaranjas > 5:
  print("Compre nenhuma")
else:
      print("Compre ambas")
