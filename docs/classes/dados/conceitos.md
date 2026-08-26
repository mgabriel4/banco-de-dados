# Conceitos Básicos

## Banco de Dados

**O que é um banco de dados?**

Um banco de dados é uma coleção organizada de dados, que representa algo do mundo real. O banco de dados serve para guardar informações de forma estruturada, para que elas possam ser consultadas, atualizadas e analisadas facilmente. Exemplos de dados são:

* Em uma loja, os dados podem ser clientes, produtos e vendas.

* Em uma faculdade, podem ser alunos, cursos e notas.

É importante compreender também a diferença entre dado e informação.

O dado em si não consegue te dar nenhum insight, pois é algo bruto, sem interpretação. Exemplo: “Maria”, “Rua X, nº 100”.

Já a informação é quando o dado ganha significado para um usuário. Exemplo: “Maria mora na Rua X, nº 100”.

Ou seja, dado = elemento isolado, informação = dado com contexto.

## Componentes de um Sistema de Banco de Dados

Um sistema de banco de dados não é só o banco em si. Ele é formado por:

1. **Dados** – são as informações armazenadas, o conteúdo em si.
    * Podem ser acessados por um usuário (mono) ou muitos ao mesmo tempo (multi).

    * Precisam ser integrados (não duplicados) e compartilhados.

2. **Hardware** – equipamentos que armazenam e processam dados. Ex: HDs, servidores, memória.

3. **Software** – programas que gerenciam os dados. Ex: Oracle, MySQL, SQL Server, PostgreSQL.

4. **Usuários**:

    * DBA (Administrador de Banco de Dados): cuida da segurança, desempenho e manutenção.

    * Administrador de Dados: define regras de como os dados devem ser armazenados.

    * Desenvolvedores: criam programas que usam o banco.

    * Usuários Finais: acessam o banco por meio de sistemas (ex: site do banco).

## Objetivos e Vantagens de um Banco de Dados

### Objetivos

* Esconder a complexidade interna (abstração).

* Garantir independência entre dados e aplicações.

### Vantagens

* Compartilhamento – vários programas usam os mesmos dados.

* Menos redundância – sem dados duplicados desnecessários.

* Menos inconsistência – evita dados divergentes (ex: endereço atualizado só em parte do sistema).

* Transações seguras – garante que operações críticas (ex: transferência bancária) sejam realizadas corretamente.

* Integridade e segurança – dados corretos e protegidos contra acessos indevidos.

## Como funciona um SGBD?

O SGBD (Sistema Gerenciador de Banco de Dados) é o software que:

* Define os dados → usa DDL (Data Definition Language).

* Manipula os dados → usa DML (Data Manipulation Language: SELECT, INSERT, UPDATE, DELETE).

* Otimiza consultas → escolhe a forma mais eficiente de buscar dados.

* Garante segurança e integridade.

* Controla concorrência → permite que muitos usuários usem o banco ao mesmo tempo sem erro.

* Mantém metadados (dicionário de dados = dados sobre os dados).

* Exemplos de SGBDs: MySQL, PostgreSQL, Oracle, SQL Server.

## Arquitetura de Banco de Dados

Três níveis de visão dos dados:

1. Externo (usuário) → o que cada usuário vê (ex: um cliente só vê sua conta).

2. Conceitual (comunidade) → visão global dos dados (ex: todas as contas de todos os clientes).

3. Interno (físico) → como os dados realmente são armazenados no disco.

Essa separação garante a independência entre usuário, modelo de dados e armazenamento físico.