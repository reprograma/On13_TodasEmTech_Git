### Resolvendo conflitos de código
Criar uma branch a partir da main chamada `ex8-seuNome`

Ir no arquivo [index.html](index.html) e alterar a linha `<h1> Oi, meu nome é <b>Usuário teste</b></h1>` com o seu nome.

`git add . && git commit -m "Adicionando o meu nome"`

`git push origin ex8-seuNome`

Criar o Pull Request no github como ensinado

Perceberemos conflitos, como resolver ?

`git pull origin main`

Um conflito aparecerá.

`git status` para visualizar

Resolveremos juntas e depois

`git add . && git commit -m "Resolvendo conflitos"`

`git push origin ex8-seuNome`

E olharemos o resultado nos pull requests
