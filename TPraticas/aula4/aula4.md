### Pergunta P1.1

Para aceder a alguns sites nos EUA tem que estar localizado nos EUA.

1. Efetuando o comando `sudo anonsurf start` consegue garantir que está localizado nos EUA?
2. Porquê? Utilize características do protocolo TOR para justificar.

### Resposta P1.1


#### 1 
Não, devido ao processo de aleatorização na seleção dos OR's que o TOR fornece. Pois, nada nos garante que o último OR esteja localizado nos EUA.

Mas podemos obter um IP nos EUA se executarmos o comando ` sudo anonsurf change`  várias vezes e formos verificar ao site `  http://myiplocator.net/ `. Como não sabemos qual a sequência dos OR's nem o OR final da futura execução não podemos garantir que na próxima execução estamos localizados nos EUA.




#### 2
Não conseguimos garantir que estamos localizados nos EUA, pois o TOR garante-nos anonimato ponto a ponto, ou seja não sabemos qual é a sequência dos OR nem qual é o OR final. Essas sequências de três OR's são realizadas pelos OP, que é um servidor local para cada utilizador. Devido ao facto que os OR's escolhidos são alterados periodicamente podemos ter a probabilidade de estarmos localizados nos EUA, mas é um processo em que não conseguimos garantir que em uma dada execução vamos estar nos EUA.



### Pergunta P1.2
No seguimento da experiência anterior, aceda a <http://zqktlwi4fecvo6ri.onion/wiki/index.php/Main_Page> ou <https://www.facebookcorewwwi.onion/>.

1. Clique no símbolo do Onion (cebola) do lado esquerdo da barra de URL e verifique qual é o circuito para esse site.

2. Porque existem 6 "saltos" até ao site Onion, sendo que 3 deles são "_relay_"? Utilize características do protocolo TOR para justificar.



### Resposta P1.2


#### 1


#### 2

