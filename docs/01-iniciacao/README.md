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

## Justificativa

A execução do projeto se faz conveniente devido ao fato de que ele deve facilitar os processos que envolvem a vigilância residencial e comercial, uma vez que essa ocorrerá de forma automatizada, com alto índice de precisão em relação à identificação de pessoas pelas imagens das câmeras, e será instalada de forma personalizada, para atender às necessidades do cliente. Ademais, o uso do sistema que será produzido deve economizar recursos financeiros à longo prazo, já que descartará a necessidade de contratação de profissionais de vigilância, o que poderia acarretar em gastos elevados.

## Critérios de Sucesso

* Entregar dentro do prazo que foi estipulado no contrato com no máximo um mês de atraso para evitar o pagamento de multa.

* Entregar um software inteligente e confiável que tenha contra medidas para possíveis acidentes naturais como falta de energia e que consiga detectar avaria nos equipamentos.

* Conseguir lucrar com o projeto.

* Conseguir otimizar o projeto para deixar com menos requisitos de hardware sem perder qualidade.

* Conseguir um aumento significativo de segurança nas áreas em que forem instaladas o sistema.

# Partes Interessadas

## Identificação das Partes Interessadas

| Nome            | Posição / Cargo        | Papel Projeto | E-mail      | Telefone    |
|-----------------|-----------------       |---------------|-------------|-------------|
| Maria Emanuelly | CEO do Grupo Porteiros | Contra ativista | maria_damota@hotmnail.com | (35) 98112-8183 |
| Bryan Vinicius  | Representante da INTELBRAS | Implementação física | bryan_vinicius@intelbrasr.com.br | (35) 99779-7570 |
| Diego Benedito  | Síndico Condomínio Floresça | Adoção do sistema | diego-porto93@floresca.com | (31) 99764-0856 |
| Daiane Camila   | Adm. do Boulevard Shopping | Adoção do sistema  | daiane_camila@boulervard.com.br | (31) 98874-5702 |

## Avaliação das Partes Interessadas

| Nome            | Expectativa no Projeto | Influência    | Importância / Poder | Apoio       | Observações   |
|-----------------|------------------------|---------------|---------------------|-------------|---------------|
| Maria Emanuelly | Falha no projeto/fim   | Alta          | Média             | Negativo    | Convencendo sobre a não-adoção o projeto |
| Bryan Vinicius  | Sucesso e Implementação em ampla escala | Alta    | Alta   | Positivo    | Divulgando para possíveis compradores |
| Diego Benedito  | Adoção no sistema de segurança próprio | Baixo    | Média  | Positivo    | Primeiro apoiador do projeto |
| Daiane Camila   | Adoção ampla em seus empreendimentos   | Alta     | Alta   | Positivo    | Principal apoiadora visando expansão |

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

## Estimativa de Custo

A estimativa de custo do projeto envolveu a previsão de gastos relacionados às remuneração dos funcionários, ao hardware, às despesas com água, luz e Internet, à hospedagem e nuvem, aos softwares de terceiros, aos serviços e treinamentos, e também uma reserva de garantia. Por fim, conclui-se que o projeto é viável e sua realização será lucrativa.

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        | Salários, benefícios e garantias | 3000 h | R$ 99,50 | R$ 298.500,00 |
| Hardware                | Máquina para treinamento do modelo | 600 h | R$ 35,00 | R$ 21.000,00 |
| Despesas Mensais        | Água, Luz, Internet, entre outros | 3600 h | R$ 1,32 | R$ 4.752,00 |
| Hospedagem e Nuvem      | Gasto com servidor remotos | 3600 h | R$ 5,61 | R$ 20.196,00 |
| Software de terceiros   | Contrato de Licença da LLM | 3000 h | R$ 20,00 | R$ 60.000,00 |
| Licenciamento           | Direitos de imagens para treino | 0 h | R$ --- | Pode variar |
| Serviços e treinamento  | Sistemas internos e preparação dos funcionários | 300 h | R$ 34,00 | R$ 10.200,00 |
| Reserva de garantia     | Seguro em caso de gastos adicionais | 0 h | R$ --- | R$ 20.000,00 |
| **Total Geral**         | Agregado dos valores | 3000 h | R$ 144,88 | R$ 434.648,00 |


## Estimativa de Prazo

