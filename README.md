Fitness Tracker

Este projeto foi desenvolvido durante a disciplina de Desenvolvimento Mobile, com foco no aprendizado da integração entre linguagens e na compreensão do funcionamento do Flutter.

Funcionalidades

Autenticação de Usuários: Permite criar contas e autenticar credenciais.

Gerenciamento de Exercícios: Modelos de exercícios definidos no backend.

Criação de Workouts: Seleção de exercícios para compor treinos personalizados.

Lista de Treinos: Workouts criados ficam armazenados e podem ser marcados como concluídos.

Planejamento Futuro: Integração com um banco de dados para armazenar treinos e progresso do usuário.

Tecnologias Utilizadas

Frontend

Flutter: Framework para desenvolvimento de aplicações móveis multiplataforma.

Dart: Linguagem de programação utilizada no Flutter.

Backend

Java 11: Linguagem utilizada para a API.

Spring Boot: Framework para desenvolvimento da REST API.

Spring Security: Implementação de autenticação e controle de acesso.

JWT (JSON Web Token): Autenticação baseada em tokens.

Maven: Gerenciador de dependências do projeto.

Estrutura do Backend

O backend foi desenvolvido utilizando Spring Boot, seguindo uma arquitetura REST. Atualmente, ele inclui os seguintes modelos:

Usuário: Responsável por armazenar informações de login e autenticação.

Exercício: Representa os exercícios disponíveis para os treinos.

Workout: Modelo que agrupa vários exercícios, criando um treino personalizado para o usuário.

Atualmente, os workouts são armazenados diretamente no código, mas a ideia é que no futuro eles sejam persistidos em um banco de dados, permitindo que os usuários acompanhem seu progresso.









