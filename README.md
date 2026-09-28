ACADEMIA V5

O que é este projeto?

O Academia V5 é um sistema feito em PHP que representa o funcionamento básico de uma academia. O projeto foi desenvolvido para colocar em prática os conceitos de Programação Orientada a Objetos.

Qual problema ele procura representar?

O sistema representa algumas situações que podem acontecer em uma academia, como alunos fazendo matrículas, escolhendo planos, realizando pagamentos e tendo treinos com diferentes exercícios.

A ideia é organizar essas informações através de classes e objetos, deixando cada parte do sistema responsável por uma função.

Como ele foi desenvolvido?

O projeto foi desenvolvido em PHP utilizando classes para representar as partes principais de uma academia.

Cada classe possui suas próprias informações e funções. O arquivo index.php é utilizado para criar os objetos e mostrar como eles funcionam juntos.

A estrutura funciona basicamente assim:

Pessoa -> informações básicas de uma pessoa
Aluno -> representa um aluno
Professor -> representa um professor
Plano -> representa um plano da academia
Matricula -> relaciona um aluno com um plano
Treino -> representa um treino
Exercicio -> representa os exercícios de um treino
Pagamento -> representa um pagamento

Principais funcionalidades

- Criar e exibir alunos
- Criar professores
- Criar planos
- Fazer matrículas
- Alterar o plano de uma matrícula
- Cancelar uma matrícula
- Criar treinos
- Adicionar exercícios aos treinos
- Registrar e realizar pagamentos

Tecnologias utilizadas

- PHP -> linguagem utilizada para desenvolver o sistema
- Git -> utilizado para controlar as versões do projeto
- GitHub -> utilizado para armazenar e compartilhar o projeto

Conceitos de Programação Orientada a Objetos

Classes e objetos -> cada parte importante da academia é representada por uma classe e seus objetos

Encapsulamento -> os dados das classes são protegidos e acessados através de métodos

Herança -> Aluno e Professor utilizam características que vêm da classe Pessoa

Construtores -> utilizados para criar os objetos já com suas informações

Métodos -> representam ações que os objetos podem realizar, como realizar um pagamento ou cancelar uma matrícula

Relacionamento entre objetos -> diferentes classes trabalham juntas. Por exemplo, uma Matricula possui um Aluno e um Plano, enquanto um Treino possui um Professor e vários Exercicios

Estrutura do projeto

Pessoa.php -> informações básicas de uma pessoa
Aluno.php -> representa um aluno
Professor.php -> representa um professor
Plano.php -> representa um plano
Matricula.php -> representa uma matrícula
Exercicio.php -> representa um exercício
Treino.php -> representa um treino
Pagamento.php -> representa um pagamento
index.php -> executa e demonstra o funcionamento do sistema

O projeto foi feito principalmente para praticar Programação Orientada a Objetos utilizando um exemplo de um sistema de academia.