O projeto foi cuidadosamente planejado juntamente da equipe para ser concluído em um total de 3.000 horas de trabalho. 
Nossa equipe estará totalmente dedicada a garantir que todas as etapas sejam executadas com excelência e dentro do prazo, tendo
como data de inicio 01 de agosto de 2024, e término 31 de dezembro de 2024.

Entendemos que imprevistos possam ocorrer, e por isso estamos considerando uma margem de duas semanas, ou seja, até 14 de janeiro
de 2025, para a entrega final do projeto sem aplicação de multa. 

Durante todo o período de desenvolvimento, nossa equipe de gestores de projeto estará disponível para fornecer atualizações regulares sobre o progresso das atividades. 
Caso surjam dúvidas ou necessidade de alinhamentos, estaremos prontos para atendê-lo(a) de maneira ágil e eficiente.

Estamos comprometidos em entregar um projeto de alta qualidade dentro do prazo estipulado e com total transparência. 
Agradecemos a confiança depositada em nossa empresa e reiteramos nosso compromisso com a excelência em cada etapa do desenvolvimento.

* Prazo previsto (em horas): 3000 horas
* Data de início: 01 / 08 / 2024
* Data de término: 31 / 12 / 2024

## Escopo Preliminar e Premissas

## Declaração de Escopo

### Requisitos Funcionais

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

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| Garantia situacional do modelo | ALTA | 
|RNF-002| Suporte multiplataforma do aplicativo móvel | BAIXA |
|RNF-003| Serviço de suporte a longo prazo para clientes | ALTA |
|RNF-004| Garantia de compatibilidade com diferentes modelos e marcas de camêras | MÉDIA |
|RNF-005| Otimização para situações de alta demanda do sistema | ALTA |


### Restrições

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RE-001| Comunicação contextual entre diferentes instâncias do sistema | ALTA | 
|RE-002| Existência de diferentes modos de operação do aplicativo | MÉDIA |
|RE-003| Diferenciação entre modelos específicos de veículos | BAIXA |
|RE-004| Implantação de um sistema interno contra falhas elétricas | ALTA |
|RE-005| Implantação de um sistema que contacte a polícia em caso de detecção de movimentos suspeitos | ALTA |


### Contra-Escopo

A tabela a seguir apresenta as atividades que não serão executadas no projeto

|ID    | Descrição do Contra-Escopo          | 
|------|-------------------------------------|
|CE-001| Treinamento de modelo de LLM        |
|CE-002| Pesquisa de viabilidade do mercado. |
|CE-003| Instalação de câmeras. |
|CE-004| Instalação de alarmes. |
|CE-005| Gerenciamento do servidor de Banco de Dados em nuvem. |

### Condições para início do Projeto

A tabela a seguir, apresente as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto    | 
|------|--------------------------------------------------|
|CI-001| Assinatura de contrato de prestação de serviços. |
|CI-002| Apresentação de garantias definidas no contrato. |
|CI-003| Efetização do contrato da licença com a LLM |
|CI-004| Configuração das máquinas para treinamento da LLM |

## Marcos Agendados e Entregas

A tabela a seguir, identifique os marcos do projeto e os entregáveis previstos (requisitos).

|ID   | Marco do Projeto                                                  | 
|-----|-------------------------------------------------------------------|
|M-1  | Demonstração do funcionamento das funções principais do modelo |
|M-2  | Integração inicial do modelo em um sistema controlado de monitoramento |
|M-3  | Concepção do sistema funcional do projeto para avaliação dos clientes e investidores |
|M-4  | Aperfeiçoamento do modelo para situações do mundo real e adversas |
|M-5  | Integração definitiva para sistemas de segurança e monitoramento |
|M-6  | Interface visual e experiência do usuário com o sistema finalizado do projeto |
|M-7  | Garantia de implementação simplificada para o usuário final, como manuais e documentação |
|M-8  | Reuniões finais com os clientes e investidores para possíveis mudanças ou adições no sistema |
|M-9  | Mudanças de última hora com base no feedback, se necessário |
|M-10 | Lançamento oficial da aplicação |

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
| EAP / WBS             | Zoho | https://www.zoho.com/blog/pt-br |  Organizar visualmente o projeto, o plano e as suas dependências em detalhes. |
| Cronograma do Projeto | GitHub Project |https://github.com/orgs/ICEI-PUC-Minas-PMG-EC-GPS/projects/34/views/1| Utilizado para criar e designar tarefas parra os membros da equipe. |
| Matriz RACI           | | | |

```diff
+ Tarefa 03:
+ Fim da seção a ser atualizada.
```

----
