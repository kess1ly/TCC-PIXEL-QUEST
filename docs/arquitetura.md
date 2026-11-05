# Arquitetura do PIXEL QUEST

## Estrutura do sistema

O PIXEL QUEST será desenvolvido utilizando uma arquitetura dividida em três partes principais:

### Frontend
Responsável pela interface visual e pela interação com os usuários, utilizando HTML, CSS e JavaScript.

### Backend
Responsável pelo processamento das informações, autenticação dos usuários e comunicação com o banco de dados, utilizando PHP.

### Banco de dados
Responsável pelo armazenamento das informações do sistema, utilizando MySQL.

## Comunicação entre as partes

O frontend se comunica com o backend por meio de requisições utilizando a Fetch API. O backend processa as solicitações, consulta ou altera os dados no banco MySQL e retorna as respostas necessárias.

Essa organização permite separar a interface visual, o processamento e o armazenamento dos dados.
