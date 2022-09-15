# Autenticacao-com-Node.js-e-MongoDB-com-JWT

Login e Registro com Node.js

- API com Express e MongoDB.
- Endpoints públicos e privados.
- Os privados precisam de um token para serem acessados.
- O token é entregue através de um login bem sucedido.
- O token é enviado através do header da requisição.
- Um middleware valida o token.
- Não há persistência de sessão no back-end, tudo é feito pelo token.

## Dependencias

Todas as dependências de produção e de desenvolvimento do projeto.

### Bcrypt

Cria e decodifica a hash de senha.

### DotEnv

Criar um arquivo de configuração com as variaveis sensiveis de ambientes.

### Express

Framework que cria a API.

### JSONWebToken

Manusear token, criar e validar.

### Mongoose

ODM, facilita o trabalho com o MongoDB.

### Nodemon

Dependência de desenvolvimento. Atualiza a aplicação sempre que o codigo for salvo e cria um servidor de 
desenvolvimento.