## Projeto - Sistema de Controle de Empréstimo e Devolução de Livros
### Centro Paula Souza - Fatec Ferraz - Curso de Análise e Desenvolvimento de Sistemas
### Disciplina – Programação Web – Prof. Edson Saraiva de Almeida
### Grupo 9
thalles shinji rocha sato
### Backlog do produto
- REQ01 – Cadastrar Livro
Como – atendente da biblioteca
Eu quero – cadastrar um livro
De maneira que – seja possível consultar e emprestar o livro
- REQ01CT01 – cadastrar com sucesso
Dado: que o atendente da biblioteca tem um livro não cadastrado
Quando: o atendente informa os dados do livro
Então: o sistema valida os dados E apresenta uma mensagem confirmando o cadastro do livro
- REQ02 - Consultar livro
- REQ03 - Alterar livro
- REQ04 - Excluir livro
- REQ05 – Cadastrar usuário
Como – atendente da biblioteca
Eu quero – cadastrar um usuário
De modo que – seja possível realizar o empréstimo de um livro.
- REQ05CT01 – Cadastro de usuário com sucesso
Dado (pré-requisito) – que o RA do usuário não está cadastrado.
Quando (descrição das ações que devem ser realizadas) – o atendente digita as informações do usuário e confirma a operação.
Então (resultado esperado) – o sistema retorna uma mensagem confirmando que o cadastro foi realizado
- REQ05CT02 – Cadastro de usuário invalido
Dado (pré-requisito) – que o RA do usuário está cadastrado.
Quando (descrição das ações que devem ser realizadas) – o atendente digita as informações do usuário e confirma a operação.
Então (resultado esperado) – o sistema retorna uma mensagem informando que o usuário já está cadastrado
