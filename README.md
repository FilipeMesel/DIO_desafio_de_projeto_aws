# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 15/06/2023 Empresa: Abstergo Industries Responsável: Filipe Mesel Lobo Costa Cardoso

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1
- Ferramenta: Amazon Bucket S3
- Foco: Armazenamento de arquivos HTML, CSS, Java Script, imagens e etc.
- Descrição: Ideal para armazenar arquivos de plataformas de controle de estoque, rastreabilidade da cadeia de suply da fábrica e ferramentas administrativas que vinherem a ser desenvolvidas.

### Etapa 2
- Ferramenta: Amazon CloudFront
- Foco: Entrega de conteúdo (CDN) da Amazon Web Services (AWS) que tem como foco principal a distribuição de conteúdo de forma rápida e segura para usuários finais em todo o mundo. Ele é projetado para melhorar a velocidade de carregamento de sites, aplicativos e outros conteúdos da web, minimizando a latência e aumentando a disponibilidade.
- Descrição: Proteger o acesso ao Bucket S3

### Etapa 3
- Ferramenta: Amazon Lambda
- Foco: Permite que os desenvolvedores executem código de forma escalável e sem servidor, em resposta a eventos específicos, sem se preocupar com a infraestrutura. Isso proporciona maior agilidade no desenvolvimento e reduz custos, pois os recursos são consumidos apenas durante a execução do código.
- Descrição: Permitir a integração das APIs de Back-end das plataformas cujo Front-end se encontra nos Buckets S3

### Etapa 4 [Extra]
- Ferramenta: Amazon RDS
- Foco: Criação e gerenciamento de bancos de dados
- Descrição: Permitir persistência dos dados de medicamentos, clientes e usuários das plataformas descritas na Etapa 1.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a construção e manutenção de plataformas web, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Assinatura do Responsável pelo Projeto:

Filipe Mesel Lobo Costa Cardoso

