### Fundamentos do Azure

- [O que é Azure?](#what-is-azure)
- [Quais são as principais categorias do serviço do Azure?](#categorias-azure)
- Criação de conta Azure
- Portal Azure
- Azure Resource Manager
- Prova de certificação AZ-900: Azure Fundamentals

--- 

<div id="what-is-azure" />

### O que é o Azure?

É um conjunto cada vez maior de serviços de nuvem para ajudar a organização a enfrentar seus desafios de negócios com a liberdade de poder criar, gerenciar, construir e implantar aplicações em uma enorme rede global usando suas ferramentas e estruturas favoritas

![azure](https://user-images.githubusercontent.com/34458509/152707851-3ebf2ff4-7372-4be6-99bf-1561a52f6ca6.png)

---

<div id="categorias-azure" />

### Principais Categorias de Serviço do Azure

O Microsoft Azure dispõe de mais de 600 serviços, distribuidos em categorias sendo elas: computação, rede, armazenamento, móvel, banco de dados, web, IoT, big data, inteligência artificial e DevOps.

![categorias-azure](https://user-images.githubusercontent.com/34458509/152708066-dad28135-7635-42f7-a430-22a28a450573.png)

---

#### Tipos de Serviços de Computação

![servicos](https://user-images.githubusercontent.com/34458509/152708441-875e4aa5-014d-45bc-81b5-86c7f3f44fe1.png)

- **Azure Functions:** serviço de computação sem servidor controlado por eventos;
- **Azure Kubernetes Service:** permite o gerenciamento de um cluster de VMs que executam serviços em containers;
- **Azure Container Instance:** serve para executar aplicações em containers no Azure sem provisionamento de servidores nem de máquinas virtuais;
- **Azure Service Fabric:** plataforma de sistemas distribuidos e é executado no Azure ou até mesmo localmente;
- **Azure Virtual Machine Scales Set:** ajuda no dimensionamento de VMs do windows ou linux hospedadas no Azure;
- **Azure Virtual Machine:** são máquinas virtuais do windows ou linux hospedadas;
- **Azure Batch:** que é um serviço gerenciado para aplicações paralelos e de alto desempenho;

---

#### Tipos de Serviços de Rede

Vincular recursos de computação e fornecer acessos as aplicações são as principais funções da rede Azure. A funcionalidade da rede na Azure inclui uma variedade de opções para conectar o mundo exterior aos serviços  e recursos nos datacenters globais do microsoft Azure.

![servicos-de-rede](https://user-images.githubusercontent.com/34458509/152710123-2419526e-8637-4d36-9101-e2543852939e.png)

- **Azure Virtual Network:** conecta VMs a conexões de VPN, ou seja, de rede virtual privada de entrada;
- **Azure Load Balancer:** permite o gerenciamento de closter de VMs executem serviços em containers;
- **Azure Application Gateway:** ajuda a otimizar a entrega de form de servidores da aplicação aumentando assim simultaneamente a segurança da aplicação;
- **Azure VPN Gateway:** acessa as redes virtuais do Azure por meio de Gateways VPN de alto desempenho;
- **Azure DNS:** fornece resposta de DNS extremamente rápidas e disponibilidade de domínios extremamente alta;
- **Azure CDN:** que distribui o conteúdo de alta largura de banda para clientes do mundo todo;
- **Azure DDoS Protection:** protege as aplicações hospedadas no Azure contra ataques DDoS, ou seja, de negação de serviço distribuido;
- **Azure Traffic Manager:** distribui o tráfego de rede entre as regiões do Azure como um todo;
- **Azure ExpressRoute:** conecta-se com o Azure por meio de conexões seguras, dedicadas de alta largura de banda;
- **Azure Network Watcher:** monitora e diagnostica problemas de rede usando a análise baseada em cenário;
- **Azure Firewall:** implementa o firewall de alta segurança e alta disponibilidade com escabilidade ilimitada;
- **Azure Virtual WAN:** cria uma WAN, ou seja, uma rede de longa distância unificada conectando sites locais e remotas;

---

#### Tipos de Serviços de Armazenamento

O Azure fornece 4 tipos principais de serviços de armazenamento

![tipos-armazenamento](https://user-images.githubusercontent.com/34458509/152710492-551fa60d-dbfe-47db-af0d-9b8e2b189f3d.png)

- **Azure Blob Storage:** para objetos grandes como arquivos de vídeo ou bitmaps;
- **Azure File Storage:** compartilhamento de arquivos que pode acessar gerenciar como servidor de arquivos;
- **Azure Queue Storage:** armazenamento de dados para enfileiramento de mensagens e a entrega confiavel delas entre as aplicações;
- **Azure Table Storage:** repositório noSql independentes de qualquer esquema;

---

#### Tipos de Serviços Banco de Dados

O Azure fornece vários serviços de banco de dados para armazenar uma ampla variedade de volumes de tipos de dados e com a conectividade global esses dados ficam disponíveis para os usuários instantaneamente

![tipos-servicos-banco-de-dados](https://user-images.githubusercontent.com/34458509/152711212-790812b2-4d0a-45d8-a0a9-b74c4ea94e74.png)

- **Azure Cosmos DB:** distribuido globalmente que da suporte a opções de noSql;
- **Azure SQL Database:** relacional totalmente gerenciado com dimensionamente automático, inteligência integral e uma segurança totalmente robusta;
- **Azure MySQL Database:** relacional do mySql totalmente gerenciado e escalonável com alta disponibilidade e segurança;
- **Azure PostgreSQL Database:** totalmente gerenciavél e escalonável com alta disponibilidade e segurança;
- **SQL Server ou VM's:** hospedam aplicações empresariais SQL Server na nuvem;
- **Azure Synapse Analytics:** data warehouse gerenciado com segurança integral em todos os níveis de escala sem custo adicional;
- **Azure Database Migration Service:** serviço de migração de bancos de dados para nuvem sem alteração no código da aplicação;
- **Azure Cache for Redis:** armazena em cache os dados estáticos usados com frequência para reduzir a latência de dados de aplicações;
- **Database for MariaDB:** relacional para MariaDB totalmente gerenciavél e escalonável com alta disponibilidade e segurança;

---

#### Tipos de Serviços Web

No mundo dos negócios atuais é essencial ter uma experiência de sucesso da Web o Azure inclui suporte de primeira classe para criar e hospedar aplicações web e serviços web baseado em HTTP os serviços do Azure voltado para hospedagem de Web inclui:

![servicos-web](https://user-images.githubusercontent.com/34458509/152711692-4b5d6848-e141-4ff0-bc02-cc10b5ba841c.png)

- **Azure App Service:** criação rápida de aplicações de nuvem poderosas baseados na Web;
- **Azure Notification Hub:** envio de notificações por push para qualquer plataforma de qualquer backend;
- **Azure API Management:** publica APIs para desenvolvedores parceiros e funcionários de maneira segura e em escala;
- **Azure Web Apps:** ajuda a criar e implantar aplicações web criticas em escala;
- **Azure Signal Service:** adiciona funcionalidades da Web em tempo real com facilidade;

---

#### Tipos de Serviços de Big Data

Os dados vem em todos os formatos e tamanhos, big data é um grande volume de dados (sistema de clima, sistema de comunicação, pesquisas genomica, plataforma de geração de imagem e muitos outros cenários que produzem centenas de gigabytes de dados). Com essa quantidade de dados se torna dificil de analisar e tomar decisões, o volume geralmente é tão grande que formas tradicionais de processamento e análise não são mais apropriadas.
Tecnologias de cluster e softwares livres foram desenvolvidas para lidar com esse grande volume de dados:

![servicos-big-data](https://user-images.githubusercontent.com/34458509/152712249-18ff2161-7b08-4bf2-a2af-d6798dd871ac.png)

- **Azure Synapse Analytics:** executa análise em grande escala usando o EDW que é o Enterprise Data Warehouse baseado em nuvem e aproveita o PP (Processamento Paralelo) massivo para executar consultas complexas rapidamente em tetabyte de dados;
- **Azure HDInsight:** serviço que processa grandes quantidade de dados com clusters gerenciadas de clusters hadoop na nuvem;
- **Azure Databricks:** serviço de análise colaborativo com base no Apache Spark que pode ser integrado com outros serviços de big data no Azure;

---

#### Tipos de Serviços de Inteligência Artificial

Inteligência artificial no contexto de computação em nuvem basea-se em uma ampla gama de serviços cujo núcleo é uma machine learning (técnica de ciência de dados que permite que os computadores usem os dados existentes para prever futuros comportamentos, resultados e tendências) usando o aprendizado de máquina os computadores aprendem ser sem explicitamente programados. As estimativas ou previsões de aprendizados de máquina podem tornar as aplicações e dispositivos muito mais inteligentes.

![servicos-ia](https://user-images.githubusercontent.com/34458509/152713544-e39f1a12-3106-45e6-aba1-27e912908d6c.png)

- **Azure Cognitive Search:** serviço de pesquisa e bsuca totalmente gerenciada;
- **Azure Machine Learning Service:* ambiente baseada em nuvem usadad para desenvolver, treinar, testar, implantar e gerenciar e ate acompanhar modelos de aprendizado de maquina podendo ajustar e ate criar;
- **Azure Machine Learning Studio:** worskpace colaborativo do tipo arrastar e soltar podendo criar, testar, implantar soluções de aprendizado de máquina usando modulos de manipulação de dados e algoritmos de aprendizados de máquinas pré criados;
- **Cognitive Services:** serviços de inteligência artificial e APIs cognitivas para criação de aplicativos mais inteligentes;
- **Bot Services:** serviço gerenciado e criado especificamente para desenvolvimento de bot;

---

#### Tipos de Serviços de DevOps

O DevOps reúne pessoas, processos e tecnologias, automatizando a entrega de software para fornecer valor contínuo aos usuários. Com o Azure DevOps você pode criar, compilar e lançar pipelines que fornecem integração, entrega e implantação contínuas para seus aplicativos. Você pode integrar repositórios e testes de aplicativos, executar o monitoramento de aplicativo e trabalhar com artefatos de compilação. Você também pode trabalhar os itens e inseri-los em uma lista de pendências do produto para acompanhar, automatizar a implantação de infraestrutura e integrar uma série de ferramentas e serviços de terceiros, como Jenkins e Chef. Todas essas funções e muitas outras estão totalmente integradas ao Azure a fim de permitir implantações consistentes e repetíveis para seus aplicativos, visando fornecer processos de build e versão simplificados.

![servicos-devops](https://user-images.githubusercontent.com/34458509/152714221-f52b63d4-6bc3-4b1a-805c-5e67d2bdfba7.png)

- **Azure DevOps:** Use ferramentas de colaboração de desenvolvimento, tais como pipelines de alto desempenho, repositórios Git privados gratuitos, quadros Kanban configuráveis e amplos testes de carga baseados em nuvem automatizados;
- **Azure DevTest Labs:** Crie rapidamente ambientes Windows e Linux sob demanda para testar ou demonstrar aplicativos diretamente dos pipelines de implantação.
- **Azure Boards:** ferramentas Agile comprovadas para planejar, monitorar e discutir o trabalho com as equipes.
- **Azure Pipelines:** compile, teste e implante com CI/CD que funciona em qualquer linguagem, plataforma e nuvem, podendo se conectar ao GitHub ou a qualquer outro provedor Git e implantar continuamente.
- **Azure Repos:** repositórios Git privados, hospedados na nuvem e ilimitados e colabore para compilar códigos melhores com solicitações de pull e gerenciamento de arquivos avançado.
- **Azure Test Plans:** ferramentas de teste exploratório e manual.
- **Azure Artifacts:** criação, hospedagem e compartilhamento de pacotes com a equipe e adição de artefatos a pipelines de CI/CD com um único clique.

---

#### Referências:

- [Introduction to Azure fundamentals](https://docs.microsoft.com/pt-br/learn/modules/intro-to-azure-fundamentals/)
