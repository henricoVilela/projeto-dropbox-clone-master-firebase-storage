# projeto-dropbox-clone-master-firebase-storage
Pagina web que simula algumas das funcionalidades do dropBox.

## Descrição:
Esse projeto é basicamente o mesmo [projeto-dropbox-clone-master-local-storage](https://github.com/henricoVilela/projeto-dropbox-clone-master-local-storage), a diferença é que alem de usar o **Realtime Database** do firebase, aqui é usado outro recurso do firebase que é o [storage](https://firebase.google.com/docs/storage?hl=pt-br), responsavel por armazenar os arquivos fisicos em nuvem. Com isso qualquer um que executar a aplicação apontando pro mesmo Database e Storage do firebase estaram sicronizados, acessando os mesmos arquivos.

## IMPORTANTE:
- Instalar o [NodeJs](https://nodejs.org/en/).
- Instalar o [Bower](https://bower.io/) *npm install -g bower*.
- Executar o comando *'bower install'* na pasta *'app > public'*.
- Executar o comando *'npm install'* na pasta *'app'* para baixar e instalar todas as dependencias do node.
- Abrir um terminal na pasta *'app'* e executar o comando *'npm start'*. (localhost:3000/) para acessar a aplicação.
- O fireBase ja esta configurado com o meu projeto publico de teste. Para uma nova configuração siga os [passos](https://firebase.google.com/docs/web/setup?authuser=0). 
