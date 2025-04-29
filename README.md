# aulas.python

![ilustração linguagem python](https://lginfo.com.br/site/wp-content/uploads/2023/10/Python-Symbol.png)

## Tipos primitivos(string, number(int/float), boolean

Para saber mais, [clique aqui](https://revistamonet.globo.com/celebridades/noticia/2025/04/o-alerta-que-selena-gomez-deu-para-taylor-swift-sobre-blake-lively-segundo-jornal-e-como-tudo-se-confirmou-com-e-assim-que-acaba.ghtml)

### Operadores artitiméticos

São os sinais que usamos pra fazer contas, tipo na matemática mesmo! Aqui estão os principais:

+
(mais): soma
-
(menos): subtração
*
(asterisco): multiplicação
/
(barra): divisão
//
(divisão inteira): divide e descarta a parte decimal
%
(módulo): pega o resto da divisão
**
(dobro de asterisco): potência, tipo 2**3 = 8
Exemplo:

```Py
a = 10
b = 3
print(a + b)  # 13
print(a / b)  # 3.333...
print(a % b)  # 1 (resto da divisão)
```

#### Operadores lógicos/comparativos

São usados pra fazer perguntas e decidir o que fazer com base na resposta. Vamos dividir em dois:

Operadores comparativos:

==
(igual a)
!=
(diferente de)
>
(maior que)
<
(menor que)
>=
(maior ou igual a)
<=
(menor ou igual a)
Operadores lógicos:

and
(e): as duas condições precisam ser verdadeiras
or
(ou): pelo menos uma precisa ser verdadeira
not
(não): inverte o valor lógico
Exemplo:
```py
idade = 20
if idade >= 18:
    print("Você é maior de idade!")
else:
    print("Ainda não é maior de idade.")
```
**Tipos de estruturas condicionais:**

- if: Executa um bloco de código se uma condição especificada fpr verdadeira.
- elif: Significa "else if" e permite que você verifique várias condições.
- else: Executa um bloco de código se nenhuma das condições anteriores for verdadeira.

```py
idade = 20
if idade >= 18:
    print("Pode dirigir!")
elif idade >= 16:
    print("Pode aprender a dirigir, mas ainda não pode dirigir sozinho.")
else:
    print("Ainda não pode dirigir.")
```
