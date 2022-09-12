# Backlog

## 1. Introdução

O backlog do produto é a lista de itens (histórias de usuário, bugs, deveres) usados pelo time de software para coordenar o trabalho
a ser feito. Ele serve como ponte entre a geração e implementação das **histórias de usuário**.

No Scrum temos dois backlogs:

- Product backlog: refere-se a uma lista contendo as necessidades gerais do produto, onde o gerente ou Product owner, define de acordo com a priorização feita pelo cliente. Durante as reuniões de Sprint Planning o gerente apresenta o backlog para a equipe e é definido quais serão as tarefas da Sprint.

- Sprint backlog: refere-se a uma lista contendo artefatos menores,de uma sprint , que agrega valor a cada nova sprint para o cliente, diferente.

Histórias de usuário descrevem funcionalidades com o objetivo de agregar valor ao cliente e à equipe de desenvolvimento.
Cohn propõe a forma de estruturar uma US (sua gramática), que é a mais utilizada pelos desenvolvedores. A estrutura
proposta por Cohn descreve pontos fundamentais dos requisitos do usuário, sendo: tipo de usuário; objetivo; e a razão
do requisito descrito.

Alguns dos motivos para utilizar hitórias de usuários são (Cohn, 2004):

- Enfatizam comunicação verbal;
- São compreensivas para todos;
- Do tamanho certo para planejamento;
- Trabalham com desenvolvimento iterativo;
- Incentivam o adiantamento dos detalhes;
- Estimulam o projeto participativo.

Para complementar a escrita das histórias de usuário são descritos os critérios de aceitação, os quais tem grande importância
para os desenvolvedores, pois definem pontos que devem ser considerados durante a implementação. Os critérios de aceitação
das histórias de usuário descritas nesse arquivo podem ser encontrados na seguinte página: [Critérios de Aceitação](modelagem/criterios_de_aceitacao.md).

### 1.1 Épicos

Um épico é uma história de usuário que ainda não foi detalhada, é muito grande ou ainda possui muita incerteza e portanto não pode ser transformada em incremento do produto. O épico deve ser separado em histórias de usuário menores. Para o nosso projeto, foram definidos 2 grandes épicos principais.

#### Épico 01: Gerenciamento de Perfil

| História de Usuário | Rastreabilidade | Eu, como usuário, gostaria de... | Para poder...                         | Prioridade |
|---------------------|-----------------|----------------------------------|---------------------------------------|------------|
| US1                 | RF1             | Criar uma página                 | Escrever minhas anotações             | M          |
| US5                 | RF5             | Me autenticar no sistema         | Ter acesso às funcionalidades do app  | M          |
| US32                | RF32            | Criar uma conta                  | Acessar as funcionalidades do sistema | M          |
| US33                | RF33            | Realizar logout                  | Sair da conta dentro do sistema       | M          |

_Tabela 1: histórias de usuário do épico 1_

#### Épico 02: Gerenciamento de Página

