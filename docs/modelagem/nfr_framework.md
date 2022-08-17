# NFR Framework

## 1. Introdução

NFR framework é um framework utilizado para manipular Requisitos Não-Funcionais expressando-os, conceitual e
individualmente, por meio dos ditos <i>softgoals</i> - objetivos pouco precisos quanto à suas definição e
seus critérios de satisfação - e grafica e coletivamente, através do chamado <i>SIG</i> (grafo de interdependência de
softgoals).

Em termos práticos, objetiva decompor os requisitos não funcionais em níveis menores, aumentando sua granulidade, bem
como criando inter-relacionamentos entre suas representações (<i>softgoals</i>), o que
facilita a compreensão e a tarefa de priorização.

## 2. Legenda

Os softgoals se subdividem em três grupos; enquanto a definição dos relacionamentos entre eles, as chamadas <i>
interdependências</i>, se ramificam em dois e os procedimentos de avaliação em seis.

### 2.1 Softgoals

#### NFR

Representa os Requisitos Não-Funcionais e tem sua representação gráfica na _Figura 1_.

| Figura 1: Softgoal NFR               |
|--------------------------------------|
| ![image](../_media/softgoal_nfr.png) |
| Fonte: (CHUNG et al., 2000)          |

#### Operacionalização

Representam operações, processos e estruturações utilizados para satisfazer os softgoals NFR, tem sua representação na _Figura 2_.

| Figura 2: Softgoal de Operacionalização            |
|----------------------------------------------------|
| ![image](../_media/softgoal_operacionalizacao.png) |
| Fonte: (CHUNG et al., 2000)                        |

#### Afirmação

Apoiam as tarefas de priorização e refinamento dos softgoals. Em suma, embasam as tomadas de decisão e os rumos do
sistema, tem sua representação na _Figura 3_.

| Figura 3: Softgoal de Afirmação             |
|---------------------------------------------|
| ![image](../_media/softgoal_afirmacao.jpeg) |
| Fonte: (CHUNG et al., 2000)                 |

### 2.2 Interdependências

### Refinamentos:

Nesse tipo de interdependência, um softgoal pai de caráter geral se ramifica, de modo <i>Top-Down</i>, em dois ou mais
filhos especializados.
Graficamente, esse ramificação pode ser realizada em qualquer um dos três tipos de softgoals (NFR, operacionalização e
adição) e é representada por um vetor
que parte dos filhos no sentido do pai (Figura 4).

| Figura 4: Exemplo de decomposição em softgoal NFR|
|----------------------------------------|
| ![image](../_media/decomposicao_softgoal_nfr.jpg) |

### Contribuições:

Uma vez que sucessivas decomposições dos softgoals pais e de seus filhos tenham sido realizadas, é importante poder
mensurar o quanto cada
membro dos níveis inferiores contribuí para a satisfação dos níveis superioes e, portanto, dos requisitos não-funcionais
como
um todo. Essa métrica é a chamada <i>contribuição</i> e pode ser visualizada graficamente por meio da inscrição de
alguns dos termos abaixo nas setas
que expressm a relação de decomposição.

#### Contribuição <i>AND</i>:

Se os <i>softgoals</i> descendentes forem satisfeitos os ascendentes também o serão. Exemplo na _Figura 5_.

| Figura 5: Exemplo de contribuição <i>AND</i> entre softgoals NFR|
|----------------------------------------|
| ![image](../_media/exemplo_contribuicao_and.jpeg) |

#### Contribuição <i>OR</i>:

Se ao menos um dos <i>softgoals</i> descendentes for satisfeito o ascendente também o será.

### 2.3 Procedimento de avaliação:

O objetivo aqui é determinar em que medida um conjunto de decisões satisfaz os requisitos não funcionais, determinando
se cada
softgoal ou interdependência do SIG foi suficientemente satisfeito. Para isso, são atribuídos rótulos aos softgoals
conforme a _Figura 6_.

| Figura 6: Rótulos utilizados pelos softgoals|
|----------------------------------------|
| ![image](../_media/procedimento_avaliacao.jpg) |
| Fonte: Baseado em (CHUNG et al., 2000) |

## 3. Diagramas

Optamos por destacar três categorias de requisitos importados do modelo FURPS - confiabilidade (Figura 10 e 11), usabilidade (Figura 8 e 9) e
portabilidade (Figura 12 e 13).

### Usabilidade - sem propagação

| ![image](../_media/usabilidade_sem_propagacao.jpg)         |
|------------------------------------------------------------|
| Figura 8: Análise sem propagação do aspecto de usabilidade |

### Usabilidade - com propagação

| ![image](../_media/usabilidade_com_propagacao.jpg)         |
|------------------------------------------------------------|
| Figura 9: Análise com propagação do aspecto de usabilidade |

### Confiabilidade - sem propagação

| ![image](../_media/confiabilidade_sem_propagacao.jpg)                                    |
|-------------------------------------------------------------|
| Figura 10: Análise sem propagação do aspecto de confiabilidade |

### Confiabilidade - com propagação

| ![image](../_media/confiabilidade_com_propagacao.jpg)          |
|----------------------------------------------------------------|
| Figura 11: Análise com propagação do aspecto de confiabilidade |

### Portabilidade - sem propagação

| ![image](../_media/portabilidade_sem_propagacao.jpg)          |
|---------------------------------------------------------------|
| Figura 12: Análise sem propagação do aspecto de portabilidade |

### Portabilidade - com propagação

| ![image](../_media/portabilidade_com_propagacao.jpg)        |
|-------------------------------------------------------------|
| Figura 13: Análise com propagação do aspecto de portabilidade |

## Referências Bibliográficas

https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html

https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/guidances/checklists/supplementary_specifications_13D7A7B2.html

CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J. Non-functional requirements
in software engineering. Springer Science & Business Media: [s.n.], 2000. v. 5.

## Histórico de Versões

| Versão | Data       | Descrição                                         | Autor                           |
|--------|------------|---------------------------------------------------|---------------------------------|
| 1.0    | 30/07/2021 | Escrita da introdução, legenda e                  | Nicolas Georgeos Mantzos        |
| 1.1    | 02/07/2021 | Inserção de NFR de Confiabilidade e Portabilidade | Guilherme Brito Vilas - Bôas    |
