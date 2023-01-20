<h1 align="center" background-color:"red"># Sistema_Resilia 👩🏼‍💻</h1>

## ✳  Proposta do projeto <br>
➥ A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.


Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem
e responder algumas perguntas com nosso modelo: <br>
➥ Existem outras entidades além dessas três? <br>
➥ Quais são os principais campos e tipos? <br>
➥ Como essas entidades estão relacionadas? 
<br>



### ✳ Respostas

###  Existem outras entidades além dessas três?

1. Sim foi adicionado entidades relacionadas a um sistema de Banco de Dados para uma instituição de ensino, sendo elas: 
Matricula, Disciplinas,Sala, Turma e Professor.


### Quais são os principais campos e tipos?

2. id_matricula, id_aluno, id_curso , id_professor  <br>
 "nome"   tipo:Varchar(20) <br>
 "data de inicio curso"  tipo : DATE <br>
 "id"  tipo: INT PK <br>
 


### Como essas entidades estão relacionadas?

3. Relação entre turma e aluno (N:N) <br>
Relação entre professor e turma (N:N) <br>
Relação entre turma e sala (1:1) <br>
Relação entre aluno e curso (N:N) <br>
Relação entre curso e disciplina (1:N) <br>
Relação entre turma e disciplina (N:1) <br>



## ✳ Extras
➥ Criar o banco de dados proposto e adicionar uma pasta chamada SQL com os arquivos.
 
 
 
## ✳ Modelo do Banco de Dados.

![DataBase](https://user-images.githubusercontent.com/113525688/213037984-65d221f1-ddbd-40e3-a08d-a7106d3070df.jpeg)



 ![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=%20Finalizado&color=GREEN&style=for-the-badge)
 
 <a href="https://www.linkedin.com/in/debora-santana-7959141a0/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
 <a href="https://www.instagram.com/debora_saantana_/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
