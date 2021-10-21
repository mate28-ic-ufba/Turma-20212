# Diário de Luana

## 03/09/21

* Seleção do diário [Star_book](https://github.com/hashirshoaeb/star_book) para reconhecimento técnico.
* Realização da [Atividade 02](https://github.com/mate28-ic-ufba/turma-20212/blob/main/atividade01/luana.md) - descrição e reconhecimento inicial do diário selecionado.


## 11/09/21
* Seleção do projeto [SpotBugs](https://awesomeopensource.com/project/spotbugs/spotbugs) para reconhecimento técnico e contribuição.
* Motivos: 
  1. O projeto é desenvolvido na linguagem Java e utiliza a biblioteca _Java_Parser_ para realizar a análise estática de códigos-fonte. Possuo conhecimento sobre o uso dessas tecnologias, o que pode facilitar meu aprendizado e contribuibuições no projeto. 
  2. O repositório do projeto no GitHub possui issues com label `good first issue`, o que pode ser um bom ponto de partida para contribuir com o projeto.
  3. Conhecendo o FindBugs, antecessor do SpotBugs, penso que posso reutilizar ou aprender com suas features para evoluir a ferramenta [JNose Test](https://github.com/arieslab/jnose) (uso no projeto de doutorado).      

## 14/09/21
* Leitura dos textos sobre Licenças de Software.
* Anotações:
  1. O SpotBugs é distribuído sob a licença LGPL 2.1 (Lesser GNU Public License LGPL 2.1).
  2. LGPL - Copyleft: qualquer trabalho derivado deve ser distribuído sob a mesma licença que o original. 
  3. A JNose é distribuída sob a licença GPL 3.0, então eu posso reutilizar trechos do SpotBugs sob licença GPL 3.0. (?) 
  4. Curiosidade sobre interações com licensas usadas em outros artefatos. Por exemplo, creative-commons: "While we recommend against using a CC license on software itself, CC licenses may be used for software documentation, as well as for separate artistic elements". (?)

## 24/09/21 e 25/09/21
*  Realização da [Atividade 04](https://github.com/mate28-ic-ufba/turma-20212/tree/main/atividades/luana/atividade04.md) - Quais as principais características do projeto OSS escolhido?
*  Como o SpotBugs foi desenvolvido com base no FindBugs, busquei pelo intervalo onde um foi descontinuado e o outro teve início. 
*  Utilizei a ferramenta [CK](https://github.com/mauricioaniche/ck) para contabilizar a quantidade de classes, linhas, e métodos.

## 01/10/21
* Participação CBSoft - OpenScienSE (27 de setembro a 01 de outubro).
* Realização da primeira parte da [Atividade 05](https://github.com/mate28-ic-ufba/turma-20212/tree/main/atividades/luana/atividade05.md).
* Procurei pela documentação de usuários e contribuidores para responder as questões.
* Identifiquei que posso contribuir com o suporte da documentação em PT-BR. Atualização: focarei nas issues sobre documentação.
* Aprender sobre as ferramentas utilizadas para gerar a documentação.

## 04/10/21
* Identifiquei algumas issues sobre documentação (good first issue) nas quais posso trabalhar.
  - [Issue 1164](https://github.com/spotbugs/spotbugs/issues/1164): Adição de exemplos sobre como usar regras findsecbugs no SpotBugs.
  - [Issue 540](https://github.com/spotbugs/spotbugs/issues/540): Configuração maven para utilização das regras findsecbugs no SpotBugs.

## 06/10/21
* Investigação da issue 540:
  - Seleção do projeto [commons-io](https://github.com/apache/commons-io) para executar o SpotBugs e entender como funciona.
  - Configuração do pom.xml para a adição do SpotBugs.
  - Configuração do pom.xml para adição do plugin findsecbugs.
* Solução de como integrar o findsecbugs com SpotBugs é similar a: https://github.com/find-sec-bugs/find-sec-bugs/wiki/Maven-configuration.
* Execução da ferramenta: ![SpotBugsExecution](https://drive.google.com/uc?export=view&id=1-RdZfB1p3v9ZC-3Ra2AlWo5OAhqqjwMX)
* Aprendizado sobre as ferramentas utilizadas para gerar a documentação. Estou seguindo o tutorial [ReadTheDocs](https://docs.readthedocs.io/en/stable/tutorial/).
  - [X] Read the docs tutorial: fork do projeto [ReadTheDocs](https://github.com/luana-martins/ReadTheDocs.git), customização da build e versionamento.
  - [X] Getting started with Sphinx.
  - [X] How-to guides.

## 14/10/21
- Leitura de textos relacionados ao tema "Aspectos Sociais de FLOSS".
- Elaboração de perguntas para a apresentação do Antônio Terceiro. 

## 18/10/21
- ThrawnCA contribuidor do SpotBugs respondeu ao meu comentário na issue 540. 
- Terminei o os passos que estabeleci para aprender sobre o ReadTheDocs.

## 19/10/21
- Apenas para treinamento!!
    - Criei uma documentação para a ferramenta [JNose Test](https://jnose.readthedocs.io/en/latest/index.html) usando o ReadTheDocs e submeti um PR.
    - Como a JNose Teste é desenvolvida pelo grupo de pesquisa do qual faço parte, me senti mais confortável em treinar nele primeiro para depois fazer a correção da issue do SpotBugs. 
    - Fiquei contente com o resultado e estou me sentindo mais segura para contribuir com o SpotBugs :smiley:

## 20/10/21 e 21/10/21
- Fiz a correção da issue 540 do SpotBugs.
- Submeti o PR [1758](https://github.com/spotbugs/spotbugs/pull/1758).
- Os revisões solicitaram algumas modificações.
- Melhorei meu PR com as sugestões dos revisores.