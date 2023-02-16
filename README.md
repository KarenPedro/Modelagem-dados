# Modelagem e banco de dados 

Trabalho acadêmico cujo a proposta é desenvolver um banco de dados para uma escola.
Durante o projeto foi desenvolvido um modelo conceitual e lógico.

sobre o banco de dados:
- Existem outras entidades além dessas três (curso, turma, aluno)?               
  As entidades do modelo proposto são: 
  - curso
  - turma
  - disciplina
  - aluno
  - professor
  
</br>
<img alt="modelo conceitual" width="100%" src="https://github.com/KarenPedro/Modelagem-dados/blob/main/My%20First%20Board.jpg" />

- Quais são os principais campos e tipos?                     
  os principais campos que distinguem as entidades são as chaves primárias representadas pelas colunas com o prefixo id:
  - id_curso 
  - id_turma
  - id_disciplina
  - id_aluno
  - id_professor

</br>

- Como essas entidades estão relacionadas?        
  *curso* tem *turma*,              
  *turma* possui *disciplina*,            
  *disciplina* possui *professor* que comanda a *turma*,                  
  *aluno* pertence a *turma*.
