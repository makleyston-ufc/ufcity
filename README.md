# UFCity
O projeto UFCity oferece um ecosistema de softwares para interligar de forma eficiente todos os recursos de uma cidade. 

A plataforma UFCity é composta por uma arquitetura de redes de computadores formada por 3 camadas: edge, fog e cloud computing. Para cada uma dessas camadas há elementos de softwares dedicados ao processamento, armazenamento e análise de dados. 

Algumas características dessa plataforma são:
* Processamento em cada camada (desobrecarregando os nós da rede).
* Armazenamento distribuído.
* Análise de dados conforme semântica e contexto.
* Escalabilidade e elasticidade dos serviços.
* Open source.
* Gerenciamento dos recursos da cidade: monitoramento e acionamento.
* Suporte à Inteligẽncia Artificial (IA), incluindo análise via machine learning (ML) e tomada de decisão inteligente.
* Análise de fluxo de dados.
* Ações instatâneas baseadas em padrões em fluxo de dados.
* Expansão e adequação das funcionalidades sob demanda baseadas em IA.
* Combinação de fluxo de dados para a composição de novos serviços.
* Processamento de eventos complexos.
* Estrativicação dos dados para um gerenciamento preciso.
* Compartilhamento de dados e recursos da cidade entre subdomínios (multi domínios).
* Fácil integração com outras ferramentas e sistemas.
* Muitas outras características.

## Como utilizar a plataforma UFCity
Cada camada da plataforma deve ser implementada na cidade. A edge computing lida com os dados mais próximos dos usuários, possuindo um conhecimento restrito ao contexto local e oferecendo serviços que auxiliam o processamento e a resposta ao usuário. 
A fog computing possui um conhecimento um pouco mais amplo que a os nós da edge computing. Nesse caso, alguns serviços mais complexos são disponibilizados, tais como anotação semântica dos dados, processamento de eventos complexos e combinação de fluxo de dados. 
A cloud computing possui um conhecimento holístico da cidade, permitindo oferecer serviços estratégicos e inteligentes. A inserção e adequação de serviços na cloud computing é facilitada pelas tecnologias habilitadoras adotadas e pela estratégia de desing baseada em expansão via IA.

Para conhecer mais cada uma dessas camadas e inicializá-las em seu projeto, vejam-as a seguir em seus respectivos repositórios.

### Edge computing
O [Edge Module](https://makleyston-ufc.github.io/ufcity-edge-module/) é um componente leve, desenvolvido em C++, e eficiente para realizar processamento, agrupamento, filtragem e sumarização de dados, além de introduzir elemtnos contextuais de espaço. 
Por ser desenvolvido em C++ pode ser executado em diversos dispositivos, como smartphones e Respberry Pi.

### Fog computing
A fog computing foi projetada sob a perspectiva de serviços conteinerzados. Para tando, adotamos o Docker para gerenciar esses conteiners. 
Nessa camada há diversos componentes de softwares, dentre eles os desenvolvidos dentro desse projeto: [UFCity-Handler](), [UFCity-CEP]() e [UFCity-Semantic](). 
Outros componentes são introduzidos a partir de seus fornecedores oficiais, como [Mosquitto](), [FluentD](), [MongoDB](), [Elastich]() e [Kibana]().

### Cloud computing
A cloud computing possui um conhecimento amplo da cidade, possibilitando gerenciar serviços de recursos de toda a cidade. 
Essa camada foi desenvolvida utilizando a infraestrutura [OpenStack]() para nuvens. 
Nessa camada, os elementos de procesamento inteligente e tomada de decisão baseados em IA desempenham um papel importante. Para isso, a UFCity adota a ferramenta [Zun]() para o gerenciamento de containers de microsserviços equipados com recursos de IA. Outras ferramentas gerencia a distribuição de cargas, elasticidade permitindo o processamento e armazenamento adequado para qualquer modelo de cidade.
Um arquivo de inicialização da nuvem via OpenStack pode ser alcançado [AQUI]().
