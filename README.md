# Tags - JSON Server Fake API

Uma simples simulação de uma REST API com JSON server que será usada para projetos futuros.

Endpoit: https://sideways-shrouded-germanium.glitch.me/tags

O JSON Server é uma biblioteca capaz de criar uma API Fake em pouquíssimo tempo e sem precisar de nenhuma linha de código.

#Passo a passo:

Instalação:

```
- npm install json-server
```


Então crie uma arquivo.json, na raiz do repositório

```
{
  "tags": [
    {"title": "Node.js", "amountOfVideos": 89}, 
    {"title": "Python", "amountOfVideos": 120}, 
    {"title": "JavaScript", "amountOfVideos": 55}, 
    {"title": "Machine Learning", "amountOfVideos": 78},
    ]
}
```
Agora só precisa rodar o comando a baixo e seu servidor será inicializado

```
Json-server --watch arquivo.json
```

Por padrão a API vai funcionar na porta 3000.

Documentação: https://www.npmjs.com/package/json-server