# atvfinalgit

## Integrantes do grupo
-Thiago Gomes stein
-
-

## Objetivo
Desenvolver um projeto no portugol que peça 2 numeros ao usuario, e após isso faça a adição, subtração, divisão e multiplicação desses numeros.

## Etapas realizadas por cada membro

### Thiago Gomes Stein
-Criou o repositório pelo github
-Convidou os outros dois membros
-Configurou a chave via tutorial em slides enviados pelo professor
-Fez o arquivo base do Portugol, no portugol WebStudio:
programa {
  funcao inicio() {
    inteiro n1
    inteiro n2
    inteiro resultado
    escreva("Digite um número \n")
    leia(n1)
    escreva("Agora digite outro número! \n")
    leia(n2)
    resultado = n1+n2
    escreva("A soma resulta em ", resultado)
  }
}

-Copiou a chave ssh no Git Bash e colocou nas configurações de perfil.
-Logo após usou o git clone para colocar o repositório na maquina.
-Adicionou a operação de subtração no arquivo.
-Utilizou o git add . 
-Utilizou o git commit para commitar as mudanças realizadas.
-Por fim utilizou o git push

## Comandos utilizados
### comandos do Thiago Gomes Stein

compuni@maker451 MINGW64 ~
$ git config --global user.name "Thiago Gomes Stein"

compuni@maker451 MINGW64 ~
$ git config --global user.email "thiagomes.stein@edu.unifil.br"

compuni@maker451 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "thiagomes.stein@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:Dvo369CK6IdmFr5aLA7Lndq1vDlqp9PAvN4m991ZvOE thiagomes.stein@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
|                 |
|                 |
|                 |
|                 |
|  o   . S        |
| ..+ . +    .    |
|o.oo=.. o    +   |
|++O**Ooo+ . + o  |
|oXBXX**+o+ o E   |
+----[SHA256]-----+

compuni@maker451 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 620

compuni@maker451 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (thiagomes.stein@edu.unifil.br)

compuni@maker451 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@maker451 MINGW64 ~
$ ssh -T git@github.com
Hi Thiago-Stein! You've successfully authenticated, but GitHub does not provide shell access.

compuni@maker451 MINGW64 ~
$ git clone git@github.com:Thiago-Stein/atvfinalgit.git
Cloning into 'atvfinalgit'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@maker451 MINGW64 ~
$ cd atvfinalgit

compuni@maker451 MINGW64 ~/atvfinalgit (main)
$ git add .

compuni@maker451 MINGW64 ~/atvfinalgit (main)
$ git commit -m "Eu adicionei ao código a operação de subtração, também alterando a variavel resultado para resultadosoma, e também adicionei a variavel resultadosub"  [main d6a6ba8] Eu adicionei ao código a operação de subtração, também alterando a variavel resultado para resultadosoma, e também adicionei a variavel resultadosub
 1 file changed, 6 insertions(+), 3 deletions(-)

compuni@maker451 MINGW64 ~/atvfinalgit (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 501 bytes | 501.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:Thiago-Stein/atvfinalgit.git
   718514b..d6a6ba8  main -> main

compuni@maker451 MINGW64 ~/atvfinalgit (main)
$

## Observações
