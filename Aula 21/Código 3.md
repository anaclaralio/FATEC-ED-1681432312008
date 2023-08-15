Código 3:

\```javascript

1. Function BuscaBinaria(x){
1. esq = 1                  // Inicializa o índice da esquerda
1. dir = n                  // Inicializa o índice da direita
1. enquanto esq <= dir faca{  // Enquanto a condição for satisfeita
1. meio = ((esq + dir) / 2)  // Calcula o índice do meio
1. se A[meio] == x entao     // Verifica se o elemento no índice do meio é igual a x
1. devolve meio           // Retorna o índice do meio se a condição for satisfeita
1. senao se x > A[meio] entao // Verifica se x é maior que o elemento do meio
1. esq = meio + 1          // Atualiza o índice da esquerda para a busca na metade direita
1. senao                       // Caso contrário
1. dir = meio - 1          // Atualiza o índice da direita para a busca na metade esquerda
1. }
1. devolve -1                      // Retorna -1 se x não for encontrado
1. }

\```

Total de instruções: 14

Portanto, o total de instruções para cada código é:

Código 1: 9 instruções

Código 2: 9 instruções

Código 3: 14 instruções
