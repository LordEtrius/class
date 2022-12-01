1- Qual estrutura pra gravar a tabela?

2-Como Sorteia Nro

3-Estrutura do codigo

Resps:
1-
2 versoes pro jogo - Facil - Dififil
No Sort  - Facil - Nro de 1 a 60 - tabela 4x4
Estado grava - Nro 6 bits(0-59) - board - 96 bits(6X16) - turno - 4 bits(0-15)
Estado = 106 bits = U120

100 Sort - Dificil - - Nro 1 a 100 - Tabela 5x5
Estado grava - Nro 7 bits(0-99) - Board - 175 bits(7x25) - turno 5 bits(0-24)
Estado = 187 bits = Pair U120 U120

2-
IO no hash pra usar como seed de um prng

3-
Kind2 - e eu acho q eu sei fazer pq eu so lindo.