# ElectroFarm

<div align="center">
   <h1> 2022-1- Para cê tá mal </h1>
</div>

<br/>

## 📄 Sobre o projeto

<p style="text-indent: 20px; text-align: justify"> Este projeto visa ser um facilitador para farmácias de pequeno e médio porte que precisam de um software para o seu funcionamento. Por ser um software livre, é totalmente gratuito. Utilizando tecnologias emergentes, iremos mudar a concepção de software farmacêutico. </p>

<br/>

## ⚙️ Tecnologias utilizadas

As tecnologias foram determinadas de acordo com a necessidade das atividades a serem desenvolvidas.

| Frontend    | Backend |
| :---------- | :-----: |
| Electron.js | Node.js |

## 🤝 Colaboradores

| Nome                | Matrícula | GitHub                              | Disciplina |
| ------------------- | --------- | ----------------------------------- | ---------- |
| Arthur D'Assumpcao  | 190084570 | https://github.com/ArtAssLou        | MDS        |
| Carlos Daniel       | 190011408 | https://github.com/yesklin          | REQ        |
| Gian Medeiros       | 190055006 | https://github.com/GianMedeiros     | REQ        |
| Gustavo Barbosa     | 180042041 | https://github.com/brbsg            | MDS        |
| João Paulo Monteiro | 202045141 | https://github.com/joaombc          | MDS        |
| Lucas Rodrigues     | 200059211 | https://github.com/lucascard        | MDS        |
| Luiz Gustavo        | 180023179 | https://github.com/Luiz-GL-Campos   | REQ        |
| Magno Luiz          | 180042696 | https://github.com/magnluiz         | REQ        |
| Vinicius Alves      | 190096373 | https://github.com/viniciusalves999 | REQ        |

<br/>

## Histórico de Revisão

| Data       | Versão | Descrição                                              | Autor   |
| ---------- | ------ | ------------------------------------------------------ | ------- |
| 29/06/2022 | 1.0    | Criação do Documento e informações iniciais do projeto | REQ-MDS |

<div align="center">
   <h2> Visão do Produto e Projeto </h2>
</div>

## 1. Visão Geral do Produto

### 1.1 Declaração de posição do produto

<p style="text-indent: 20px; text-align: justify"> O ElectroFarm é um software livre, acessível a farmácias de pequeno e médio porte para a de venda e controle de estoque de produtos farmacêuticos. Esse produto tem como foco a experiência do usuário, portanto sua inteligibilidade, apreensibilidade e operacionalidade para proporcionar máxima eficiência e eficácia são os seus pontos de destaque. É uma alternativa de entrada de alta qualidade e gratuita que traz o aumento da performance na venda dos produtos, fácil de treinar novos operadores. Tendo em vista que os sistemas atuais não possuem atualizações de grande magnitude e sim apenas manutenções, esse produto torna-se o único sistema de baixo custo com alta performance. </p>

| Software      | ElectroFarm                                                                                                              |
| ------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Para          | Gabriel e Rose (donos do negócio)                                                                                |
| Quem          | Necessita de um sistema para vendas e controle de estoque de uma farmácia                                                |
| O             | É uma solução cliente-servidor                                                                                           |
| Que           | É de acessível aquisição, com foco na usabilidade do usuário, permitindo funcionalidades de controle de vendas e estoque |
| Ao contrário  | De produtos como “Vetor Farma” e “InovaFarma”                                                                            |
| Nosso produto | É um software gratuito com foco na usabilidade do usuário                                                                |

### 1.2 Objetivos do Produto

<p style="text-indent: 20px; text-align: justify"> O principal objetivo do ElectroFarm é a  venda de produtos farmacêuticos e o controle de estoque dos mesmos. Como objetivos secundários, teremos o cálculo da comissão vendedor receberá e a análise de vendas por período.
</p>

### 1.3 Tecnologias a Serem Utilizadas

