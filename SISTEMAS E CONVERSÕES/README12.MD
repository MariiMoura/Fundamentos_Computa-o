# Sistemas de Numeração Decimal e Hexadecimal

Os **sistemas de numeração** dos pcs são os formatos de como os dados podem ser mostrados sob diferentes notações. 

As **principais bases numéricas utilizadas pelos computadores** são a do sistema binário (0/1) porém existem outras bases numéricas como: 
    **Octal** composta por (0,1,2,3,4,5,6,7) (oito algarismos)
    **Decimal** composta por (0,1,2,3,4,5,6,7,8,9) (dez algarismos)
    **Hexadecimal** composta por (0,1,2,3,4,5,6,7,8,9 e A,B,C,D,E,F) (desseseis algarismos)
       # Além dos tradicionais numerais, apresenta as letras maiúsculas de “A” a “F” que representam respectivamente: A = 10, B = 11, C = 12, D = 13, E = 14, F = 15.

# Conversão de bases 

    **DECIMAL PARA BINÁRIO**
        Para realizar a conversão de decimal para binário, realiza-se a divisão sucessiva por 2 (base do sistema binário). O resultado da conversão será dado pelo último quociente e o agrupamento dos restos de divisão será o número binário. 
            45 EM DECIMAL PARA BINÁRIO
                45 / 22 / 11 / 5 / 2 / 1 (divide todos os valores por 2 e a sobra é o resultado binário)
                A leitura do resultado é feita do último quociente para o primeiro resto. Sendo assim, o resultado da conversão do número 45 para binário é 101101

    **DECIMAL PARA HEXADECIMAL**
        Segue a mesma lógica de binário, você divide o valor por 16 e a sobra é o resultado em hexadecimal.
        438 EM DECIMAL PARA HEXADECIMAL
            438 / 27 / 16 
            # O resultado é lido da direita para a esquerda a partir do último quociente. Assim. 438 é igual a 1B616 . Note que o resto da segunda divisão foi o número 11, que corresponde ao número B em Hexadecimal.

    **DECIMAL PARA OCTAL**
        segue a mesma lógica dos anteriores porém o divisor é 8 
        246 EM DECIMAL PARA OCTAL: 
            246 / 30 / 3 
            #O resultado é lido da direita para a esquerda a partir do último quociente. Assim, 246 é igual a 366

    **OCTAL PARA BINÁRIO**
        A conversão de octal para binário é feita convertendo dígito a dígito de octal em binário, da direita para a esquerda. Cada dígito é convertido para um grupo de 3 bits, conforme a lista a seguir, que apresenta ao lado esquerdo os números octais e ao direito os números binários.

            Octal - Binário:
                0 - 000;
                1 - 001;
                2 - 010;
                3 - 011;
                4 - 100;
                5 - 101;
                6 - 110;
                7 - 111.

    **HEXADECIMAL PARA BINÁRIO E O CONTRARIO**
        Segue a mesma lógica do octal 
            Hexadecimal - Binário:
                0 - 0000;
                1 - 0001;
                2 - 0010;
                3 - 0011;
                4 - 0100;
                5 - 0101;
                6 - 0110;
                7 - 0111;
                8 - 1000;
                9 - 1001;
                A - 1010;
                B - 1011;
                C - 1100;
                D - 1101;
                E - 1110;
                F - 1111.

    ** OCTAL-HEXADECIMAL E HEXADECIMAL-OCTAL**
        Para converter eles primeiro precisa converter eles para binário e de binário para o resultado que você quer que seja convertido. 

