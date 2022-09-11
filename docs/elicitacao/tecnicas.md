# Técnicas

Nesse projeto foram utilizadas algumas técnicas para levantamento de requisitos, técnicas essas que serão apresentadas e explicadas nessa seção.

## 1. Introspecção

### 1.1 Definição

A técnica de introspecção se baseia em imaginar que tipo de sistema o usuário iria querer se estivesse executando um determinada tarefa, utilizando determinado
equipamento, entre outros. Ou seja, imaginar que propriedades um sistema deveria possuim de forma a obter sucesso. Assim, o engenheiro de requisitos utiliza sua imaginação
como ferramenta prioritária, se desenhando como usuário do sistema.

### 1.2 Metodologia

Foram selecionados dois participantes do grupo para fazer a introspecção, elas serão feitas separadamente e depois os resultados serão comparados entre os participantes.

### 1.3 Participantes

- Cícero Fernandes
- Bernardo Pissuti

### 1.4 Passos

- Fazendo login no app
- Procurando por um página
- Escrevendo na página
- Tentando voltar a uma versão antiga da página
- Organizando as páginas nos workspaces

### 1.5 Resultados

Nessa seção serão apresentados os requisitos funcionais, mostrados na _Tabela 1_, e não funcionais, mostrados na _Tabela 2_, elicitados como resultado do método de introspecção.

| Código  | Requisito                                                                                                  |
|---------|------------------------------------------------------------------------------------------------------------|
| RF1     | O usuário deve poder criar uma página.                                                                     |
| RF2     | O usuário deve poder encontrar uma página criada previamente.                                              |
| RF3     | O usuário deve poder editar uma página.                                                                    |
| RF4     | O usuário deve poder excluir uma página quando desejado.                                                   |
| RF5     | O usuário deve poder ser autenticado no sistema.                                                           |
| RF6     | O usuário deve poder pesquisar as páginas já criadas pelo nome delas.                                      |
| RF7     | O usuário deve poder escolher em qual fonte editar suas páginas.                                           |
| RF8     | O usuário deve poder escolher entre o tamanho de fonte grande e pequena.                                   |
| RF9     | O usuário deve poder escolher se o texto ocupa toda a largura da página ou se fica centralizado na página. |
| RF10    | O usuário deve poder ver o histórico de alterações da página.                                              |
| RF11    | O usuário deve poder favoritar a página.                                                                   |
| RF12    | O usuário deve poder compartilhar o link para a página.                                                    |
| RF13    | O usuário deve poder escolher a aparência do sistema.                                                      |
| RF14    | O usuário deve poder escolher uma foto de identificação para cada página.                                  |
| RF15    | O usuário deve poder escolher uma foto de identificação para o workspace.                                  |
| RF16    | O usuário deve poder ter quantos workspaces desejar.                                                       |
| RF17    | O usuário deve poder escolher entre opções de templates para uma página criada.                            |
| RF18    | O usuário deve poder ver o histórico de páginas deletadas.                                                 |
| RF19    | O usuário deve poder importar páginas de outras plataformas ou aplicativos.                                |
| RF20    | O usuário deve poder adicionar fotos a página.                                                             |
| RF21    | O usuário deve poder referenciar outras páginas dentro de uma página.                                      |
| RF22    | O usuário deve poder adicionar outros perfis para editar uma página.                                       |
| RF23    | O usuário deve poder adicionar uma legenda às imagens da página.                                           |
| RF24    | O usuário deve poder escrever comentários nas páginas.                                                     |
| RF25    | O usuário deve poder criar blocos de markdown para editar as páginas.                                      |
| RF26    | O usuário deve poder escolher entre opções de edição do bloco de markdown.                                 |

_Tabela 1: Requisitos funcionais_

| Código  | Requisito                                                                     |
|---------|-------------------------------------------------------------------------------|
| RNF1    | Deve ser possível instalar a aplicação em dispositivos android                |
| RNF2    | A interface do sistema deve ser responsiva                                    |
| RNF3    | Software deve estar disponível no mínimo 98% do tempo.                        |
| RNF4    | A incidência de falhas operacionais deve não exceder 3 a cada 1000 operações. |

_Tabela 2: Requisitos não funcionais_

## 2. Questionário

### 2.1 Definição

Questionário é uma técnica que pode ser utilizada para coletar dados, sendo uma técnica barata, rápida e com pouco esforço.

### 2.2 Objetivo

Levantar informações acerca dos usuários que utilizam o aplicativo notion, de uma forma quantitativa.

### 2.3 Metodologia

Buscamos validar se o usuário utiliza o notion para coletar dados somente destes que a utilizam. Utilizamos o formato de questionário típico descrito por Sharp e coautoras (2007) que busca perguntas demográficas seguidas de perguntas sobre a experiência do usuário. e também o formato de perguntas fechadas, buscando uma maior agilidade na avaliação dos resultados. Utilizamos a escala Likert para obter a satisfação do usuário quanto a funcionalidade, em algumas das perguntas.