<p style="text-indent: 20px; text-align: justify" > Electron.JS, NodeJS com TypeScript. No banco de dados usaremos PostgreSQL com Prisma ORM e Docker Compose, para testes usaremos JEST e CYPRESS.
</p>

## 2 Visão Geral do Projeto

### 2.1 Organização do Projeto

| Papel                 | Atribuições                                                                                                                                                                                          | Responsável | Participantes               |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | --------------------------- |
| Analista de Qualidade | Garantir a qualidade do produto, garantir o cumprimento do conceito de pronto, realizar inspeções de código.                                                                                         | Lucas       | Arthur, Gustavo, João Paulo |
| Desenvolvimento       | Codificar o produto, codificar testes unitários, realizar refatoração.                                                                                                                               | Gustavo     | Arthur, Lucas, João Paulo   |
| Design                | Criar as telas e todo o layout do produto, garantir a fidelidade das telas para com o que o cliente deseja.                                                                                          | Luiz        | Vinicius, Carlos, Magno     |
| Devops                | Implementação, manutenção e atualização do ciclo de vida do software                                                                                                                                                                                       | Gustavo     | Arthur, Lucas, João Paulo   |
| Cliente               | Atualizar o escopo do produto, organizar o escopo das sprints, validar as entregas.                                                                                                                  | Rose        | Gabriel                     |
| Scrum Master          | Garantir que o Time Scrum se oriente pelos valores e práticas do Scrum, certifica-se de que os membros não se comprometam com compromissos além dos que eles conseguem cumprir dentro de uma Sprint. | Vinícius    | Gian, Magno                 |
| Product Owner         | Tem a visão do que será desenvolvido, as necessidades a serem atendidas, o público que vai utilizar os serviços, e objetivos a serem alcançados.                                                     | Carlos      | Luiz, Gian                  |

### 2.2 Planejamento das Fases e/ou Iterações do Projeto

| Sprint   | Produto                       | Data início | Data Fim |
| -------- | ----------------------------- | ----------- | -------- |
| Sprint 1 | Definição do Produto          | 22/06/2022  | 29/06/22 |
| Unidade 1| Entrega da Unidade 1          | 30/06/2022  | 30/06/22 |
| Sprint 2 | Levantamento de Requisitos com o cliente | 01/07/2022  | 08/07/22 |
| Sprint 3 | Canvas MVP e Planejamento do Projeto | 09/07/2022  | 15/07/22 |
| Sprint 4 | Confecção Backlog e Processo de Engenharia de Requisitos | 16/07/2022  | 20/07/22 |
| Unidade 2| Entrega da Unidade 2          | 21/06/2022  | 21/06/22 |
| Sprint 5 | Organização dos requisitos para inicio do desenvolvimento do produto | 22/07/2022 | 28/07/2022 |
| Sprint 6 | Desenvolvimento do MVP1 | 29/07/2022 | 04/08/2022 |
| Sprint 7 | Desenvolvimento do MVP1 | 05/08/2022 | 11/08/2022 |

Fundamentos, conceitos e exercícios.
PBB, User Story, User Story Mapping, BDD
2) Aplicação das ferramentas, métodos e técnicas de requisitos

### 2.3 Matriz de Comunicação

| Descrição                                                             | Área/Envolvidos                        | Periodicidade | Produtos Gerados                                  |
| --------------------------------------------------------------------- | -------------------------------------- | ------------- | ------------------------------------------------- |
| Acompanhamento das Atividades em Andamento (Sprint Review)            | Equipe do Projeto e Cliente            | Semanal       | Ata de reunião e Relatório de situação do projeto |
| Comunicar a situação do projeto                                       | Equipe do Projeto, Cliente e Professor | Semanal       | Ata de reunião e Relatório de situação do projeto |
| Acompanhamento dos Riscos, Compromissos, Ações Pendentes, Indicadores | Equipe do Projeto e Cliente            | Quinzenal     | Ata de reunião e Relatório de situação do projeto |
| Comunicação sobre a situação das atividades sendo executadas          | Equipe do Projeto                      | Diária        | Ata via Telegram ou Discord                       |

