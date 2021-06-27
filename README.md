# CABEÇALHO

Vendo alguns programas de linha de comando durante meus estudos, os diferentes cabaçalhos que os programas apresentam me chamaram a atenção.

Pensando nisso, pensei em criar um programa que crie esses cabeçalhos de forma dinamica e simples

Chamei o objeto criado de `Cabecalho` e por enquanto esse objeto só tem duas funções a `cria_cabecalho()` e `imagem_ascii()`

A função `cria_cabecalho()` recebe como parametro uma string e printa a frase que foi passada já formatada para o cabeçalho

A função `imagem_ascii()` recebe como parametro uma string com o nome da imagem que deseja passar para ascii e printa a imagem ascii

Foi testado com sucesso os seguntes formatos de imagem para `imagem_ascii()`:
* .jpeg
* .jpg
* .PNG
* .tiff

Dentro do arquivo vai uma imagem `caveira.jpeg` para realizar os testes

## Melhorias futuras
* A função `cria_cabecalho()` não suporta numeros, futuramente prentendo incluir os numeros
* Na função `imagem_ascii()` a maioria das imagens ficam muito grandes para se encaixarem em software de comandline
