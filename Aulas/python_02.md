# Variáveis e Tipos de Dados em Python

## 1. Conceito de Variáveis em Python

Em Python, variáveis são utilizadas para armazenar valores na memória do computador, permitindo que esses valores sejam utilizados, modificados e manipulados ao longo da execução de um programa.

Python é uma linguagem dinamicamente tipada, o que significa que:

- Não é necessário declarar previamente o tipo da variável
- O tipo é definido automaticamente no momento da atribuição
- Uma mesma variável pode receber valores de tipos diferentes ao longo do programa

Essa característica contribui para a simplicidade da linguagem e facilita o aprendizado inicial de programação.

Exemplo:

```python
idade = 20
nome = "Ana"
altura = 1.65
```

## 2. Tipagem Dinâmica e Orientação a Objetos

Python é uma linguagem orientada a objetos, na qual tudo é tratado como um objeto, incluindo números, textos e estruturas de dados.

Cada variável referencia um objeto que possui:

- Um tipo
- Um valor
- Métodos associados

Essa abordagem é fundamental para o entendimento futuro de conceitos mais avançados, como estruturas de dados, bibliotecas científicas e frameworks de Machine Learning.

## 3. Tipos de Dados Básicos

Os tipos de dados básicos são essenciais para a construção de qualquer programa e formam a base para aplicações em Ciência de Dados e Machine Learning.

### 3.1 Inteiros (int)

Utilizados para representar números inteiros, positivos ou negativos, sem casas decimais.

```python
quantidade = 10
ano = 2025
```

### 3.2 Números de Ponto Flutuante (float)

Representam números reais, ou seja, números com casas decimais. São amplamente utilizados em cálculos estatísticos, científicos e análises de dados.

```python
preco = 19.90
media = 7.5
```

### 3.3 Texto (str)

O tipo `str` é utilizado para representar textos, palavras ou sequências de caracteres.

Strings podem ser definidas utilizando aspas simples ou duplas:

```python
mensagem = "Python é incrível"
nome = 'Carlos'
```

O uso de aspas duplas facilita a inclusão de apóstrofos no texto:

```python
frase = "Aprender Python não é difícil"
```

### 3.4 Valores Booleanos (bool)

O tipo booleano representa valores lógicos e possui apenas dois estados possíveis:

- `True` (verdadeiro)
- `False` (falso)

É amplamente utilizado em tomadas de decisão, condições e validações.

```python
aprovado = True
maior_de_idade = False
```

## 4. Verificação de Tipos com a Função type()

A função `type()` permite identificar o tipo de dado associado a uma variável, sendo muito útil para fins educacionais e depuração de código.

```python
idade = 20
print(type(idade))

preco = 19.90
print(type(preco))

mensagem = "Olá, Python"
print(type(mensagem))
```

## 5. Entrada de Dados do Usuário

A função `input()` permite que o programa receba informações digitadas pelo usuário durante a execução.

```python
nome = input("Digite seu nome: ")
print("Bem-vindo,", nome)
```

> **Observação Importante:** Todo dado recebido por meio da função `input()` é interpretado como texto (str), mesmo quando o usuário digita números.

## 6. Conversão de Tipos (Casting)

Para realizar operações matemáticas com valores informados pelo usuário, é necessário converter o tipo do dado.

Exemplos de conversão:

```python
idade = int(input("Digite sua idade: "))
altura = float(input("Digite sua altura: "))
```

Esse processo é fundamental em aplicações que envolvem cálculos estatísticos, análise de dados e Machine Learning.

## 7. Operadores Básicos

Python oferece operadores aritméticos para realizar cálculos matemáticos.

| Operador | Descrição |
|----------|-----------|
| + | Adição |
| - | Subtração |
| * | Multiplicação |
| / | Divisão |
| // | Divisão inteira |
| % | Resto da divisão |
| ** | Potência |

Exemplo:

```python
a = 10
b = 3

print(a + b)
print(a * b)
print(a ** b)
```

## 8. Boas Práticas no Uso de Variáveis

Desde os primeiros programas, é importante adotar boas práticas de programação:

- Utilizar nomes claros e descritivos
- Evitar acentos e espaços
- Usar letras minúsculas e `_` (snake_case)

Exemplo:

```python
media_final = 8.2
total_alunos = 35
```

## 9. Exercícios Propostos

1. Crie um programa que solicite o nome e a idade do usuário e exiba uma mensagem personalizada.
2. Leia dois números informados pelo usuário e exiba a soma.
3. Calcule a média de três notas digitadas pelo usuário.
4. Crie uma variável booleana que indique se o aluno foi aprovado (nota maior ou igual a 6).
