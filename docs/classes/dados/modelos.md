# Abordagens e Modelos

## Abordagens

A abordagem são as diferentes formas históricas de modelar os dados em um banco de dados, com a finalidade de estruturar e acessar os dados.

### Abordagem Hierárquica

* Dados em formato de árvore.

* Um nó raiz (ex: Filial) → ramificações (ex: Departamentos) → folhas (ex: Funcionários). -- colocar um diagrama

* Problema: rigidez → um filho só pode ter um pai.

![Abordagem Hierárquica](\docs\assets\images\ab_hierarquica.png)

### Abordagem em Rede

* Dados em forma de grafo (vários caminhos possíveis).

* Um registro pode estar ligado a vários outros. Exemplo: Um funcionário pode pertencer a vários projetos/departamentos.

* Mais flexível que o hierárquico, mas difícil de implementar já que os registros são ligados por links.

### Abordagem Relacional

* É a mais utilizada hoje em dia.

* Dados organizados em tabelas (linhas = registros, colunas = atributos).

* Exemplo: tabela CLIENTE (id, nome, telefone).

* Simples, flexível, linguagem padrão: SQL.

### Abordagem Orientada à Objetos

* Une programação orientada a objetos com bancos de dados.

* Guarda “objetos” que têm atributos (dados) e métodos (comportamentos).

* Permite herança, polimorfismo, encapsulamento.

#### Resumo

| Abordagem              | Como funciona                                    | Vantagens                                                                 | Desvantagens                                                               | Exemplos de uso/histórico                |
|-------------------------|-------------------------------------------------|---------------------------------------------------------------------------|----------------------------------------------------------------------------|------------------------------------------|
| **Hierárquica**         | Estrutura em **árvore**, um pai para cada filho | Simples de implementar quando há hierarquia clara; eficiente em consultas | Rigidez (um filho só pode ter um pai); difícil de alterar a estrutura      | IMS (IBM), aplicações antigas de governo |
| **Em Rede**             | Estrutura em **grafo**, filhos podem ter vários pais | Flexível, permite múltiplos relacionamentos; evita redundância            | Complexo de implementar e manter; consultas difíceis                       | IDMS, sistemas de manufatura e engenharia |
| **Relacional**          | Dados organizados em **tabelas (linhas e colunas)** | Fácil de entender e usar; linguagem padrão (SQL); modelo dominante        | Pode ser menos eficiente em dados muito complexos ou massivos (Big Data)   | Oracle, MySQL, PostgreSQL, SQL Server    |
| **Orientado a Objetos** | Dados como **objetos** (atributos + métodos)    | Integra com linguagens OO; lida bem com dados complexos                   | Pouco difundido comercialmente; curva de aprendizado maior                 | CAD, multimídia, sistemas de engenharia  |

## Modelos

Um modelo de banco de dados define a estrutura e os relacionamentos dos dados.

### Modelo Conceitual

### Modelo Lógico

### Modelo Físico

#### Resumo.2
