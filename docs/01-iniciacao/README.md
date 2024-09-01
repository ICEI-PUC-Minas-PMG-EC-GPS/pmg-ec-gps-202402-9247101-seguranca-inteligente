# Iniciação

> A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
> Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
> É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
> Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
> Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
> O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Critérios de Sucessos](#critérios-de-sucesso)
- [Partes Interessadas](#partes-interessadas)
  - [Identificação das Partes Interessadas](#identificação-das-partes-interessadas)
  - [Avaliação das Partes Interessadas](#avaliação-das-partes-interessadas)
- [Termo de Abertura do Projeto](#termo-de-abertura-do-projeto)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
  - [Escopo Preliminar e Premissas](#escopo-preliminar-e-premissas)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos Não Funcionais](#requisitos-não-funcionais)
    - [Restrições](#restrições)
    - [Contra-Escopo](#contra-escopo)
    - [Condições para início do Projeto](#condições-para-início-do-projeto)
  - [Marcos Agendados e Entregas](#marcos-agendados-e-entregas)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)

# Introdução

Este projeto tem como objetivo desenvolver um sistema de software que utiliza visão computacional para realizar análises de imagens capturadas por câmeras de segurança em diversas disciplinas. O foco inicial será em sistemas de segurança para residências, com a possibilidade de expansão para ambientes comerciais e industriais. A execução deste projeto requer habilidades em visão computacional, inteligência artificial (IA), aprendizado de máquina (ML), administração de bancos de dados, desenvolvimento de interfaces gráficas para dispositivos móveis, e gestão de infraestrutura em nuvem. O principal propósito do software é fornecer análise em tempo real das imagens de segurança, elevando o nível de proteção e conforto dos usuários. As funcionalidades previstas incluem: a criação de "cercas elétricas virtuais" com horários programáveis, que enviam alertas ao cliente caso alguém invada o perímetro estabelecido; monitoramento de veículos em tempo real, ajustado de acordo com a posição das câmeras; detecção de ameaças, tanto de pessoas quanto de veículos; e reconhecimento de visitantes, distinguindo entre entregadores de serviços  e funcionários de empresas públicas. Todas essas funcionalidades estarão disponíveis através de um aplicativo para dispositivos móveis.

```diff
+ Tarefa 01:
+ Tema do projeto e lista de Stakeholders
```

## Problema

O fator humano é um dos componentes críticos para as falhas no processo de vigilância residencial. Isso porque, a atividade humana está sempre sujeita à falhas, por diversos motivos. Por exemplo, um porteiro que trabalha de madrugada pode, por ventura, sentir sono e não atuar diante uma invasão ao condomínio. Além disso, a contratação de funcionários de vigilância envolve um processo seletivo que exige gastos. Visto isso, faz-se necessária uma solução para a possibilidade de falhas de funcionários e que também vise a economia de gastos com o processo de segurança residencial.

## Objetivos

Objetivo geral: Fornecer uma aplicação inteligente de auxílio à segurança residencial, por meio do uso de visão computacional e aprendizado de máquina.

Objetivos específicos: 
* Análise e segmentação de imagens para identificação de pessoas e objetos.
* Integrar software com o sistema da câmera de segurança existente ou a ser instalada.
* Hospedar o sistema em um serviço de cloud confiável.
* Comparar a insegurança anterior e posterior a implementação do sistema.

> Aqui você deve descrever os objetivos do trabalho.
> Apresente um Objetivo Geral, sintetizado em uma única frase.
> Apresente também 3 ou 4 objetivos específicos (sub-produtos do sistema ou objetivos extras que podem ser alcançados pela construção do software).
> 
> **Link Útil**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)


## Justificativa

A execução do projeto se faz conveniente devido ao fato de que ele deve facilitar os processos que envolvem a vigilância residencial e comercial, uma vez que essa ocorrerá de forma automatizada, com alto índice de precisão em relação à identificação de pessoas pelas imagens das câmeras, e será instalada de forma personalizada, para atender às necessidades do cliente. Ademais, o uso do sistema que será produzido deve economizar recursos financeiros à longo prazo, já que descartará a necessidade de contratação de profissionais de vigilância, o que poderia acarretar em gastos elevados.

> Aqui você deve descrever os benefícios esperados pela construção do projeto.
> As justificativas do projeto explicam as razões e a necessidade da iniciativa.
> Elas demonstram como o projeto atende a uma demanda específica, resolve um problema ou aproveita uma oportunidade identificada.
> Além disso, definem os benefícios esperados e o impacto previsto para a organização ou a comunidade. 

## Critérios de Sucesso

* Entregar dentro do prazo que foi estipulado no contrato com no máximo um mês de atraso para evitar o pagamento de multa.

* Entregar um software inteligente e confiável que tenha contra medidas para possíveis acidentes naturais como falta de energia e que consiga detectar avaria nos equipamentos.

* Conseguir lucrar com o projeto.

* Conseguir otimizar o projeto para deixar com menos requisitos de hardware sem perder qualidade.

* Conseguir um aumento significativo de segurança nas áreas em que forem instaladas o sistema.

> Os critérios de sucesso indicam uma forma avaliar o êxito do trabalho e analisar se o projeto realmente alcançou os objetivos estabelecidos. 
> Esses critérios geralmente abrangem diversas dimensões, incluindo a entrega dentro do prazo e orçamento estipulados, a satisfação do cliente, a qualidade do produto ou serviço final, e a eficiência na utilização de recursos. 
> Além disso, a capacidade de atender aos requisitos e expectativas das partes interessadas, bem como a gestão eficaz de riscos, são considerados aspectos importantes para determinar o sucesso de um projeto. 

# Partes Interessadas

> Relacione as partes interessadas no seu projeto. 
> Você deve descrever as partes interessadas e indicar qual o nível de influência em relação ao projeto.
> Indique as principais pessoas (clientes, fornecedores, etc), indicando possíveis expectativas, nível de influência e possível importância para o sucesso do projeto.

> Você pode utilizar como referência o seguinte documento:
> [Registro de Partes Interessadas](artefatos/registro-partes-interessadas.xlsx)

## Identificação das Partes Interessadas

| Nome            | Posição / Cargo        | Papel Projeto | E-mail      | Telefone    |
|-----------------|-----------------       |---------------|-------------|-------------|
| Maria Emanuelly | CEO do Grupo Porteiros | Contra ativista | maria_damota@hotmnail.com | (35) 98112-8183 |
| Bryan Vinicius  | Representante da INTELBRAS | Implementação física | bryan_vinicius@intelbrasr.com.br | (35) 99779-7570 |
| Diego Benedito  | Síndico Condomínio Floresça | Adoção do sistema | diego-porto93@floresca.com | (31) 99764-0856 |
| Daiane Camila   | Adm. do Boulevard Shopping | Adoção do sistema  | daiane_camila@boulervard.com.br | (31) 98874-5702 |
|                 |                        |               |             |             |
|                 |                        |               |             |             |
|                 |                        |               |             |             |
|                 |                        |               |             |             |

> Opções de identificação dos stakeholders:
> - Nome: nome da parte interessada (inclui funcionários da empresa e do cliente)
> - Posição / Cargo: Identificação do cargo da parte interessada
> - - Ex.: Gerente de TI, Funcionário da Linha de Produção, Presidente, Analista de Sistema do Cliente, Desenvolvedor, etc.
> - Papel no Projeto: Papel da pessoa no projeto
> - - Ex.: Desenvolvedor, Analista de Requisitos, Analista de Testes, Product Owner, etc.
> - E-mail: E-mail do Stakeholder (*não utilizar informações pessoais*)
> - Telefone: Telefone do Stakeholder, incluindo WhatsApp (*não utilizar informações pessoais*)

## Avaliação das Partes Interessadas

| Nome            | Expectativa no Projeto | Influência    | Importância / Poder | Apoio       | Observações   |
|-----------------|------------------------|---------------|---------------------|-------------|---------------|
| Maria Emanuelly | Falha no projeto/fim   | Alta          | Média             | Negativo    | Convencendo sobre a não-adoção o projeto |
| Bryan Vinicius  | Sucesso e Implementação em ampla escala | Alta    | Alta   | Positivo    | Divulgando para possíveis compradores |
| Diego Benedito  | Adoção no sistema de segurança próprio | Baixo    | Média  | Positivo    | Primeiro apoiador do projeto |
| Daiane Camila   | Adoção ampla em seus empreendimentos   | Alta     | Alta   | Positivo    | Principal apoiadora visando expansão |
|                 |                        |               |                   |             |               |
|                 |                        |               |                   |             |               |
|                 |                        |               |                   |             |               |
|                 |                        |               |                   |             |               |

> Opções de avaliação:
> - Expectativa: descrição da expectativa da parte interessada no projeto.
> - - Ex.: Diminuição do tempo de realização das tarefas, aumento da produtividade, aumento da satisfação do cliente, etc.
> - Influência: Alta, Média, Baixa
> - Importância: Alta, Média, Baixa
> - Apoio: Positivo, Negativo, Neutro
> - Observações: Informações adicionais, para o cliente.

```diff
+ Tarefa 01
+ Fim da seção a ser atualizada.
```


-----
```diff
+ Tarefa 02
+ Termo de Abertura do Projeto
```

# Termo de Abertura do Projeto

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

> Você pode utilizar como referência o seguinte documento:
> [Termo de Abertura do Projeto](artefatos/termo-abertura-projeto.docx)

## Estimativa de Custo

......  COLOQUE AQUI O SEU TEXTO ......

> A avaliação da viabilidade econômica busca determinar a sustentabilidade financeira e o retorno sobre o investimento do empreendimento. 
> Este processo envolve a análise dos custos associados ao projeto, incluindo investimentos iniciais, despesas operacionais e potenciais custos de manutenção. 
> Simultaneamente, são examinados os benefícios esperados, como receitas, economias de custos e ganhos tangíveis e intangíveis. 
> A elaboração de projeções financeiras realistas e a aplicação de métricas como o Valor Presente Líquido (VPL) e a Taxa Interna de Retorno (TIR) contribuem para uma avaliação abrangente da viabilidade econômica do projeto. 
> Este processo permite que os gestores de projeto e as partes interessadas tomem decisões informadas sobre a continuidade, ajustes ou mesmo a interrupção do projeto, garantindo uma alocação eficiente de recursos e maximizando os benefícios econômicos esperados.

......  ATUALIZE OS ITENS DE CUSTO DO SISTEMA. ADICIONE NOVOS OU SUBDIVIDA ITENS, CASO NECESSÁRIO ......

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        |           |            |              |             |
| Hardware                |           |            |              |             |
| Serviços de Rede        |           |            |              |             |
| Hospedagem e Nuvem      |           |            |              |             |
| Software de terceiros   |           |            |              |             |
| Serviços e treinamento  |           |            |              |             |
| **Total Geral**         |           |            |              |             |


## Estimativa de Prazo

......  COLOQUE AQUI O SEU TEXTO ......

> A estimativa de prazo orienta tanto o cliente quanto a equipe de desenvolvimento do projeto em termos do tempo necessário para a conclusão do projeto como um todo. 
> Esta estimativa possibilita a criação de um cronograma realista e viável, permitindo o planejamento adequado das fases do projeto, alocação de recursos de maneira eficiente e antecipação de eventuais desafios.
> Uma estimativa precisa orienta a execução do projeto, contribui para a gestão de expectativas e para o estabelecimento de metas alcançáveis.

> Indique:
> * Prazo previsto (em horas) 
> * Data de início
> * Data de término

* Prazo previsto (em horas): 3000 horas
* Data de início: 01 / 08 / 2024
* Data de término: 31 / 12 / 2024

## Escopo Preliminar e Premissas

> Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas. 
> 
> ***A quantidade mínima de requisitos a serem preenchidos nas seções abaixo não incluem os exemplos previamente fornecidos.***

## Declaração de Escopo

> Você pode utilizar como referência o seguinte documento:
- [Declaração de Escopo](artefatos/declaracao-escopo.docx)

> Enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


### Requisitos Funcionais

......  ATUALIZE OS REQUISITOS FUNCIONAIS DO SISTEMA (MÍNIMO 10) ......

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RF-001| Identificar possíveis ameaças a segurança na residência | ALTA | 
|RF-002| Treinamento e ajuste do modelo | ALTA |
|RF-003| Servidor primário para processamento da aplicação | ALTA |
|RF-004| Servidor secundário para operações emergenciais | BAIXA |
|RF-005| Sistema de processamento e detecção de vozes | BAIXA |
|RF-006| Cadastro e login de usuários | MÉDIA |
|RF-007| Aplicação móvel para gerenciamento | ALTO |
|RF-008| Aplicação web para gerenciamento | ALTO |
|RF-009| Autenticação e tratamento de dados dos Usuários | MÉDIA |
|RF-010| Funcionalidade de histório detalhado de alertas | ALTA |

### Requisitos Não Funcionais

......  ATUALIZE OS REQUISITOS NÃO FUNCIONAIS DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| Garantia situacional do modelo | ALTA | 
|RNF-002| Suporte multiplataforma do aplicativo móvel | BAIXA |
|RNF-003| Serviço de suporte a longo prazo para clientes | ALTA |
|RNF-004| Garantia de compatibilidade com diferentes modelos e marcas de camêras | MÉDIA |
|RNF-005| Otimização para situações de alta demanda do sistema | ALTA |


### Restrições

......  ATUALIZE AS RESTRIÇÕES DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RE-001| Comunicação contextual entre diferentes instâncias do sistema | ALTA | 
|RE-002| Existência de diferentes modos de operação do aplicativo | MÉDIA |
|RE-003| Diferenciação entre modelos específicos de veículos | BAIXA |
|RE-004| Implantação de um sistema interno contra falhas elétricas | ALTA |
|RE-005| Implantação de um sistema que contacte a polícia em caso de detecção de movimentos suspeitos | ALTA |


### Contra-Escopo

......  ATUALIZE O CONTRA-ESCOPO DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as atividades que não serão executadas no projeto

|ID    | Descrição do Contra-Escopo          | 
|------|-------------------------------------|
|CE-001| Treinamento de modelo de LLM        |
|CE-002| Pesquisa de viabilidade do mercado. |
|CE-003| Instalação de câmeras. |
|CE-004| Instalação de alarmes. |
|CE-005| Host do Banco de Dados. |

### Condições para início do Projeto

......  ATUALIZE AS CONDIÇÕES PARA INÍCIO DOS PROJETOS (MÍNIMO 3) ......

A tabela a seguir, apresente as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto    | 
|------|--------------------------------------------------|
|CI-001| Assinatura de contrato de prestação de serviços. |
|CI-002| Apresentação de garantias definidas no contrato. |

## Marcos Agendados e Entregas

......  ATUALIZE OS MARCOS AGENDADOS DO PROJETO E AS DATAS PARA ENTREGAS DAS TAREFAS ......

A tabela a seguir, identifique os marcos do projeto e os entregáveis previstos (requisitos).

|ID   | Marco do Projeto                                                  | 
|-----|-------------------------------------------------------------------|
|M-1  | Liberação do sistema para cadastro de informações e configuração. |
|M-2  | Permissão para uso do sistema, por usuários focais.               |
|M-3  |                                                                   |
|M-4  |                                                                   |
|M-5  |                                                                   |
|M-6  |                                                                   |

```diff
+ Tarefa 02
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 03:
+ Metodologia do Projeto
```

# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, a divisão de papéis e tarefas e as ferramentas empregadas.
>
> Coloque detalhes sobre o processo utilizado e a implementação do Framework Scrum seguido pelo grupo. 
> O grupo deverá gerenciar as tarefas utilizando o GitHub Project para acompanhar o andamento do projeto, a execução das tarefas e o status de desenvolvimento da solução.
> 
> **Links Úteis**:
> - [Github Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project)
> - [O que é o GitHub Projects? | Guia de Iniciantes](https://www.youtube.com/watch?v=vxYTpsFKdiQ&ab_channel=JulioArruda)
> - [Introduction to GitHub Project Boards](https://www.youtube.com/watch?v=idZyqNIrt84&list=PLiO7XHcmTslc5hGrbnnmHIb0SeJLTpOEu&ab_channel=MickeyGousset)
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
> Indique as responsabilidades de cada membro do grupo no projeto.

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

> Liste as ferramentas empregadas no desenvolvimento do projeto, justificando a escolha delas, sempre que possível.
> Todas as ferramentas utilizadas devem ser listadas.
> Qualquer tipo de ferramenta que for utilizada para construção de um artefato deve ser identificada, uma vez que podem ser necessárias alterações.
> A necessidade de uso de licenças e possíveis custos relacionados devem ser indicados.

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/XXXXXXX | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/XXXXXXX |               |
| Protótipo Interativo  | MavelApp ou Figma  | https://figma.com/XXXXXXX  |               |
| Documentos Textuais   | LibreOffice Writer | N/A                        |               |
| Planilhas e Gráficos  | Google Planilhas   | https://docs.google.com/   |               |
| EAP / WBS             | | | |
| Cronograma do Projeto | | | |
| Matriz RACI           | | | |

```diff
+ Tarefa 03:
+ Fim da seção a ser atualizada.
```

----
