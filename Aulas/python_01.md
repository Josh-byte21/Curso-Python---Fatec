# 01 – Primeiros Conceitos de Programação em Python

## Objetivo do Módulo
Este módulo apresenta os primeiros conceitos práticos da linguagem Python, permitindo que o estudante escreva seus primeiros programas, compreenda a lógica básica e se familiarize com a sintaxe da linguagem.

## Estrutura Básica de um Programa em Python
Um programa em Python é composto por instruções executadas sequencialmente, de cima para baixo. Diferente de outras linguagens, Python não exige um método principal (`main`) ou estrutura complexa para iniciar a execução.

Exemplo:
```python
print("Meu primeiro programa em Python")
```

## Comentários em Python
Comentários são utilizados para explicar o código e não são executados pelo interpretador.

Comentário de uma linha:
```python
# Este é um comentário
print("Olá, Python")
```

Comentário de múltiplas linhas (docstring):
```python
"""
Este programa imprime uma mensagem na tela.
Utilizado apenas como exemplo.
"""
print("Exemplo com docstring")
```

## Variáveis
Variáveis são utilizadas para armazenar valores na memória.

Características:
- Não é necessário declarar o tipo
- O tipo é inferido automaticamente
- O valor pode ser alterado durante a execução

Exemplo:
```python
nome = "Ana"
idade = 20
altura = 1.65
```

## Tipos de Dados Básicos

Inteiro (int):
```python
quantidade = 10
```

Ponto flutuante (float):
```python
preco = 19.90
```

Texto (str):
```python
mensagem = "Python é incrível"
```

Booleano (bool):
```python
aprovado = True
```

## Função `type()`
A função `type()` permite verificar o tipo de um dado.

```python
print(type(idade))
print(type(preco))
print(type(mensagem))
```

## Entrada de Dados com `input()`
A função `input()` permite receber dados digitados pelo usuário.

```python
nome = input("Digite seu nome: ")
print("Bem-vindo,", nome)
```

Observação: Todo valor recebido via `input()` é do tipo string.

## Conversão de Tipos (Casting)
Para converter valores entre tipos, utilizamos funções específicas.

```python
idade = int(input("Digite sua idade: "))
altura = float(input("Digite sua altura: "))
```

## Operadores Aritméticos
| Operador | Descrição |
|----------|----------|
| + | Adição |
| - | Subtração |
| * | Multiplicação |
| / | Divisão |
| // | Divisão inteira |
| % | Resto |
| ** | Potência |

Exemplo:
```python
a = 10
b = 3

print(a + b)
print(a * b)
print(a ** b)
```

## Boas Práticas Iniciais
- Utilize nomes de variáveis claros e descritivos
- Evite acentuação e espaços em nomes
- Use letras minúsculas e `_` (snake_case)

Exemplo:
```python
media_final = 7.5
total_alunos = 30
```

## Exercícios Propostos
1. Crie um programa que solicite o nome e a idade do usuário e exiba uma mensagem personalizada.
2. Leia dois números digitados pelo usuário e exiba a soma.
3. Calcule a média de três notas informadas pelo usuário.
