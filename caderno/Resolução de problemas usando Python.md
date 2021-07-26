# Resolução de problemas usando Python

**Referência:** https://panda.ime.usp.br/pythonds/static/pythonds_pt/01-Introducao/03-cienciaDaComputacao.html

**Data:** 26 de julho de 2021.

---

### 1. Introdução

#### 1.3 O que é Ciência da Computação?

A ciência da computação é o estudo de **problemas**, **resolução de problemas** e **soluções** que surgem do processo de resolução de problemas. O papel do cientista de computação, ao se deparar com um problema, é desenvolver um **algoritmo**, isto é, uma lista passo-a-passo de instruções para resolver *qualquer instância* do problema que possa surgir. ***Algoritmos são processos finitos que se seguidos irão resolver o problema. Algoritmos são soluções.***

Ciência da computação também é o estudo de **abstrações**, sendo que ela que nos permite ver o problema e solução de tal forma a separar as assim chamadas **perspectivas lógicas e físicas**.

**Abstração procedimental:** considere o código abaixo.

```python
>>> math.sqrt(16)
4.0
>>>
```

Não necessariamente sabemos como a raiz quadrada está sendo calculada, mas sabemos o nome da função e como usá-la. Apenas sabemos o nome da função, que devemos dar um parâmetro (isto é, o número que será calculado a raiz quadrada) e a leitura do resultado. Esta é a **caixa preta da raiz quadrada**.

Resumidamente, a definição de abstração procedimental é:

> Um processo que oculta os detalhes de uma função específica para permitir que o usuário ou cliente veja de um nível muito alto.

#### 1.4 O que é programação?

É o processo de pegar um algoritmo e **codificá-lo** em uma notação, uma linguagem de programação, para que possa ser executado por um computador.

Todos os itens de dados no computador são representados como **cadeia de caractéres de dígitos binários**. Para que essas sequências tenham significado, precisamos ter **tipos de dados**. Esses tipos de dados internos de baixo nível (ou dados primitivos) fornecem os blocos de construção para o desenvolvimento do algoritmo.

#### 1.5 Por que estudar estruturas de dados e tipos de dados abstratos?

Um tipo de dado abstrato, ADT, é uma descrição lógica de como visualizamos os dados e as operações que são permitidas sem considerar como elas são implementadas. Isso significa que nos preocupamos mais com o que os dados representam e menos em como eles são construídos.  Fornecendo este nível de abstração, estamos criando um ***encapsulamento*** em torno dos dados. A ideia é que encapsulando os detalhes da implementação, estamos escondendo-os da visão do usuário, e isso é chamado de **ocultação de informação**.

![Abstract Data Types - GeeksforGeeks](https://media.geeksforgeeks.org/wp-content/uploads/20190828194629/ADT.jpg)

A implementação de tipos de dados abstratos, geralmente chamados de **estruturas de dados**, exigirá que forneçamos uma visão física dos dados usando alguma coleção de construções de programação e tipos de dados primitivos.

#### 1.8 Primeiros passos com dados

Em Python, uma classe é definida para ser uma descrição de como os dados se parecem, o estado, e o que os dados podem fazer, o comportamento.  

As classes são análogas aos tipos de dados abstratos, porque um usuário de uma classe só vê o estado e o comportamento de um item de dados. Os itens de dados são chamados de **objetos** no paradigma orientado a objeto. Um objeto é uma instância de uma classe.

##### 1.8.1 Tipos de dados atômicos nativos

Existem duas classes numéricas nativas no python, que implementam os tipos inteiro e ponto flutuante. Essas classes são chamadas de `int`e `float`. As operações aritméticas padrão são: +, -, *, / e **. Outras úteis são: %, módulo; //, divisão inteira. 

