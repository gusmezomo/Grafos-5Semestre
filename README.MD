# Grafos — Conversão de Representações

## 📋 Descrição

O programa lê um arquivo texto com a representação de um grafo em **Matriz de Adjacências** e converte para **Matriz de Incidências**, e vice-versa.

A estrutura interna é implementada como uma **Lista de Adjacências** utilizando listas encadeadas.

## 📌 Requisitos

- Leitura de arquivo com Matriz de Adjacências **ou** Matriz de Incidências
- Conversão entre os dois formatos
- Exportação do grafo nos dois formatos
- Estrutura interna baseada em Lista de Adjacências com listas encadeadas

## 🗂️ Arquivos

| Arquivo | Descrição |
|---|---|
| `main.cpp` | Ponto de entrada do programa |
| `Grafo.h` / `Grafo.cpp` | Estrutura principal do grafo |
| `Nodo.h` / `Nodo.cpp` | Nó da lista encadeada |
| `ListaSE.h` / `ListaSE.cpp` | Lista simplesmente encadeada |
| `GrafoADJ.txt` | Exemplo de entrada — Matriz de Adjacências |
| `GrafoINC.txt` | Exemplo de entrada — Matriz de Incidências |

## 🚀 Compilação e Execução

```bash
g++ main.cpp Grafo.cpp ListaSE.cpp Nodo.cpp -o grafo
./grafo
```

## 🛠️ Linguagem

C++