| História de Usuário | Rastreabilidade | Eu, como usuário, gostaria de...                                                               | Para poder...                                                                                                   | Prioridade |
|---------------------|-----------------|------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|------------|
| US2                 | RF2             | Encontrar uma página criada previamente                                                        | Ver as informações escritas nela                                                                                | M          |
| US3                 | RF3             | Editar uma página                                                                              | Para ter controle total sobre ela caso falhe em algum item e precise editá-lo                                   | M          |
| US4                 | RF4             | Excluir uma página                                                                             | Remover ela das páginas existentes                                                                              | M          |
| US6                 | RF6             | Pesquisar por uma página                                                                       | Encontrar ela mais rapidamente                                                                                  | C          |
| US7                 | RF7             | Escolher em qual fonte editar minha página                                                     | Escrever texto com a fonte desejada                                                                             | S          |
| US8                 | RF8             | Escolher entre tamanho de fonte grande ou pequena                                              | Escrever texto com tamanho de fonte desejada                                                                    | C          |
| US9                 | RF9             | Escolher se o texto da página ocupa toda a largura da página ou se fica centralizado na página |                                                                                                                 | C          |
| US10                | RF10            | Visualizar o histórico de alterações da página                                                 | Verificar as alterações feitas                                                                                  | S          |
| US11                | RF11            | Favoritar uma página                                                                           | Salvar ela na aba de favoritos                                                                                  | C          |
| US12                | RF12            | Compartilhar o link de uma página                                                              | Liberar que outros usuários tenham acesso a ela                                                                 | M          |
| US13                | RF13            | Escolher a aparência do sistema                                                                | Mudar a temática de cores do design do sistema                                                                  | W          |
| US14                | RF14            | Escolher uma foto de identificação da página                                                   | Identificar uma página                                                                                          | W          |
| US15                | RF15            | Escolher uma foto de identificação do workspace                                                | Identificar um workspace                                                                                        | C          |
| US16                | RF16            | Criar quantos workspaces que eu quiser                                                         | Organizar meus workspaces com conteúdo similar                                                                  | S          |
| US17                | RF17            | Poder escolher entre opções de templates de uma página criada                                  | Criar páginas padronizadas sem muito esforço                                                                    | M          |
| US18                | RF18            | Ver o histórico de páginas deletadas                                                           | Gerenciar suas deleções e até recuperar alguma                                                                  | S          |
| US19                | RF19            | Importar páginas de outras plataformas ou aplicativos                                          | Ter uma versão editável de uma página que ele se interessou                                                     | C          |
| US20                | RF20            | Adicionar fotos a página                                                                       | Visualizar de maneira melhor um item que ele estava digitando mas precisaria de uma imagem para entender melhor | S          |
| US21                | RF21            | Referenciar outras páginas dentro de uma página                                                | Ter acesso a outras páginas que complementem o tópico abordado                                                  | C          |
| US22                | RF22            | Adicionar outros perfis para editar uma página                                                 | Ter a opinião/visão de um outro alguém no tópico abordado                                                       | C          |
| US23                | RF23            | Adicionar uma legenda às imagens da página                                                     | Saber do que a imagem se trata                                                                                  | C          |
| US24                | RF24            | Escrever comentários nas páginas                                                               | Posteriormente checar alguma anotação ou observação feita                                                       | W          |
| US25                | RF25            | Criar blocos de markdown para editar as páginas                                                | Construir itens que na digitação comum não se apresentam com tanta facilidade, como tabelas                     | M          |
| US26                | RF26            | Escolher entre opções de edição do bloco de markdown                                           | Editar o bloco criado como desejado                                                                             | M          |
| US27                | RF27            | Ter uma agenda                                                                                 | Visualizar afazeres do dia desejado                                                                             | S          |
| US28                | RF28            | Criar fórmulas matemáticas                                                                     | Ter facilidade caso necessite anotar alguma fórmula                                                             | S          |
| US29                | RF29            | Criar seu próprio quadro kanban personalizado                                                  | para gerenciar suas tarefas com facilidade                                                                      | S          |
| US30                | RF30            | Escrever blocos de código                                                                      | Entender a sintaxe do código sem se perder na linguagem padrão ou não estilizada                                | C          |
| US31                | RF31            | Ser informado da situação do clima na minha região                                             | Saber como está o tempo sem precisar minimizar minha aplicação                                                  | W          |

_Tabela 2: histórias de usuário do épico 2_

## 2. Priorização do Backlog

### 2.1 Metodologia

A priorização das histórias de usuário do Backlog foi realizada utilizando a Persona Carlos da Silva. O Dono do Produto passou pelas 33 histórias de usuário e pelos respectivos critérios de aceitação, explicando para o interpretador da Persona. Sendo assim, a partir da descrição, dos objetivos pessoais e praticos da Persona, ela decidiu se a história de usuário possui prioridade: baixa, média ou alta. Depois de decidido a prioridade, a persona Carlos da Silva validou se os critérios de aceitação descritos satisfazem ou não a história em questão. 

### 2.2 Participantes 

Os participantes da priorização das histórias de usuário do Backlog:

- Arthur Lima (Dono do Produto)
- Leonardo Vitoriano (Interpretador da Persona Carlos da Silva)

### 2.3 Gravação 

A gravação da priorização e validação do Backlog a partir da Persona pode ser encontrado nesse link:

