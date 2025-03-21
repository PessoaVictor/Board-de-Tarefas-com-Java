# Board Management System

Este projeto é um sistema de gerenciamento de boards, desenvolvido em Java, que permite criar, gerenciar e visualizar boards e cards.

## Funcionalidades

- **Criar Board**: Crie um novo board com colunas personalizadas.
- **Gerenciar Cards**: Adicione, mova, bloqueie, desbloqueie e cancele cards dentro de um board.
- **Visualizar Board**: Veja os detalhes do board, incluindo colunas e cards.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal.
- **Gradle**: Ferramenta de automação de build.
- **Liquibase**: Ferramenta de versionamento de banco de dados.
- **MySQL**: Banco de dados relacional.
- **Lombok**: Biblioteca para reduzir o código boilerplate.

## Configuração do Ambiente

1. **Clone o repositório**:
    ```sh
    git clone <URL_DO_REPOSITORIO>
    cd board
    ```

2. **Configure o banco de dados**:
    - Certifique-se de que o MySQL está instalado e rodando.
    - Crie um banco de dados chamado `board` e configure o usuário e senha no arquivo `src/main/resources/liquibase.properties`.

3. **Execute as migrações do banco de dados**:
    ```sh
    ./gradlew run
    ```

4. **Compile e execute o projeto**:
    ```sh
    ./gradlew build
    ./gradlew run
    ```

## Como Usar

1. **Criar um novo board**:
    - Execute o programa e selecione a opção "Criar um novo board".
    - Siga as instruções para adicionar colunas e cards.

2. **Gerenciar um board existente**:
    - Selecione a opção "Selecionar um board existente" e insira o ID do board.
    - Utilize as opções do menu para gerenciar os cards.