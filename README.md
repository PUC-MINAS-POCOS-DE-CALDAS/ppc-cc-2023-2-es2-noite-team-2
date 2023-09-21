# Sistema de Gerenciamento de Matrículas da PUC

O Sistema de Gerenciamento de Matrículas da PUC é uma aplicação desenvolvida para facilitar o processo de matrícula de alunos em disciplinas oferecidas pela Pontifícia Universidade Católica (PUC). Este sistema permite aos alunos se matricularem em disciplinas de acordo com sua grade curricular, garantindo que as regras de pré-requisitos e conflitos de horários sejam respeitadas.

## Funcionalidades Principais

- Cadastro de Professores: Registre informações sobre os professores, incluindo nome, número de identificação, especialização e disponibilidade de horários.

- Cadastro de Disciplinas: Registre informações sobre as disciplinas, como nome, código, carga horária e pré-requisitos.

- Cadastro de Cursos: Crie cursos com seus respectivos códigos e liste as disciplinas obrigatórias para cada curso.

- Matrícula de Alunos: Permita que os alunos se matriculem em disciplinas disponíveis para seu curso, com validação automática de pré-requisitos e conflitos de horários.

- Alocação Automática de Professores: O sistema aloca automaticamente professores para as disciplinas, considerando a disponibilidade de horários dos professores e evitando conflitos.

- Grade de Horários: Mantenha uma grade de horários das 7:00 da manhã às 22:30, todos os dias da semana, para alocar as disciplinas.

## Regras de Negócio

- Um professor não pode ser alocado em dois horários conflitantes, mesmo em disciplinas diferentes.
  
- Um aluno não pode alocar duas matérias que conflitem no horário.

## Desenvolvido por Rodrigo Franco de Melo Nogueira, Jeferson Henrique Pereira e Thiago Junio Saraiva
- Este arquivo `README.md` fornece uma visão geral do projeto, suas funcionalidades principais. 
