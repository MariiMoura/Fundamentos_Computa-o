# FUNÇÃO LÓGICA E ÁLGEBRA BOOLEANA 
    A função lógica opera sobre variavéis binárias e retorna o resultado em binário também. 
    A análise sistema lógica é utilizada para análise e projeto de circuitos de computação, chamada também de BOOLEANOS
        Os BOOLEANOS são respostas que são dadas em binário sendo 0 (representando não, falso, aparelho desligado, ausência de tensão, chave elétrica desligada, etc) e 1 (representando sim,verdadeiro, aparelho ligado, presença de tensão, chave ligada, etc)

Existe blocos de funções realizadas pela lógica BOOLEANA, um contrário do outro: 

   # FUNÇÃO E (AND)
    Executa a multiplicação (conjunção) booleana de duas ou mais variáveis binárias. Por exemplo, assuma a convenção no circuito. Chave aberta = 0; Chave fechada = 1 Lâmpada apagada = 0; Lâmpada acesa = 1.

    TABELA VERDADE: A tabela verdade é um mapa onde são colocadas todas as possíveis interpretações (situações), com seus respectivos resultados para uma expressão booleana qualquer. Como visto no exemplo anterior, para 2 variáveis booleanas (A e B), há 4 interpretações possíveis Em geral, para N variáveis booleanas de entrada, há 2N interpretações possíveis.


[   A	B	A.B
    0 	 0 	 0
    0 	 1 	 0
    1 	 0 	 0
    1 	 1 	 1
]

  #  Função OU (OR)
    Executa a soma (disjunção) booleana de duas ou mais variáveis binárias, por exemplo, assuma a convenção no circuito:

        Chave aberta = 0; Chave fechada = 1
        Lâmpada apagada = 0; Lâmpada acesa = 1

         TABELA VERDADE: Observe que, no sistema de numeração binário, a soma 1+1=10 Na álgebra booleana, 1+1=1, já que somente dois valores são permitidos (0 e 1).

[   A 	 B 	 A+B 
    0 	 0 	  0
    0	 1 	  1
    1	 0 	  1
    1	 1 	  1
]

   # Funções e Portas Lógicas Não (NOT)
    Executa o complemento (negação) de uma variável binária, e se a variável estiver em 0, o resultado da função é 1, e se a variável estiver em 1, o resultado da função é 0 (essa função também é chamada de inversora).

    Usando as mesmas convenções dos circuitos anteriores, tem-se que:

    Quando a chave A está aberta (A=0), passará corrente pela lâmpada e ela acenderá (S=1);
    Quando a chave A está fechada (A=1), a lâmpada estará em curto circuito e não passará corrente por ela, ficando apagada (S=0).

        TABELA VERDADE: A Porta lógica NÃO, ou inversor, é o circuito que executa a função NÃO, e o inversor executa a tabela verdade da função NÃO, se a entrada for 0, a saída será 1; Se a entrada for 1, a saída será 0. 

[A 	 Ã 
 0 	 1 
 1 	 0 
]