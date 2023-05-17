# Projeto (Fase 1)

## Descrição dos serviços da escola:
* Escola – Deve fazer cadastro de alunos, professores e turmas. A Escola deve interagir com a Biblioteca para indicar quais usuários são alunos ou professores, de maneira que eles possam pegar uma quantidade maior de livros emprestados.
* Biblioteca – Sua principal função é realizar empréstimos de livros a usuários. Para isto, são necessários cadastros de livros e usuários. A Biblioteca é um serviço independente da Escola, de maneira que qualquer pessoa pode pedir livros emprestados. No entanto, professores e alunos podem pegar uma quantidade maior de livros emprestados. Assim, a Biblioteca deve pedir informações sobre os usuários à Escola para saber se são professores, alunos ou usuários comuns.
* Autenticação – Serviço de autenticação de usuários da Escola e da Biblioteca. Este é o único serviço responsável por armazenar credenciais (login, senha, chaves de acesso…) e fazer autenticação dos usuários (log in, log out). Será usado pela Escola e pela Biblioteca para autenticar seus usuários.

## Como executar o serviço
* Documentação do Laravel: [Documentação](https://laravel.com/docs/10.x)
* [Composer](https://getcomposer.org/doc/)
* Comando para executar o serviço em porta definida: php artisan serve --port *porta*

## Rotas usadas:
* / - Que retorna '{"/hello": "Hello, World!"}'
* /hello - Que retorna "Hello, World!"