### 2.4 Gerenciamento de Riscos

<p style="text-indent: 20px; text-align: justify" > Para gerenciar os riscos do nosso projeto, primeiramente o avaliamos como um todo, requisitos funcionais e não funcionais, tecnologias a serem utilizadas para desenvolvimento do projeto, qual o método de desenvolvimento a equipe utilizaria, quais são os impedimentos para a realização das atividades ou comunicação com o cliente. Cada um desses pontos gerou certas preocupações entre os integrantes da equipe, e para que não hajam complicações ou impedimentos devido a algum acontecimento inesperado em relação aos temas discutidos, resolvemos realizar as seguintes tarefas: </p>

- Sempre identificar os riscos no início das diferentes fases do projeto, levando em consideração as ferramentas que serão utilizadas, disponibilidade, conhecimento da equipe e também comunicação aberta e fácil com todos os envolvidos.

- Realizar atividades para diminuir os riscos. Ou seja, verificar se todo o time têm facilidade com uma ferramenta escolhida, senão como ensinar a um membro essa nova tecnologia, definir métodos de comunicação que fique fácil para todos, sempre comunicar dificuldades para a equipe se situar e poder contornar a situação antes que se agrave. Difundir o conhecimento para que todos possam aprender e melhorar constantemente.

- Revisar os riscos a cada sprint(por se tratar de um processo ágil porém adaptado a equipe).

- Caso algum risco venha a ser identificado mas já tinha sido previsto antes, realizar as atividades com formas de resolvê-lo o mais breve possível.

- Sempre manter registrados os riscos para que a equipe tenha acesso e consiga se preparar para contornar o problema caso ocorra.

### 2.5 Critérios de Replanejamento

<p style="text-ident: 20px; text-align: justify" > O projeto poderá ser replanejado se: </p>

- A equipe encontrar dificuldades com o cumprimento da metodologia selecionada.
- A equipe ter problemas em aprender as ferramentas novas que não conheçem e que sejam necessárias.
- Caso haja algum problema que não possa ser resolvido de forma rápida, como a disponibilidade ou comunicação do cliente(incluindo problemas de saúde ou comunicação com a equipe).
- Se o cliente ou a equipe decidirem futuramente um método melhor para o desenvolvimento da nossa solução.

## 3 Processo de Desenvolvimento de Software

<p style="text-ident: 20px; text-align: justify" > Boas práticas de programação com Pair programming, de forma que todo o time seja rotativo e linear, garantindo o desenvolvimento técnico de todos. Usaremos o ciclo de vida evolutivo, pois os requisitos podem variar. Seguiremos a metodologia ágil com diversas cerimônias do Scrum.
</p>

### 3.1 Análise e Design

| Atividade                         | Método         | Ferramenta      | Entrega                         |
| --------------------------------- | -------------- | --------------- | ------------------------------- |
| Elaboração do design da interface | Reunião Remota | Figma           | Protótipo de alta fidelidade    |
| Modelagem da arquitetura          | Reunião Remota | Draw.io         | Arquitetura do projeto          |
| Modelagem do banco de dados       | Reunião Remota | DBdesigner      | Design do banco de dados        |
| Design de testes                  | Reunião Remota | LucidChart      | Diagrama da estrutura de testes |

### 3.2 Atividade 2

| Atividade                    | Método           | Ferramenta       | Entrega                 |
| ---------------------------- | ---------------- | ---------------- | ----------------------- |
| Construção da Interface      | Pair Programming | Electron         | Construção do front-end |
| Construção do API            | Pair Programming | NodeJS + Express | Construção do Back-end  |
| Construção do Banco de Dados | Pair Programming | PostgreSQL       | Banco de dados Modelado |

### 3.3 Atividade 3

