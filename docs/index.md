<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/ciencia-da-computacao">Ciência da computação</a></h3>


<font size="+12"><center>
Sistema de Presenças
</center></font>

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Funcionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Enzo Guarnieri - 10410074
* Erika Borges Piaui - 10403716
* João Pedro Zavanela Andreu - 10410137
* Júlia Campolim de Oste - 10408802


# Descrição do Projeto

   O projeto visa a criação de um sistema capaz de controlar as presenças dos alunos da Escola Infinito. Esse sistema irá substituir o que, até então, era registrado apenas em papel.
   
   A escola possui apenas turmas do ensino Fundamental I (do primeiro ao quinto ano), cada turma possui cerca de 10 a 30 alunos, um professor responsável por todas as principais disciplinas (artes, ciências, geografia, história, matemática e português) e outros professores para as aulas de educação física e inglês. 
A chamada é realizada duas vezes todos os dias sendo a primeira no início das aulas e a segunda após o intervalo. Para obter aprovação, o aluno precisa ter comparecido a, pelo menos, 75% das aulas, caso contrário será reprovado.
  
   Para isso, o sistema deverá ter dois usuários em mente, os alunos e os professores, e cada um deles terá funções e privilégios diferentes na aplicação. Os usuários tidos como professores, devem ser capazes de registrar as faltas dos alunos duas vezes por dia (como descrito anteriormente). Os usuários alunos, devem ser capazes de visualizar as suas faltas ao entrar no sistema (tanto em número inteiro, quanto em porcentagem) para monitorar sua presença. 
   
   Por parte do sistema, é esperado que ele gere relatórios filtrados por atributos como data, ano do ensino, turma, professor, disciplina e/ou aluno, envie notificações em casos de faltas excessivas, possua fonte ajustável como recurso de acessibilidade e possa ser acessado através de qualquer navegador web.
  

# Análise de Requisitos Funcionais e Não-Funcionais

### Requisitos Funcionais:
  
[RF001] - Registrar faltas: o professor deve ser capaz de fazer o registro de faltas duas vezes por dia (no início das aulas e após o retorno do intervalo).

[RF002] - Gerar relatórios: o sistema deve ser capaz de gerar relatórios filtrados por atributos como data, ano do ensino, turma, professor, disciplina e/ou aluno.

[RF003] - Enviar notificações: em casos de faltas excessivas, o sistema deve ser capaz de enviar informes aos pais ou responsáveis do aluno (presença abaixo de 80%).

[RF004] - Acessibilidade: o sistema deve ser acessível para todos os usuários, tendo recursos como fonte ajustável.

[RF005] - Acesso multiplataforma: os usuários devem conseguir acessar o sistema a partir de qualquer navegador web.

[RF006] - Visualizar faltas: ao entrar no sistema, os alunos (e os pais/responsáveis) devem ser capazes de visualizar as faltas obtidas (tanto em número inteiro quanto em percentual).

[RF007] - Login: os usuários devem ter uma conta cadastrada no sistema.

>Obs.: cada turma deve ter um professor associado

### Requisitos Não-Funcionais:

[RNF001] - Segurança: o sistema deve possuir recursos de segurança como backup de dados e gerenciamento de acesso à internet.

[RNF002] - Responsividade: visualização clara e intuitiva para todos os tipos de dispositivos.

[RNF003] - Acessibilidade: talkback, alto contraste 

[RNF004] - Performance: o sistema deve ser capaz de executar suas funcionalidades de forma rápida e eficiente.

[RNF005] - Permissões do sistema: apenas os professores podem registrar as faltas e cada aluno só tem acesso ao seu próprio portal.

[RNF006] - Cópia de segurança: o sistema precisa gerar uma cópia de todos os dados periodicamente.

# Diagrama de Atividades
![Sistema de presença (2)](https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/146954304/dc7f9728-09b6-43b9-8a7e-50642021a221)

<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/146954304/b90c49c6-65ab-45db-a866-e7795ca0791e"
 width='60%' height='60%'>


https://lucid.app/lucidchart/09bf3d0f-0714-4774-8c14-1613e47d1285/edit?invitationId=inv_62353d02-d8a5-462d-ac49-aba2bbbf892d

https://lucid.app/lucidchart/ae7eb6ca-9d50-47fd-9099-b65f06538b90/edit?viewport_loc=-10%2C-10%2C1707%2C800%2C0_0&invitationId=inv_c103ba97-477f-4448-b843-19512f7281fc
# Diagrama de Casos de Uso
[UC001] - Entrar: Os usuários aluno, professor e pais/responsáveis são capazes de entrar no sistema usando usuário e senha.

[UC002] - Registrar faltas: O usuário professor é capaz de registrar a presença dos alunos.

[UC003] - Visualizar faltas: Os usuários aluno e pais/responsáveis são capazes de visualizar as faltas registradas em seu perfil.

[UC004] - Sair: Os usuários aluno, professor e pais/responsáveis são capazes de sair do sistema.

https://lucid.app/lucidspark/d65dbbed-831e-4c9a-99a7-d65d75cd2e5e/edit?viewport_loc=1280%2C2477%2C2048%2C984%2C0_0&invitationId=inv_002db528-4321-4766-96fe-4a00e58eb570
*&lt;Diagrama para visualizar o comportamento dos atores&gt;*

# Descrição dos Casos de Uso

*&lt;Descrição do comportamento entre os atores/resquisitos&gt;*

# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
