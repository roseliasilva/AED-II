# Complexidade das diferentes operações na Árvore de Busca Binária (BST)

## Challenge 01: Find Closest Value.

Este é um algoritmo Python para encontrar o valor mais próximo de um valor alvo em uma Árvore de Pesquisa Binária (BST).

### Descrição da Solução

A solução consiste em uma função chamada `findClosestValue(tree, target)`, que recebe uma árvore de pesquisa binária (BST) e um valor alvo como entrada e retorna o valor na BST que está mais próximo do valor alvo.

O algoritmo começa a busca pelo valor mais próximo a partir do nó raiz da árvore de busca binária. Ele trabalha de forma iterativa, explorando a árvore e estreitando a busca com base no valor alvo e no valor atual do nó. O valor mais próximo é constantemente atualizado durante o processo de busca.

### Instruções de Execução

1. Certifique-se de ter Python instalado em seu sistema.
2. Clone este repositório em sua máquina local:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git 
```

3. Navegue até o diretório do projeto:
```bash
cd nome-do-repositorio
```

4. Execute o arquivo de teste para verificar se a solução está funcionando corretamente:
```bash
pytest
```

### Complexidade do Algoritmo
A complexidade de tempo do algoritmo é O(h), onde h é a altura da árvore de pesquisa binária. No melhor caso, quando a árvore está perfeitamente balanceada, a complexidade de tempo é O(log n), onde n é o número de nós na árvore. No pior caso, quando a árvore é desbalanceada, a complexidade de tempo pode ser O(n), onde n é o número de nós na árvore.

A complexidade de espaço é O(1), pois o algoritmo utiliza apenas uma quantidade constante de espaço adicional para armazenar variáveis locais e recursivas.
