## A.

## Usuario Regular:

### Comando para criar o usuario:

sudo adduser pessoa_1

![](pessoa_1.PNG)

A senha defina foi "pessoa_1"

## Administrador:

### Comando para criar o Administrador:

sudo adduser pessoa_2

![](pessoa_2.PNG)

A senha defina foi "pessoa_2"

Para transformar o usuario em Administrador foi usado o comando "sudo usermod -aG sudo pessoa_2"

![](sudo.PNG)

## B.

Usei o comando passwd no usuário "pessoa_2" e troquei a senha para "senha_troca".

![](passwd.PNG)

## C.

O comando para mudar o diretório inicial foi:

pessoa_1:
![](diretorio.PNG)

pessoa_2:
![](diretorio2.PNG)

## D.

O comando para mudar o UID foi:

pessoa_1:
![](IDpessoa1.PNG)

pessoa_2:
![](IDpessoa2.PNG)

## E.

Comando para criar um novo grupo de utilizadores e adicionar o utilizador regular:
![](novogrupo.PNG)

## F e G.

Para adicionar permissões usei o comando "sudo visudo /etc/sudoers" que me leva para um ficheiro onde eu posso adicionar as permissões

![](visudo.PNG)

