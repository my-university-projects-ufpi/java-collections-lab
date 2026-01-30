# 📚 Estruturas de Dados em Java — Trabalho Final

Este repositório contém a implementação e estudo prático de diversas **estruturas de dados da linguagem Java**, desenvolvidas como trabalho final da disciplina de **Estrutura de Dados**.

O projeto tem como objetivo compreender o funcionamento interno, características e diferenças entre as principais coleções da Java Collections Framework, por meio de implementações próprias e testes práticos.

---

## 🎯 Objetivo do Trabalho

Este trabalho busca:

- Analisar o comportamento das principais estruturas de dados
- Comparar desempenho e organização interna
- Compreender vantagens e limitações de cada coleção
- Aplicar conceitos teóricos na prática
- Desenvolver código organizado e eficiente

---

## ⚙️ Estruturas Implementadas

O projeto contempla as seguintes estruturas:

---

### 📌 HashMap

O **HashMap** armazena pares chave-valor utilizando uma tabela hash.

Não garante ordem dos elementos e oferece alto desempenho em operações básicas.

#### Características:
- Inserção, busca e remoção em `O(1)` (médio)
- Não mantém ordenação
- Permite chave e valor nulos

---

### 📌 LinkedHashMap

O **LinkedHashMap** estende o HashMap e mantém a ordem de inserção dos elementos.

Utiliza uma lista duplamente encadeada interna.

#### Características:
- Mantém ordem de inserção
- Desempenho próximo ao HashMap
- Permite iteração previsível

---

### 📌 TreeMap

O **TreeMap** armazena os dados de forma ordenada, baseado em uma árvore balanceada (Red-Black Tree).

#### Características:
- Elementos ordenados automaticamente
- Operações em `O(log n)`
- Não permite chave nula

---

### 📌 List

A **List** representa uma coleção ordenada que permite elementos duplicados.

No projeto, são utilizadas implementações baseadas em listas dinâmicas.

#### Características:
- Acesso por índice
- Mantém ordem
- Permite repetição
- Inserção pode ser custosa no meio da lista

---

### 📌 PriorityQueue

A **PriorityQueue** organiza os elementos com base em prioridade.

É geralmente implementada com Heap.

#### Características:
- Remoção sempre retorna o elemento prioritário
- Inserção e remoção em `O(log n)`
- Não garante ordem total

---

### 📌 HashSetED

O **HashSetED** é uma implementação própria baseada em tabela hash.

Armazena elementos únicos, sem ordem definida.

#### Características:
- Não permite duplicatas
- Alto desempenho
- Baseado em hashing

---

### 📌 LinkedHashSetED

O **LinkedHashSetED** mantém os elementos únicos e preserva a ordem de inserção.

É baseado em HashSet com lista encadeada.

#### Características:
- Elementos únicos
- Mantém ordem
- Iteração previsível

---

### 📌 TreeSetED

O **TreeSetED** mantém os elementos ordenados automaticamente.

Utiliza uma estrutura baseada em árvore balanceada.

#### Características:
- Ordenação natural
- Operações em `O(log n)`
- Não permite valores nulos

---

## 🛠️ Tecnologias Utilizadas

- Linguagem: Java
- Paradigma: Orientação a Objetos
- Estruturas: Java Collections Framework

---

## 📊 Conceitos Aplicados

- Estruturas Baseadas em Hash
- Árvores Balanceadas
- Heaps
- Coleções Genéricas
- Análise de Complexidade
- Boas Práticas em Java

---
