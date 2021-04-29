# Como criar uma extensão para seu navegador

## Grupo 1 - Antonio, Athilas, Caliu, Erica, Haile, Roy, Victor

## Neste txt você aprenderá a como fazer uma extensão para seu browser com apenas um arquivo json e um outro js (javascript). Esta extensão, quando ativada, deixará o background de algumas páginas com uma cor diferente.

## Sem enrolação, vamos começar:

Passo 1 - Crie um arquivo .json chamado manifest

Passo 2 - Abra chaves para deixar seu código dentro: { desta forma }

Passo 3 - Dentro das chaves defina a versão do manifest = "manifest_version":2,

Passo 4 - Depois defina o nome = "name": "Hello World Extension",

Passo 5 - Depois coloque uma descrição = "description":"Minha primeira extensão para chrome",

Passo 6 - Defina a versão = "version": "0.1",

Passo 7 - Importe o script, que no caso é o outro arquivo que criaremos a seguir = ![image](https://user-images.githubusercontent.com/71882342/116598132-dc871f80-a8fc-11eb-88fc-7ac74f619390.png)

Passo 8 - No final, o arquivo manifest vai ficar assim = ![image](https://user-images.githubusercontent.com/71882342/116598006-b3ff2580-a8fc-11eb-913a-b9833ac0df60.png)

Passo 9 - Agora crie o arquivo .js chamado "content.js"

Passo 10 - Em seguida, coloque o código que será responsável por alterar a imagem de fundo para a cor que você deseja = 
document.body.style.backgroundColor = "#000";

#000 se trata da cor, que neste caso é preto. Para colocar outras cores você insere o valor dela, ou, escreva ela entre as aspas, exemplo: "red".
