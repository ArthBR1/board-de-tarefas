# Board de Tarefas em Java

## Descrição do Projeto

Este projeto é um sistema de gerenciamento de tarefas desenvolvido em Java utilizando Gradle como ferramenta de build. O sistema permite organizar tarefas em colunas, com funcionalidades para mover cards entre colunas, bloquear tarefas e gerenciar informações detalhadas sobre cada item.

## Tecnologias Utilizadas

- **Java**: Linguagem principal do projeto
- **Gradle**: Gerenciamento de dependências e build
- **MySQL**: Banco de dados relacional para persistência
- **Lombok**: Para redução de boilerplate code
- **JDBC**: Conexão com o banco de dados

## Funcionalidades Principais

- Gerenciamento de colunas (criação, ordenação, tipos)
- Criação e movimentação de cards entre colunas
- Bloqueio de cards com motivo e registro de data/hora
- Visualização detalhada de boards e cards
- Tratamento de exceções específicas (cards bloqueados, finalizados, entidades não encontradas)

## Estrutura do Projeto

O projeto está organizado em pacotes principais:

- `br.com.dio.dto`: Objetos de transferência de dados (DTOs)
- `br.com.dio.exception`: Classes de exceção customizadas
- `br.com.dio.persistence`: Configurações de persistência e banco de dados
  - `config`: Configurações de conexão
  - `converter`: Conversores de tipos (ex: OffsetDateTime)
  - `migration`: Estratégias de migração de banco

## Observação Sobre o Projeto
Foi o projeto do Decola Tech 2025 mais difícil pra mim até agora. Tive que fazer 100% acompanhando as aulas, pois quando tentava fazer "do meu jeito" sempre dava algum erro que não se resolvia de maneira alguma. Tentarei refazer posteriormente.

## Referências Bibliograficas
https://github.com/digitalinnovationone/board/tree/master
