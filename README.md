# Microlins
Este código foi feito para a empresa Microlins. Nele, desenvolvi um código que me ajudasse a encontrar a média dos alunos que fossem terminando o curso e, posteriormente, inserindo à uma planilha e alimentando-a cada vez mais com os dados.


Neste código utilizei somente 3 bibliotecas para a realização do meu objetivo, e são eles: ```datatime```, ```time```, ```pandas```

## biblioteca datatime

para trazê-la ao código, somente precisei fazer um ```from datetime import time, datetime```
fazendo isso, ja foi o suficiente para ser possível a utilização da biblioteca para cálculos com data.

## biblioteca time
Com ela, fiz um ```import time as t```
Sua função no código foi de usar um ```time.sleep()``` para o código aguardar.

## biblioteca pandas
para a sua utlização, é recomendado que abra o CMD ou o terminal e faça: ```py -m pip install pandas```
caso já o tenha é fortemente recomendado que faça um ```--upgrade```.

Sua função foi de pegar as variáveis, sendo elas o ```nome do aluno, curso, quantidade de aulas e sua data de conclusão```
e inserí-las à uma planilha, podendo ser ```.csv```, ```.xlsx``` ou qualquer outra. Neste caso, utilizei um ```.xlsx```.

Feito isso, exporto a planilha utilizando o comando ```df.to_excel(NomeDoArquivo.extensão, encoding='latin')``` para então já ter tudo salvo.

#


Neste código, antes mesmo de precisar utilizar as bibliotecas logo acima, criei ```classes``` e ```def functions```para melhor compreendimento do código e ser o mais próximo de clean code possível.

cada uma das functions tem uma funcionalidade específica e destinada à qualidade de código.


Por fim, este foi o algoritmo que desenvolvi para a empresa Microlins.
