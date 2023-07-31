para rodar no github workspace:

1- executei usando o github workspace

2- criei o arquivo .env usando somente as variáveis correspondentes ao Azure Open AI (comentei as 2 primeiras)

3- executei "npm install typescript -g" dentro da pasta TypeChat

4- executei "npm install" dentro da pasta TypeChat

5- executei "npm run build-all"

6- comecei a executar cada exemplo usando o comando "node ./dist/main.js ./dist/input.txt" dentro da pasta do próprio exemplo


para rodar localmente:

1- instalar "npm install typechat" no diretório do projeto

2- instalar "npm install typescript -g" no diretório do projeto

3- executei "npm install" dentro da pasta TypeChat

4- executei "npm run build-all"

5- no caso do exemplo de música, adicionei os ids do spotify

6- e na hora de iniciar a app, usei apenas o comando "node ./dist/main.js" (sem parametro)

7- e uma vez com a aplicação iniciada, eu pedi a música