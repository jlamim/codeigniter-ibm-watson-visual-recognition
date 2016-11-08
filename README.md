# IBM Watson + CodeIgniter + Unirest PHP

Esse é um exemplo de integração entre a API do Visual Recognition, um dos serviços do IBM Watson, e o CodeIgniter.

Como o IBM Watson não possui um SDK oficial para PHP, somente a possibilidade de requisição cURL, então utilizamos a biblioteca Unirest PHP para fazer essas requisições à API do Visual Recognition.

Após fazer o clone/download do projeto, execute o comando a seguir para instalar as dependências através do Composer.

```
composer install
```

No diretório `application/libraries` tem um arquivo chamado `IBMWatsonVR.php`, que é onde está o código inicial da integração. Ele faz as requisições à API para poder obter as informações da imagem.

Essa library ainda está em fase inicial, contemplando somente requisições via método GET, onde você precisa enviar a URL da imagem para obter as informações dela.

Futuramente ela receberá atualizações para suportar o método POST, permitindo enviar o arquivo da imagem, além de poder também enviar múltiplas imagens.

## Colaborando com a evolução da library

Você pode contribuir com a evolução da library. Para isso, verifique as issues no repositório da library (link abaixo), faça um fork e nos ajude a ampliar os recursos dela.

## Links Úteis

* IBM Watson - http://www.ibm.com/watson/
* Unirest PHP - https://github.com/Mashape/unirest-php
* Repositório da library IBMWatsonVR para CodeIgniter - https://github.com/jlamim/codeigniter-ibm-watson-visual-recognition
* Tutorial sobre a integração do CodeIgniter com a API do Visual Recognition - http://www.universidadecodeigniter.com.br/integracao-inicial-entre-codeigniter-e-visual-recognition/