- [Vídeo](https://youtu.be/xoBXTkI3cgk)

### 2.4 Priorização

Para a atividade de priorização e validação utilizamos utilizamos a Persona [Carlos da Silva](https://requisitos-de-software.github.io/2022.1-Notion/#/elicitacao/personas?id=_21-carlos-da-silva) onde o integrante Leonardo interpretou seu papel e avaliador pelo integrante Arthur.

O resultado da priorização pode ser encontrado na Tabela 1 a seguir:

| ID da história | Importância para a persona (baixa, média, alta). | Os Critérios de aceitação estão corretos para validar a história                              |
|----------------|--------------------------------------------------|-----------------------------------------------------------------------------------------------|
| [US1](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=Prioridade-,US1,-RF1)           | alta                                             | sim                                                                                           |
| [US2](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=Prioridade-,US2,-RF2)           | alta                                             | sim                                                                                           |
| [US3](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US3,-RF3)           | alta                                             | sim                                                                                           |
| [US4](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US4,-RF4)           | alta                                             | não, confirmação de exclusão antes de excluir                                                 |
| [US5](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US5,-RF5)           | Alta                                             | sim                                                                                           |
| [US6](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US6,-RF6)           | alta                                             | sim                                                                                           |
| [US7](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=C-,US7,-RF7)           | média                                            | não, ícone clicável para seleção de fonte adequada                                            |
| [US8](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=S-,US8,-RF8)           | média                                            | não, ícone clicável para seleção de fonte adequada                                            |
| [US9](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=C-,US9,-RF9)           | média                                            | não, ícone clicável para selecão                                                              |
| [US10](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=C-,US10,-RF10)           | média                                            | sim                                                                                           |
| [US11](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US11,-RF11)           | média                                            | sim                                                                                           |
| [US12](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US12,-RF12)           | baixa                                            | sim                                                                                           |
| [US13](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US13,-RF13)           | média                                            | sim                                                                                           |
| [US14](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US14,-RF14)           | baixa                                            | sim                                                                                           |
| [US15](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US15,-RF15)           | baixa                                            | sim                                                                                           |
| [US16](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US16,-RF16)           | alta                                             | sim                                                                                           |
| [US17](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US17,-RF17)           | Alta                                             | sim                                                                                           |
| [US18](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US18,-RF18)           | Média                                            | sim                                                                                           |
| [US19](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US19,-RF19)           | Alta                                             | Sim                                                                                           |
| [US20](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US20,-RF20)           | Alta                                             | Sim                                                                                           |
| [US21](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US21,-RF21)           | Alta                                             | Sim                                                                                           |
| [US22](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US22,-RF22)           | baixa                                            | sim                                                                                           |
| [US23](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US23,-RF23)           | Alta                                             | sim                                                                                           |
| [US24](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US24,-RF24)           | Alta                                             | sim                                                                                           |
| [US25](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US25,-RF25)           | Média                                            | sim                                                                                           |
| [US26](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US26,-RF26)           | baixa                                            | sim                                                                                           |
| [US27](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US27,-RF27)           | alta                                             | sim                                                                                           |
| [US28](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US28,-RF28)           | baixa                                            | sim                                                                                           |
| [US29](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US29,-RF29)           | alta                                             | não, gostaria de adicionar tempo inicial e tempo final, cor vermelha para 1 antes de expirar. |
| [US30](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US30,-RF30)           | baixa                                            | sim                                                                                           |
| [US31](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US31,-RF31)           | baixa                                            | sim                                                                                           |
| [US32](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US32,-RF32)           | alta                                             | sim                                                                                           |
| [US33](https://requisitos-de-software.github.io/2022.1-Notion/#/modelagem/backlog:~:text=M-,US33,-RF33)           | alta                                             | sim                                                                                           |

*Tabela 3 - Backlog Scrum*

## Referências Bibliográficas

Andrade, Edson; Uma Comparação Voltada a Interpretação Entre Casos de Uso e Histórias
de Usuário com Cenário de Aceitação; RS, 2016.

Sedano, Todd; et al. The Product Backlog.

Souza, Jonathan, et al. Descrevendo requisitos de User eXperience em
Critérios de Aceitação de User Stories.

https://agilemanifesto.org/

https://www.scaledagileframework.com/

## Histórico de Versões

| Versão | Data       | Descrição                                              | Autor                          | Revisor             |
|--------|------------|--------------------------------------------------------|--------------------------------|---------------------|
| 1.0    | 26/07/2022 | Criação da Página e Incorporação de Texto Introdutório | Bernardo Pissutti              | Arthur e Leonardo   |
| 1.1    | 28/07/2022 | Adição das histórias de usuário US1 - US15             | Bernardo Pissutti              | Arthur e Leonardo   |
| 1.2    | 01/08/2022 | Reformulação da tabela de Histórias de Usuários        | Leonardo Vitoriano             | Nicolas e Guilherme |
| 1.3    | 02/08/2022 | Adição das histórias de usuário US16 - US33            | Cícero Fernandes               | Arthur e Leonardo   |
| 1.4    | 02/08/2022 | Adição dos critérios de aceitação US16 - US33          | Arthur Jose e Leonardo Milomes | Nicolas e Guilherme |
| 1.5    | 02/08/2022 | Adicionando informação inicial backlog                 | Arthur                         | Nicolas e Guilherme |
| 1.6    | 02/08/2022 | Adicionando resultado backlog scrum                    | Arthur                         | Nicolas e Guilherme |
| 1.7    | 02/08/2022 | Adicinando a priorização do backlog                    | Leonardo Milomes               | Nicolas e Guilherme |
| 1.8    | 12/09/2022 | Adicinando links e definindo priorização                     | Arthur               | - |