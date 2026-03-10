# Desafio-Pratico-
Desafio Prático: Algoritmos em Grafos — Da Teoria ao Mundo Real
# Projeto de Grafos: Da Teoria à Prática

## 🧩 Fase 1: Análise LeetCode

### 1. Clone Graph (#133)
- **Algoritmo:** DFS (Busca em Profundidade).
- **Complexidade de Tempo:** $O(V + E)$ - Cada nó e aresta é visitado uma vez.
- **Complexidade de Espaço:** $O(V)$ - Espaço para o Hash Map de cópias.

### 2. Network Delay Time (#743)
- **Algoritmo:** Dijkstra (com Min-Heap).
- **Complexidade de Tempo:** $O(E \log V)$ - Devido às extrações da fila de prioridade.
- **Complexidade de Espaço:** $O(V + E)$ - Armazenamento da lista de adjacência.

## 🌍 Fase 2: Aplicação no Mundo Real
**API:** [PokeAPI](https://pokeapi.co/)
**Aplicação:** Mapeamos cadeias de evolução Pokémon como grafos dirigidos e pesados. 
Utilizamos a lógica do **Dijkstra** para calcular o menor "custo de experiência" para 
alcançar diferentes evoluções a partir de uma base comum.
