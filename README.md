# IC---Problemas-de-Caminho-minimo

**Membros do projeto:**
  - Tiago Macedo -> Orientador
  - João Vinicius -> Estudante
  - Rodrigo -> Estudante

**Objetivo Principal:**
Nesse projeto nós estudamos as estruturas e alguns métodos para resolver problemas de caminho minimo.

Utilizamos a representação de um grafo na forma de dicionários em python

Para o estudo levamos em consideração alguns pontos a serem provados:

1º queriamos utilizar dijkstra e medir seu tempo de execução.

2º Queriamos comparar com os outros métodos de busca mais simples.

3º Após comparar vimos que a heurísitca gulosa era mais rapida, porém ela errava e ai começamos a utilizar métodos de probabilidade e estatística para verificar essa taxa de erro:

  - Para essa parte utilizamos: remoção de outliers, média aritmética, regressão linerar e correlação.
  
4º fora todos os testes também queremos aplicar nas próximas versões os algoritmos de Bellman-Ford e A*, e fazer suas comparações de tempo com dijkstra e verificar algumas possibilidades de aplicações.


Resultados:

Dijkstra x Heurística Gulosa -> Tempo:

![image](https://github.com/Jvfc745/IC---Problemas-de-Caminho-minimo/assets/102577378/2242050e-c63e-4d5b-a3e4-a4695222b37e)

Maximo de vértices em um grafo na busca exaustiva: (14 vértices utilizando RAM do Colab)

![image](https://github.com/Jvfc745/IC---Problemas-de-Caminho-minimo/assets/102577378/78adfcad-2bd5-4d8d-924c-3bd27bfe9793)

Erro da heurística gulosa:

![image](https://github.com/Jvfc745/IC---Problemas-de-Caminho-minimo/assets/102577378/ce13ffe5-a749-461b-bc8d-0010eb1a5b29)

Dados adicionais:

Encontramos pela regressão linear uma relação de número de grafos e queda na taxa de acerto da heurística gulosa:

![image](https://github.com/Jvfc745/IC---Problemas-de-Caminho-minimo/assets/102577378/37562ccb-9375-4931-a4b8-77c736c66ac0)

Correlação do numero de vértices com acetos:

![image](https://github.com/Jvfc745/IC---Problemas-de-Caminho-minimo/assets/102577378/e4e1b0c1-9c1d-41be-8f82-51fdc35a6b5b)

