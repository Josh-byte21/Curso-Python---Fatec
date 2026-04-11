# Listas em Python

## 1. O que são Listas

Em Python, listas são estruturas de dados utilizadas para armazenar coleções ordenadas de valores. Elas são semelhantes aos vetores ou arrays de outras linguagens de programação, porém com maior flexibilidade.

Uma lista pode:

- Armazenar diferentes tipos de dados (números, textos, booleanos, etc.)
- Conter quantos elementos forem necessários
- Ser percorrida (iterada) facilmente
- Ter seus valores modificados durante a execução do programa

Listas são amplamente utilizadas em Ciência de Dados e Machine Learning para armazenar conjuntos de dados, resultados intermediários e coleções de valores.

## 2. Criação de Listas

Uma lista é criada utilizando colchetes `[]`, com os elementos separados por vírgula.

Exemplo:

```python
numbers = [1, 2, 3]
names = ["Ana", "Carlos", "Maria"]
```

Também é possível criar listas vazias:

```python
numbers = []
strings = []
```

## 3. Tipos de Dados em Listas

Uma lista pode conter elementos de diferentes tipos de dados:

```python
mixed_list = [1, "Python", 3.14, True]
```

Apesar dessa flexibilidade, em aplicações de análise de dados é comum trabalhar com listas que armazenam elementos do mesmo tipo, facilitando operações estatísticas e processamento posterior.

## 4. Acesso aos Elementos de uma Lista

Os elementos de uma lista são acessados por meio de índices, que começam em zero.

Exemplo:

```python
names = ["Ana", "Carlos", "Maria"]

print(names[0])  # Ana
print(names[1])  # Carlos
print(names[2])  # Maria
```

### Índice inexistente

Tentar acessar um índice que não existe gera um erro (exceção):

```python
print(names[3])  # IndexError
```

Esse comportamento ajuda a evitar acessos indevidos à memória e torna o código mais seguro.

## 5. Adicionando Elementos com o Método append()

O método `append()` permite adicionar um novo elemento ao final da lista.

Exemplo:

```python
numbers = []

numbers.append(1)
numbers.append(2)
numbers.append(3)

print(numbers)
```

Da mesma forma, podemos adicionar textos a uma lista de strings:

```python
strings = []

strings.append("hello")
strings.append("world")

print(strings)
```

## 6. Importância das Listas no Contexto do Projeto

No contexto do projeto Introdução à Programação em Python e Fundamentos de Machine Learning, listas são fundamentais para:

- Armazenar conjuntos de dados
- Representar amostras e variáveis
- Preparar dados para bibliotecas como NumPy e Pandas
- Manipular resultados de modelos e algoritmos

O domínio de listas é um passo essencial antes do estudo de estruturas mais avançadas.

## 7. Exercício Proposto

Realize as seguintes tarefas:

1. Crie uma lista vazia chamada `numbers` e adicione os números 1, 2 e 3 utilizando o método `append()`
2. Crie uma lista vazia chamada `strings` e adicione as palavras "hello" e "world"
3. Dada a lista abaixo, atribua à variável `second_name` o segundo nome da lista

```python
names = ["Ana", "Carlos", "Maria"]
```

### Resultado esperado (exemplo)

```python
numbers = []
strings = []

numbers.append(1)
numbers.append(2)
numbers.append(3)

strings.append("hello")
strings.append("world")

names = ["Ana", "Carlos", "Maria"]
second_name = names[1]

print(numbers)
print(strings)
print(second_name)
```

## 8. Conexão com Próximos Conteúdos

O estudo de listas prepara o estudante para compreender:

- Estruturas de repetição (`for`, `while`)
- Estruturas de dados avançadas
- Manipulação de dados com NumPy e Pandas
- Representação de conjuntos de dados em Machine Learning