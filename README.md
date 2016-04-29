# Linha de comando básica
### Os principais comandos utilizados no [vídeo](https://youtu.be/rKBqXJZocYk)

## NAVEGAÇÃO

``ls`` - Lista os arquivos de um diretório.

``ll`` - Lista tudo dentro de um diretório (arquivos ocultos, tamanho, data de criação, permissões, etc).

``dir`` - É o comando equivalente ao ``ls`` no Windows.

``cd`` - Muda de diretório.

Exemplos:

```shell
ls

ls pasta1

ls ..

cd pasta1

cd pasta1/pasta-interna

cd ..
```

## CRIAR E REMOVER PASTAS

``mkdir`` - Cria uma nova pasta.

``rmdir`` - Apaga uma pasta, contanto que esteja vazia, do contrário, leia abaixo.

Exemplos:

```shell
mkdir pasta1

rmdir pasta1
```

## CRIAR E REMOVER ARQUIVOS

``touch`` - Cria um novo arquivo.

``copy con`` - É o comando equivalente ao ``touch`` no Windows. Seguido de ``ctrl + z``.

``rm`` - Remove um arquivo.

``del`` - É o comando equivalente ao ``rm`` no Windows.

``rm -rf`` - Força a remoção de arquivos, diretórios, subdiretórios e qualquer forma de vida existente. CUIDADO!

Exemplos:

```shell
touch exemplo.txt

rm exemplo.txt

rm *

rm -rf pasta1/
```

## COPIAR

``cp`` - copia um arquivo ou pasta.

``copy`` - É o comando equivalente ao ``cp`` no Windows.

Exemplos:

```shell
cp exemplo.txt ~/pasta1

cp exemplo.txt copia-exemplo.txt
```

## MOVER

``mv`` - move um arquivo ou pasta.

``move`` - É o comando equivalente ao ``mv`` no Windows.

Exemplos:

```shell
mv exemplo.txt ola.txt #renomeia

mv exemplo.txt ../pasta2
```