| Atividade                          | Método           | Ferramenta                 | Entrega                       |
| ----------------------------       | ---------------- | -------------------------- | ----------------------------- |
| Criação de cenários de teste       | Reunião remota   | Discord, Notion, Cucumber  | Documento com cenários em BDD |
| Implementação de regressivos       | Reunião remota   | Discord, Notion            | Tabela com casos de aceitação |
| Implementação de testes e2e        | Pair Programming | Cypress.io, github actions | Suíte de testes               |
| Implementação de testes unitários  | Pair Programming | Jest                       | Suíte de testes               |

## 4 Processo de Engenharia de Requisitos

<p style="text-ident: 20px; text-align: justify" > Será uma abordagem ágil porém adaptada para as necessidades e disponibilidade da equipe. Essa abordagem será voltada mais para o Scrum, definimos os meios de reunião e comunicação fácil, com sprint reviews semanais, podendo assim, ser bem flexível para todos. </p>

### 4.1 Elicitação de Requisitos

| Atividade                                 | Método               | Ferramenta              | Entrega                       |
| ----------------------------              | ---------------      | ------------------------| ----------------------------- |
| Conversa com o cliente                    | Entrevista e reunião | Discord                 | Lista de requisitos           |


### 4.2 Análise de Requisitos

| Atividade                  | Método         | Ferramenta      | Entrega                 |
| ---------------------------|----------------|-----------------| ------------------------|
| Refinamento dos requisitos | Reunião remota | Discord e Figma | Backlog                 |

### 4.3 Documentação de Requisitos

| Atividade                          | Método         | Ferramenta | Entrega                                        |
| ---------------------------        |----------------|------------| -----------------------------------------------|
| Criação do Documento de Requisitos | Criação de um documento contendo todos os requisitos levantados na análise de requisitos, separando em funcionais e não funcionais | Github Pages | Documento de Requisitos |

### 4.4 Verificação e Validação de Requisitos

| Atividade                                 | Método                                      | Ferramenta | Entrega                                            |
|---------------------------------          |----------------                             |---------   | ---------------------------------------------------|
| Verificar se os requisitos estão corretos | Validação por parte do cliente com a equipe | Discord    | Integralização de funcionalidades aprovadas        |


### 4.5 Gerenciamento de Requisitos

| Atividade                                           | Método                                                                   | Ferramenta | Entrega              |
| ----------------------------------------------------|--------------------------------------------------------------------------|---------   | ---------------------|
| Acompanhamento e Refinamento do backlog | Reuniões entre as equipes de REQ e MDS possivelmente para esclarecimento de duvidas e validação com o cliente | Github Pages | Documento Backlog refinado  |

## 5 Lições Aprendidas

### 5.1 Unidade 1

#### 5.1.1 MDS

* Definir um escopo e arquitetura de desenvolvimento de forma concisa;

* Gerenciar melhor o conhecimento para com as duas equipes;

* Definir a metodologia/processo que se encaixa melhor no projeto;

* Como especificar cada atividade do processo de engenharia de software;

* Conhecer suas funções e os limites de sua atuação dentro e com o time.

#### 5.1.2 Requisitos

* Olhar um projeto de diferentes formas, analisar todas as visões de um projeto com toda a equipe;

* Definir Proposta de Engenharia de Requisitos;

* Esclarecimento das atividades que serão realizadas no projeto.

#### 5.1.3 MDS-Requisitos

* Gerenciamento de expectativa de toda a equipe, conversas mais calmas e esclarecedoras;

* Escolha de projeto menos preocupante em relação a disciplina e o desenvolvimento da equipe, comunicação realizada mais frequentemente;

* Definição de cada função no time;

* Melhor definição do limite da fronteira entre as duas equipes.

### 5.2 Unidade 2

#### 5.2.1 MDS

#### 5.2.2 Requisitos

* Esclarecimento das informações sobre o projeto, sempre perguntar e tirar duvidas sobre quaisquer informações do projeto diretamente para a equipe inicialmente.

#### 5.2.3 MDS-Requisitos

* Melhorar comunicação entre os membros da equipe.