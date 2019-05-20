# Detecção automática de problemas elétricos por meio da análise computacional de imagens térmicas

O repositório contém um dataset de imagens térmicas de um experimento elétrico, que simula os problemas de mal-contato e sobrecorrente em uma placa de circuito impresso.

A pasta imagens contém as imagens originais e térmicas (sem rótulos), além de sequências de gravação em formato .mat. O conteúdo atualmente está incompleto, as imagens estão sendo filtradas e organizadas.

O arquivo "fm.mat"é o arquivo no formato MATLAB com todas as imagens devidamente rotulados.
É uma matriz multidimensional, onde as duas primeiras dimensões são a largura e altura da imagem, e a terceira dimensão, o número sequencial da imagem. 

A pasta "classificadores" contém classificadores gerados para as imagens de fm.mat, com os modelos já treinados.
