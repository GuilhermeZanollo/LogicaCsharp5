# LogicaCsharp5

RESOLUÇÃO DOS EXERCICIOS DO CURSO: https://github.com/acenelio/curso-logica-de-programacao-csharp

Matrizes - possuem linhas e colunas por serem bidimensionais

Uma matriz corresponde a uma coleção de dados de tamanho fixo, indexada, bidimensional e homogênea

- Indexada: os elementos são acessados por meio de indices
- bidimensional: duas dimensões
- homogênea: todos dados são do mesmo tipo

Matrizes são também chamadas de arranjos bidimensionais

Em C# a primeira posição de uma matriz é a posição 0, 0 (linha 0, coluna 0)

Um arranjo deve ser alocado previamente, antes de ser utilizado. Uma vez alocado, sua quantidade de elementos é fixa.

-> Arranjos funcionam exatamente como nas outras regras, se possuo 3 colunas, vai de 0 a 2

Como criar uma matriz?
declaração -> double[,] A; -> para indicar que é matriz, colocasse a virgula dentro do colchetes (ATÉ ENTÃO SO TEM UMA VARIAVEL A DEFINIDA NA MEMORIA RAM)
instanciação -> A = new double[3, 4]; -> a partir daqui, sera alocado na memoria, uma matriz de 3 linhas e 4 colunas chamada A

Como acessar os elementos de uma matriz?
Digamos que quero alocar um valor 10 na linha 1, coluna 2?: A[1, 2] = 10 
