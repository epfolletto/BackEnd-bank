# `Projeto`
Sistema bancário

# `Descrição`
O Projeto Sistema bancário-backend foi desenvolvido como uma atividade dentro do curso Full-Stack Web Developer da Labenu, o qual consiste na elaboração de uma API que retorna dados conforme as requisições enviadas. Trata-se de uma ferramenta básica que simula o funcionamento de um banco.

A documentação da API pode ser acessada [aqui](https://documenter.getpostman.com/view/21552787/2s7YfU5rLx).

# `Modo de usar`
As requisições que podem ser feitas são:  

- **[GET] getAccounts:** busca todas as contas cadastradas. Com as informações do nome do usuário, cpf, data de nascimento, saldo e extrato.
- **[POST] createAccount:** cria uma nova conta, fornecendo (via body) nome, cpf e data de nascimento.
- **[GET] getBalanceByCpf:** busca o saldo de uma conta, fornecendo (via body) o cpf do usuário.
- **[PUT] deposit:** faz o depósito de saldo em uma conta, fornecendo (via body) o nome, cpf e valor.
- **[POST] pay:** faz o pagamento de uma conta, fornecendo (via body) o cpf, descrição, valor e data.
- **[PUT] updateBalance:** atualiza o saldo de um usuário.
- **[POST] transfer:** faz uma transferência de valor entre contas, fornecendo (via body) o nome e cpf do remetente, nome e cpf do destinatário e valor.

# `Instalando e rodando o projeto`
Fazer o clone do projeto:
- git clone link-do-repositório

Instalar as dependências:
- npm install

Rodar o projeto:
- npm run dev

# `Tecnologias utilizadas`
<div>
<img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
<img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge">
<img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white">
<img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white">
</div>

# `Autor`
Evandro Paulo Folletto </br>
<a href="https://www.linkedin.com/in/evandrofolletto/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> <a href="https://github.com/epfolletto"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>

# `Imagens`
Abaixo são mostradas algumas imagens de requisições:

### Requisição getAccounts:
<img src="./src/images/img_1.png"/>

### Requisição createAccount:
<img src="./src/images/img_2.png"/>

### Requisição transfer:
<img src="./src/images/img_3.png"/>