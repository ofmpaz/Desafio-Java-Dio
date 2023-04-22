# Desafio-Java-Dio

Matrícula de alunos na academia
Este é um sistema de matrícula de alunos em uma academia, implementado em Java utilizando os padrões de projeto Observer e seguindo as boas práticas do paradigma de Orientação a Objetos.

O sistema consiste em três classes principais: Aluno, Professor e Academia. A classe Aluno representa um aluno, contendo seus dados (peso, altura, idade, sexo). A classe Professor representa um professor, contendo seus dados (nome, telefone) e uma lista de alunos matriculados. A classe Academia é responsável por gerenciar as matrículas de alunos, mantendo uma referência para o professor e notificando os observadores (no caso, os inscritos na academia) quando há uma nova matrícula ou desmatrícula.

Como utilizar
Para utilizar o sistema, basta instanciar um objeto da classe Professor e passá-lo como parâmetro para um objeto da classe Academia. Em seguida, é possível realizar as operações de matrícula, desmatrícula e listagem de alunos através do objeto da classe Academia.

