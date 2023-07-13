# Desafio de Desenvolvimento Web - MySQL

Olá! Este é um desafio de desenvolvimento web focado em MySQL. Nele, você irá criar os scripts para realizar as quatro operações básicas (CRUD - Create, Read, Update, Delete) em uma tabela do MySQL. Além disso, você irá criar os scripts para criar a base de dados e a tabela necessárias para este desafio.

## Descrição do Desafio

Seu objetivo é criar os seguintes scripts em SQL:

1. Script para criar a base de dados:
   - Nome da base de dados: `desafio_web`
   
2. Script para criar a tabela `usuarios`:
   - Colunas da tabela:
     - `id` (inteiro, auto incrementado, chave primária)
     - `nome` (texto)
     - `email` (texto)
     - `funcao` (texto)

3. Script para inserir um registro na tabela `usuarios`.

4. Script para ler os registros da tabela `usuarios` e exibi-los.

5. Script para atualizar um registro específico na tabela `usuarios`.

6. Script para excluir um registro específico da tabela `usuarios`.

## Dicas

- Utilize o Docker para instalar o MySQL no seu ambiente de desenvolvimento. Isso facilitará a criação e configuração do banco de dados.
- Recomendo o uso do HeidiSQL como cliente do MySQL para facilitar a execução dos scripts SQL e a visualização dos resultados.

## Instalação do MySQL com Docker

Para facilitar o ambiente de desenvolvimento, recomendo a utilização do Docker para instalar o MySQL. Siga os passos abaixo:

1. Certifique-se de ter o Docker instalado em sua máquina. Caso não tenha, você pode encontrá-lo e baixá-lo em: https://www.docker.com/get-started

2. Abra o terminal ou prompt de comando e execute o seguinte comando para baixar a imagem do MySQL:

   ```bash
   docker pull mysql
   docker run -d -p 3306:3306 --name mysql-container -e MYSQL_ROOT_PASSWORD=suasenha mysql

3. Após instalado o heidiSQL (<a href="https://www.heidisql.com/download.php"> https://www.heidisql.com/download.php</a>) no windows,
Faça o login no mysql usando as credenciais abaixo (com a senha que você usou no código acima):
  - host: localhost
  - usuário: root
  - senha: suasenha

4. Use o heidiSQL para executar os scripts.

## Entrega

Após concluir o desafio, você pode compartilhar os scripts SQL em seu GITHUB.
Lembre-se de usar o commit a cada script concluído.
Certifique-se de incluir todos os scripts necessários para criar a base de dados, a tabela e executar as operações CRUD.

Divirta-se e boa sorte!
