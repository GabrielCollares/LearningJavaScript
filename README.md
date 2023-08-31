# LearningJavaScript


### Variaveis
```
 Atribuições variavel// Possuem o mesmo Nome começando com minusculo e seguindo de nomes com letra maiuscula ex (variavelNUmeroUm)
```
```
 Const =  cria uma variável cujo o valor é fixo, ou seja, uma constante somente leitura 
```
```
 let = permite que você declare variáveis limitando seu escopo no bloco, instrução, ou em uma expressão na qual ela é usada 
```

### DataTypes
```
Boolean = True or False
String = 'Name' "Name" `name`
Number = -1, 0, 1, 1.5
```

### Formatando Strings
```
var s = 'JavaScript'
'Estou aprendendo s' // não faz interpolação
'Estou aprendendo' + s // usa concatenação
`Estou aprendendo ${s}` // usa template string

s.length // quantos caracteres a string tem
s.toUpperCase() // tudo para letras 'MAIUSCULAS'
s.toLowerCase() // tudo para letras 'MINUSCULAS'

// STRING TO NUMBERS
var n1 = 21         var n1 = 21.5        var n1 = 21.5
var n2 = 23         var n2 = 23          var n2 = 23.5
n1 + n2 = 44        n1 + n2 = 44 .5      n1 + n2 = 45
Number.ParsetInt    Number.ParsetFloat   Number

Number.ParsetInt  // Numeros inteiros
Number.ParsetFloat  // Numeros Reais
Number // Todos os tipos

// NUMBER TO STRING
 String(n1)
 n2.toString()
```
### Comandos Básicos

```
window.alert (DISPARA ALERTA NA GUIA)
window.confirm (CONFIRMAR EX CANCEL OR OK)
window.prompt (ESCREVER ALGO)
document.write (ESCREVE NA TELA / BODY)
```


## Exemplos
~~~JavaScript
        var n1 = Number(window.prompt('Digite um numero: '))
        var n2 = Number(window.prompt('Digite outro numero: '))
        var s = n1 + n2
        window.alert('Soma é --> ' + s)

        var nome = window.prompt('Qual é seu nome ?')
        document.write(`Olá, ${nome} ! seu nome tem ${nome.length} letras! </br>`)
        document.write(`Seu nome em maiuscúlo é ${nome.toUpperCase()}</br>`)
        document.write(`Seu nome em minuscúlo é ${nome.toLowerCase()}`)


        var nome = window.prompt('whats your name ?')
        window.alert('é um grande prazer em te conhecer, ' + nome + ' seja bem-vindo')
~~~



### Teclas 
```
* \'	aspas simples
* \"	aspas duplas
* \\	barra invertida
* \n	nova linha
* \t	tab
* \r	retorno de carro
* \b	retroceder
* \f	quebra de página 
```

### Operadores Aritméticos/Atribuição
``` 
+ somar
- diminuir 
* vezes
/ dividir 
% resto da divisao inteira
** elevado
```

### Operadores Relacionais
``` 
9 > 4 = true
7 < 4 = false
8 >= 8 = true
7 <= 4 = false 
6 == 6 = true Igualdade
6 == '6' = true Igualdade
6 === '6' = false Identicos
4 != 4 = false Diferente
```

### Operadores Lógicos
```
! = Negação
&& = Conjunção
|| = disjunção
```
~~~JavaScript
idade >= 15 && <=17 // idade entre 15 e 17?
estado == 'RJ' || estado == 'SP' // O estado é RJ ou SP?
salário > 1500 && sexo != 'M' // o salário é acima de 1500 e não é homem?

var média= 8
média >=7? 'APROVADO': 'REPROVADO'
~~~

