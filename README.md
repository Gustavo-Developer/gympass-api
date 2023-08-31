# App

Gym pass style app.

## RFs ( Requisitos Funcionais )

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-ins em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma academia

## RNs ( Regras de Negócio )

- [ ] O usuário não pode se cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver a (100m) da academia;
- [ ] O check-in so pode ser validado até 20m após criado;
- [ ] O check-in so pode ser validado por administradores;
- [ ] A academia so pode ser cadastrada por administradores;

## RNFs ( Requisitos Não-funcionais )

- [ ] A senha do usuário deve estar criptografada;
- [ ] Os dados da aplicacão precisam estar persistidos em um banco PostigreSQL;
- [ ] Todas listas de dados precisam estar paginadas com 20 itens por página
- [ ] O usuário deve ser identificado por um JWT - Json Web Token


## Funcionalidades e Aprendizado

- Geolocalizacão
- Autenticacão c/ JWT
- Controle de acesso
- Paginacão
- SOLID
- Docker
- Design Patters
- Check-in
- Armazenamento de Estados
- Docker
- Deploy



## Comandos e configuracões do Projeto

- Iniciando o Projeto
    ```bash
      npm init -y
    ```
- Criando o arquivo TSConfig
    ```bash
      npx tsc --init
    ```
- Adicionando arquivo .gitignore
- Configuracão do .npmrc (mantém as versões fixas)
- Configuracão do EsLint
- Configuracão das Variaveis de Ambiente
- Instalando e configurando o Prisma
    ```bash
      npx prisma init
    ```

    ```bash
      npx prisma gerenate
    ```