# Gerenciamento Universitário

Um sistema de gerenciamento universitário desenvolvido como parte do curso de Modelagem e Banco de Dados. Este projeto utiliza Java e MySQL para criar um sistema robusto de gerenciamento de informações acadêmicas, incluindo dados de alunos, cursos, disciplinas e muito mais.

## Visão Geral do Projeto

O objetivo deste projeto é criar uma aplicação funcional que simule o gerenciamento de uma universidade, permitindo a manipulação de informações essenciais, como:

- Cadastro e gerenciamento de alunos.
- Cadastro e gerenciamento de professores.
- Gerenciamento de cursos e disciplinas.
- Matrículas e organização acadêmica.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal do projeto.
- **MySQL**: Banco de dados relacional para armazenamento de informações.
- **Maven**: Gerenciador de dependências e automação de builds.
- **Spring Boot**: Framework para simplificar o desenvolvimento de aplicações Java.

## Estrutura do Projeto

A estrutura principal do projeto é organizada da seguinte forma:

- **src/**: Contém o código-fonte da aplicação.
  - **main/**: Arquivos principais do aplicativo.
  - **test/**: Arquivos de teste para validar as funcionalidades.
- **pom.xml**: Arquivo de configuração do Maven.
- **HELP.md**: Documentação adicional sobre o projeto.
- **.gitignore**: Arquivo para ignorar arquivos desnecessários no controle de versão.

## Funcionalidades Principais

1. **Cadastro de Alunos**: Permite adicionar, editar e remover alunos.
2. **Cadastro de Professores**: Permite gerenciar informações de professores.
3. **Gerenciamento de Cursos e Disciplinas**: Controle completo sobre o currículo acadêmico.
4. **Matrículas**: Relaciona alunos a cursos e disciplinas.

## Requisitos de Instalação

Certifique-se de ter as seguintes ferramentas instaladas no seu sistema:

- **Java JDK 8 ou superior**
- **MySQL Server**
- **Maven**
- **Git**

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/gerenciamento-universitario.git
   cd gerenciamento-universitario
   ```

2. Configure o banco de dados:
   - Crie um banco de dados no MySQL.
   - Atualize o arquivo `application.properties` com as credenciais do seu banco.

3. Compile e execute o projeto usando Maven:
   ```bash
   ./mvnw spring-boot:run
   ```

4. Acesse o sistema:
   Abra o navegador e acesse: [http://localhost:8080](http://localhost:8080)

## Exemplos de Uso

### Cadastro de Aluno

```sql
INSERT INTO alunos (nome, matricula, curso) VALUES ('João Silva', '2024001', 'Ciência da Computação');
```

### Listagem de Disciplinas

```sql
SELECT * FROM disciplinas WHERE curso = 'Engenharia';
```

## Contribuição

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. Faça um fork do repositório.
2. Crie um branch para sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Realize suas alterações e faça um commit:
   ```bash
   git commit -m "Minha nova feature"
   ```
4. Envie para o repositório remoto:
   ```bash
   git push origin minha-feature
   ```
5. Abra um pull request no GitHub.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.