Após definir o escopo do Questionário fizemos 9 questões no Google Forms, Sendo 7 de múltipla escolha e somente 2 permitindo selecionar mais de uma opção, a fim de evitar o cansaço na realização do formulário.

### 2.4 Questões

#### 1. Já utilizou o aplicativo Notion?

| ![image](https://user-images.githubusercontent.com/60429513/178844427-3c55a468-e2e0-4618-b207-2de9e03097e1.png) |
|-----------------------------------------------------------------------------------------------------------------|
| Figura 1: questão 1; Fonte: autoria própria.                                                                    |

Com o objetivo de analisar quantas pessoas já utilizaram ou não o aplicativo, refinando a pesquisa e direcionando o usuário alvo.

#### 2. Qual sua faixa etária?

| ![image](https://user-images.githubusercontent.com/60429513/178844474-9c82c79e-ed35-43cd-8b97-d209bb525616.png) |
|-----------------------------------------------------------------------------------------------------------------|
| Figura 2: questão 2; Fonte: autoria própria.                                                                    |

Com objetivo de conhecer mais sobre a idade dos usuários que utilizam o aplicativo.

#### 3. Em quais dispositivos costuma utilizar o Notion?

| ![image](https://user-images.githubusercontent.com/60429513/178844508-a33b5056-4025-408e-a50a-d925ac4071a5.png) |
|-----------------------------------------------------------------------------------------------------------------|
| Figura 3: questão 3; Fonte: autoria própria.                                                                    |


Com o objetivo de conhecer como os usuários fazem uso do aplicativo.

#### 4. Quais funções do app você considera essenciais?

| ![image](https://user-images.githubusercontent.com/60429513/178844536-19ffa890-f06e-4885-8b7a-822f434ab013.png) |
|-----------------------------------------------------------------------------------------------------------------|
| Figura 4: questão 4; Fonte: autoria própria.                                                                    |


Pergunta diferente das anteriores, agora temos o foco de entender mais sobre o aplicativo e o que faz os usuários quererem utilizar o notion.

#### 5. Utiliza com frequência aplicativos do tipo "lista de tarefas" para organizar o dia a dia?

| ![image](https://user-images.githubusercontent.com/60429513/178844570-54fe96ed-d25e-495f-aeec-1edc45045c45.png) |
|-----------------------------------------------------------------------------------------------------------------|
| Figura 5: questão 5; Fonte: autoria própria.                                                                    |



Com o objetivo de conhecer se os usuários recorrem a softwares de gerenciamento de tarefas para se organizar.

#### 6. A liberdade de utilizar novos templates facilita na organização da pessoal e/ou equipe?

| ![image](https://user-images.githubusercontent.com/60429513/178844608-41c01fae-0da5-4f5b-8256-376efcfa50e0.png) |
|-----------------------------------------------------------------------------------------------------------------|
| Figura 6: questão 6; Fonte: autoria própria.                                                                    |


Com o objetivo de induzir novos usuários a tentarem criar seus proprios templates e analisar o impacto que uma funcionalidade especifica tem sobre os usuários.

#### 7. O Notion melhorou a organização do seu time ou pessoal?


| ![image](https://user-images.githubusercontent.com/60429513/178844642-47af25b4-6719-49e6-865b-fca533811258.png) |
|-----------------------------------------------------------------------------------------------------------------|
| Figura 7: questão 7; Fonte: autoria própria.                                                                    |


Com o objetivo de analisar o impacto do notion na organização de time e das pessoas.

#### 8. Com qual frequência utiliza o Notion?

| ![image](https://user-images.githubusercontent.com/60429513/178844673-383af217-3d20-467f-ae19-8df4f39b4098.png) |
|-----------------------------------------------------------------------------------------------------------------|
| Figura 8: questão 8; Fonte: autoria própria.                                                                    |

Com o objetivo de analisar a presença do aplicativo notion no dia a dia dos usuários

#### 9. Qual versão do Notion você utiliza?

| ![image](https://user-images.githubusercontent.com/60429513/178844706-ec635a0d-9283-4d8c-8be4-6438f1a2a1d1.png) |
|-----------------------------------------------------------------------------------------------------------------|
| Figura 9: questão 9; Fonte: autoria própria.                                                                    |


Com o objetivo de analisar o perfil dos usuários que buscam mais funcionalidades no app e os que se contentam com o gratuito.

#### 10. Quanto numa escala de 1 a 5 o Notion atendeu suas expectativas


| ![image](https://user-images.githubusercontent.com/60429513/178844741-fc9e1869-85c1-4bb3-9a25-898c94e5e2dc.png) |
|-----------------------------------------------------------------------------------------------------------------|
| Figura 10: questão 10; Fonte: autoria própria.                                                                  |


Com o objetivo de analisar o quão o notion auxilia na vida dos usuários.

### 2.5 Resultados

Nessa seção serão apresentados os resultados da técnica de questionário, mostrados na tabela 3 e 4.

| Código | Requisito                                                           |
| ------ | ------------------------------------------------------------------- |
| RF1    | O usuário deve poder ter uma agenda para visualizar afazeres do dia |

_Tabela 3: Requisitos funcionais elicitados_

| Código | Requisito                             |
| ------ | ------------------------------------- |
| RNF1   | O aplicativo deve ser cross-plataform |

_Tabela 4: Requisitos não funcionais elicitados_

### 2.6 Link para o formulário

https://forms.gle/jcfPwYnpMMMfXKDRA

## 3. Brainstorming

### 3.1 Introdução

O brainstorming fornece informações sobre os tipos de conteúdos e características que os usuários querem e desejam em um
produto(Courage e Baxter, 2005)

### 3.2 Sessão 1

#### 3.2.1 Método

A sessão de brainstorming foi realizada de 21:20 à 21:30 do dia 11 de julho de 2022. O moderador (Bernardo Pissutti), 
juntamento com mais 3 membros da equipe(Guilherme Brito, Leonardo, Arthur) realizaram o Brainstorming com o auxilio da 
ferramenta Miro. As conclusões podem ser obsevadas na _Figura 11_ interativa abaixo.

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVOqie_Mc=/?moveToViewport=69,-928,2872,1300&embedId=975743771421" frameborder="0" scrolling="no" allowfullscreen></iframe>

_Figura 11: sessão 1 de brainstorming; Fonte: autoria própria._

#### 3.2.2 Resultados

Nessa seção serão apresentados os resultados da técnica de brainstorming, mostrados na _Tabela 3_ e _Tabela 4_.

| Código | Requisito                                                                     |
| ------ | ----------------------------------------------------------------------------- |
| RF1    | O usuário deve poder criar Formulas matemáticas                               |
| RF2    | O usuário deve poder criar seu próprio quadro kanban personalizado            |
| RF3    | O usuário pode escrever blocos de código                                      |
| RF4    | O usuário deve ser informado da situação do clima em sua região               |
| RF5    | O usuário poderá usar templates compartilhar disponibilizados pela comunidade |

_Tabela 5: Requisitos funcionais_

| Código | Requisito                                                          |
| ------ | ------------------------------------------------------------------ |
| RNF1   | As formulas matemáticas devem seguir o formato LaTex               |
| RNF2   | A sintaxe dos códigos deve seguir uma das linguagens mais recentes |

_Tabela 6: Requisitos não funcionais_

### 3.3 Sessão 2


#### 3.3.1 Método

Essa sessão de brainstorming foi realizada de 11:39 à 11:47 do dia 10 de setembro de 2022, com o objetivo de elicitar 
requisitos de funcionalidade não implementadas no app do Notion. O moderador (Bernardo Pissutti), juntamento com mais 
2 membros da equipe(Cicero Fernandes e Leonardo Vitoriano) realizaram o brainstorming com o auxilio da ferramenta Miro. 
As conclusões podem ser obsevadas na _Figura 12_ interativa abaixo.

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVPY-lE6Y=/?moveToViewport=-1125,-532,1667,754&embedId=676466904782" frameborder="0" scrolling="no" allowfullscreen></iframe>

_Figura 12: sessão 2 de brainstorming; Fonte: autoria própria._

#### 3.3.2 Resultados

Nessa seção serão apresentados os resultados da técnica de brainstorming, mostrados na _Tabela 7_.

| Código | Requisito                                                                                     |
|--------|-----------------------------------------------------------------------------------------------|
| RF1    | O usuário deve poder usar mesa e lápis digital a fim de editar meu caderno                    |
| RF2    | O usuário deve poder visualizar próximas página por uma seta que guia o usuário à horizontal  |
| RF3    | O usuário deve poder visualizar os topicos compartilhados pela comunidade através de uma guia |
| RF4    | O usuário deve poder adicionar capas aos cadernos                                             |
| RF5    | O usuário deve poder escolher entre templates de capas                                        |
| RF6    | O usuário deve poder categorizar seus cadernos em tópicos                                     |

_Tabela 7: Requisitos funcionais_

#### 3.3.3 Vídeo

<iframe width="560" height="315" src="https://www.youtube.com/embed/to1-TVr84rQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Referências Bibliográficas

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. 50 slides. Material apresentado para a disciplina
de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

Engenharia de requisitos: software orientado ao negócio de Carlos Eduardo Vazquez, Guilherme Siqueira Simões - capitulo 7;

Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.R.

## Histórico de Versões

| Versão | Data       | Descrição                                 | Autor             | Revisor  |
|--------|------------|-------------------------------------------|-------------------|----------|
| 1.0    | 13/07/2022 | Adição da técnica de introspecção         | Cícero Fernandes  | Leonardo |
| 1.1    | 13/07/2022 | Adição da técnica de questionário         | Arthur José       | Nicolas  |
| 1.2    | 13/07/2022 | Adição da técnica de brainstorming        | Bernardo Pissutti | Todos    |
| 1.3    | 24/07/2022 | Melhorando a documentação da introspecção | Bernardo Pissutti | -        |
| 1.4    | 10/09/2022 | Documentando a sessão 2 do brainstorming  | Bernardo Pissutti | -        |
