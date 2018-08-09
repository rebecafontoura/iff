##Utilização do comando GETS
```ruby
#Primeiro fazemos uma pergunta.
#Adicionamos um nome escolhido a uma variável que seria "sabor".
#A função do 'gets' é pegar o valor dessa variável e armazená-la para um futuro uso.

Exemplo
puts "Como está o suco de laranja ?"
sabor = gets
print "Sua opnião sobre o suco de laranja é que está: "
print sabor
#finalmente utilizamos o comando print para mostrar na tela o valor digitado que no caso poderia ser "uma delícia" por exemplo.
```
##Utilização do comando GETS de uma forma resumida
```ruby

Exemplo
puts "Como está o suco de laranja ?"
sabor = gets
print "sua opnião sobre o suco de laranja é que está: #{sabor}"

#Essa forma é chamada de interpolação, basta colocar dentro da string a variável entre as chaves #{}.
#ATENÇÃO strings definidas com chaves simples não tem como fazer interpolação, por isso use aspas duplas.
#Prefira sempre optar por esse método ao invés de concatenação(+) ou do append(<<), por ser mais elegante e rápido.
```
