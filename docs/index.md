<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/ciencia-da-computacao">Ciência da computação</a></h3>


<font size="+12"><center>
Sistema de Presenças
</center></font>

**Conteúdo**

- [Autores](#autores)
- [Descrição do Projeto](#descrição-do-projeto)
- [Análise de Requisitos Funcionais e Não-Funcionais](#análise-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-casos-de-uso)
- [Descrição dos Casos de Uso](#descrição-dos-casos-de-uso)
- [Diagrama de Sequência](#diagrama-de-sequência)
- [Diagrama de Classes](#diagrama-de-classes)
- [Diagrama de Estados](#diagrama-de-estados)
- [Diagrama de Implantação](#diagrama-de-implantação)
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
  
   Para isso, o sistema deverá ter três usuários em mente, os alunos, os professores e os pais/responsáveis, sendo que cada um deles terá funções e privilégios diferentes na aplicação. Os usuários tidos como professores, devem ser capazes de registrar as faltas dos alunos duas vezes por dia (como descrito anteriormente). Os usuários alunos, devem ser capazes de visualizar as suas faltas ao entrar no sistema (tanto em número inteiro, quanto em porcentagem) para monitorar sua presença. Os usuários tipo pais/responsáveis, devem ser capazes de acompanhar a presença dos alunos vinculados à eles e de receber notificações caso seus filhos estejam prestes a reprovar por falta. Vale ressaltar que o usuário deverá estar cadastrado no sistema para poder entrar e, caso erre as credenciais mais de 5 vezes, sua conta deverá ser bloqueada até que o processo de recuperação de senha seja finalizado.
   
   Por parte do sistema, é esperado que ele gere relatórios filtrados por atributos como data, ano do ensino, turma, professor, disciplina e/ou aluno, envie notificações em casos de faltas excessivas, possua fonte ajustável como recurso de acessibilidade e possa ser acessado através de qualquer navegador web.
  

# Análise de Requisitos Funcionais e Não-Funcionais

### Requisitos Funcionais:
  
[RF001 - Registrar faltas]: o professor deve ser capaz de fazer o registro de faltas duas vezes por dia (no início das aulas e após o retorno do intervalo).

[RF002 - Gerar relatórios]: o sistema deve ser capaz de gerar relatórios filtrados por atributos como data, ano do ensino, turma, professor, disciplina e/ou aluno.

[RF003 - Enviar notificações]: em casos de faltas excessivas, o sistema deve ser capaz de enviar informes aos pais ou responsáveis do aluno (presença abaixo de 80%).

[RF004 - Acessibilidade]: o sistema deve ser acessível para todos os usuários, tendo recursos como fonte ajustável.

[RF005 - Acesso multiplataforma]: os usuários devem conseguir acessar o sistema a partir de qualquer navegador web.

[RF006 - Visualizar faltas]: ao entrar no sistema, os alunos (e os pais/responsáveis) devem ser capazes de visualizar as faltas obtidas (tanto em número inteiro quanto em percentual).

[RF007 - Entrar]: os usuários devem ter uma conta cadastrada no sistema.

[RF008 - Sair]: os usuários devem ser capazes de sair da sua conta quando desejarem.

[RF009 - Calcular faltas]: O sistema deverá calcular a porcentagem de faltas de um aluno toda vez que uma chamada for realizada.

[RF010 - Enviar notificações]: O sistema deverá enviar notificações para os pais/responsáveis de um aluno que estiver perto de reprovar por falta.

>Obs.: cada turma deve ter um professor associado

### Requisitos Não-Funcionais:

[RNF001 - Segurança]: o sistema deve possuir recursos de segurança como backup de dados e gerenciamento de acesso à internet.

[RNF002 - Responsividade]: visualização clara e intuitiva para todos os tipos de dispositivos.

[RNF003 - Acessibilidade]: talkback, alto contraste 

[RNF004 - Performance]: o sistema deve ser capaz de executar suas funcionalidades de forma rápida e eficiente.

[RNF005 - Permissões do sistema]: apenas os professores podem registrar as faltas e cada aluno só tem acesso ao seu próprio portal.

[RNF006 - Cópia de segurança]: o sistema precisa gerar uma cópia de todos os dados periodicamente.

[RNF007 - Usuário e/ou senha incorretos]: o sistema precisa enviar um e-mail de recuperação de senha para o usuário caso ele tenha errado as credenciais mais de 5 vezes ao tentar entrar no portal. Caso o usuário tenha errado suas credenciais mais de 5 vezes, deve ser bloqueado por novas tentativas até ter concluído a etapa de recuperação de senha.

# Diagrama de Atividades

<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/6d9b4db0-c8a4-46d0-a4d7-09ce81ef1499"
 width='90%' height='90%'></p>

<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/dd4f3593-6c70-4a38-bc7a-15196f5e1bb8"
 width='90%' height='90%'></p>

# Diagrama de Casos de Uso
[UC001 - Entrar]: Os usuários aluno, professor e pais/responsáveis são capazes de entrar no sistema usando usuário e senha.

[UC002 - Registrar faltas]: O usuário professor é capaz de registrar a presença dos alunos.

[UC003 - Visualizar faltas]: Os usuários aluno e pais/responsáveis são capazes de visualizar as faltas registradas em seu perfil.

[UC004 - Sair]: Os usuários aluno, professor e pais/responsáveis são capazes de sair do sistema.

[UC005 - Calcular porcentagem de faltas]: O sistema deverá calcular a porcentagem de faltas de um aluno toda vez que uma chamada for realizada.

[UC006 - Enviar notificações]: O sistema deverá enviar notificações para os pais/responsáveis de um aluno que estiver perto de reprovar por falta.

[UC007 - Usuário e/ou senha incorretos]: O sistema deverá enviar um e-mail de recuperação de senha para o usuário caso ele tenha errado as credenciais mais de 5 vezes.

<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/f26da456-ab87-437e-bc2b-8f604a2d2452)" width='90%' height='90%'></p>
 
# Descrição dos Casos de Uso

[UC001 - Entrar]<br><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/06a9b676-92f9-4175-ad0b-4d094be22ed2" width='60%' height='60%'><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/25dfbd46-583f-4c8f-bb4b-e76976c8d535" width='60%' height='60%'><br>

[UC002 - Registrar faltas]<br><br>
<center><img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/15968a95-ec80-431a-8b5d-46e92da23324" width='60%' height='60%'><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/fecbcd89-70b3-4abc-b14e-b5d38a5079fb" width='60%' height='60%'><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/f2ac688d-0268-490d-b5d8-4f478a1f144d" width='60%' height='60%'></center><br>

[UC003 - Visualizar faltas]<br><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/31c02df4-a26c-4801-b0a1-e98d7b5f261b" width='60%' height='60%'><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/617b6b77-a161-4aa6-8fc7-100005f4e1cd" width='60%' height='60%'><br>

[UC004 - Sair]<br><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/7aa825fc-6a98-443a-818a-659098156903" width='60%' height='60%'><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/32a82c37-add9-40dc-9e23-e632e6c45373" width='60%' height='60%'><br>

[UC005 - Calcular porcentagem de faltas]<br><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/7e419cc2-9f39-4204-9bfa-b90e07df20bd" width='60%' height='60%'>

[UC006 - Enviar notificações]<br><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/b1baae40-301b-4461-9382-7155899be77d" width='60%' height='60%'>

[UC007 - Usuário e/ou senha incorretos]<br><br>
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/63428392/9d04ae57-3704-435c-94d8-47d0258d4855" width='60%' height='60%'>

# Diagrama de Sequência

[UC001 - Entrar]<br><br>
<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/862d6fcb-0b01-404b-84c2-7262f537d7af"
 width='70%' height='70%'></p>

[UC002 - Registrar faltas]<br><br>
<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/77b07915-f1be-4dcb-a8c7-cf4b46d8e330"
 width='70%' height='70%'></p>

[UC003 - Visualizar faltas]<br><br>
<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/385a63b8-356b-4847-9063-ffc119c32979"
 width='70%' height='70%'></p>

[UC004 - Sair]<br><br>
<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/eedd602f-4431-40f5-a2e2-53d226c1f47c"
 width='70%' height='70%'></p>

[UC005 - Calcular porcentagem de faltas]<br><br>
<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/adf47213-0d37-4b36-8c4c-958758448d17"
 width='70%' height='70%'></p>

[UC006 - Enviar notificações]<br><br>
<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/8673a493-1867-4373-9530-885e65e7795b"
 width='70%' height='70%'></p>

[UC007 - Usuário e/ou senha incorretos]<br><br>
<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/63428392/a278a6d2-3ab3-4c16-bf0e-dd05c71bc717"
 width='70%' height='70%'></p>


# Diagrama de Classes
<p align="center">
<img src = "https://github.com/admiradores-do-theo/UML-Classroom-FCI/assets/161724552/47fc8f37-58c4-47bc-8b66-b8eb8ca69b0f"
 width='70%' height='70%'></p>
 
# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
