# Como usar:

Existem poucas coisas que precisam ser feitas, nelas vc precisa modificar 3 arquivos, sendo eles os arquivos:
 "auth.env"
 "BanLista.txt"
 "Init.bat"

## auth.env:

Abra o arquivo como texto.
No campo "TWITCH_USERNAME" preencha com o nick da conta que será usada.
No campo "TWITCH_OAUTH" será preciso pegar o autenticador da conta que será usada, vc pode obter nesse site, basta conectar usando a conta que vai banir os nicks https://twitchapps.com/tmi/
![](https://cdn.discordapp.com/attachments/802623372856262717/1056994472875004054/image.png)

## BanLista.txt
Só tacar os nicks das pessoas que vc pretende banir, um nick por linha ***não colocar mais de uma palavra por linha.***

## Init.bat

Esse pode ser um pouco confuso no começo, mas é de fato, bem simples.

`node Public.js canal/canal/canal/canal "BanLista.txt"`
|Item  |Uso|
|--|--|
|Node  |`Uso do Node.js para iniciar o banimento`  |
|Public.js|`O nome do script que da ban`|
|canal/canal/canal/canal  |`Canais separados por "/" `|
|"BanLista.txt"| `O arquivo de texto onde esta os nicks`|


