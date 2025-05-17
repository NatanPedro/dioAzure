# dioAzure

## Microsoft Azure – Localizando Serviços por Categoria

No portal do Azure, os serviços são organizados por categorias para facilitar o acesso. Exemplos:

- Computação: Máquinas Virtuais, Azure App Service, AKS.
- Rede: VNet, Load Balancer, Application Gateway.
- Armazenamento: Blob Storage, Disk Storage.
- Bancos de Dados: Azure SQL, Cosmos DB.
- IA e Machine Learning: Azure OpenAI, Cognitive Services.
- Ferramentas de DevOps: Azure DevOps, GitHub Actions.

---

## Benefícios da Nuvem Azure

- Escalabilidade sob demanda.
- Alta disponibilidade global com regiões distribuídas.
- Segurança corporativa com RBAC e criptografia.
- Redução de custos com o modelo pay-as-you-go.
- Inovação rápida com integração a serviços inteligentes.


## Modelos de Serviço: IaaS, PaaS e SaaS

IaaS - Infraestrutura gerenciada pelo cliente - VMs, Storage, VNet
PaaS - Plataforma gerenciada, cliente cuida do app - App Service, Azure SQL
SaaS - Tudo gerenciado pelo provedor - Microsoft 365, Dynamics 365

---

## Componentes de Arquitetura do Azure

- Recursos: unidades de computação, rede, armazenamento.
- Grupo de Recursos: agrupamento lógico de recursos.
- Assinatura (Subscription): contrato de uso do Azure.
- Região: localização geográfica dos recursos.
- Zona de Disponibilidade: redundância e tolerância a falhas.
- Azure Resource Manager (ARM): gerenciador de infraestrutura como código.

---

## Computação e Rede no Azure

### Computação:
- Máquinas Virtuais (VMs)
- App Services (PaaS)
- Azure Kubernetes Service (AKS)
- Azure Functions (Serverless)

### Rede:
- VNet (rede privada virtual)
- Load Balancer (camada 4)
- Application Gateway (camada 7)
- VPN Gateway

---

## Configurando Recursos e Dimensionamento de VMs

Ao criar uma VM, é possível configurar:

- SKU/tamanho (CPU, RAM)
- Tipo e tamanho de disco (SSD, HDD)
- Região de implantação
- Sistema operacional
- Rede (VNet, IPs, NSG)
- Autoescalonamento e balanceamento
- Scripts de inicialização automatizados

---

## Análise de Sentimentos com Language Studio no Azure AI

A Análise de Sentimentos é um recurso do Azure Language Service que avalia o tom emocional presente em textos (positivo, negativo, neutro ou misto).

### Principais pontos:
- Ferramenta utilizada: Language Studio (https://language.cognitive.azure.com)
- Analisa textos e retorna scores de sentimento por frase e por documento.
- Pode ser usada para processar opiniões em redes sociais, reviews, feedbacks etc.
- Suporte multilíngue (incluindo português).
- Pode ser testada sem necessidade de código, diretamente no portal.

---

## Azure Cognitive Search: Utilizando AI Search para Indexação e Consulta de Dados

O Azure Cognitive Search combina busca tradicional com enriquecimento cognitivo, permitindo análise avançada e indexação inteligente de conteúdos.

### Funcionalidades:
- Indexação de documentos em diversos formatos (PDF, Word, imagens com OCR).
- Enriquecimento de conteúdo com serviços cognitivos (extração de frases-chave, entidades, etc.).
- Suporte a busca semântica e consultas em linguagem natural.
- Ideal para construir buscas empresariais inteligentes ou portais de conhecimento.
- Pode ser integrada com IA generativa para fornecer respostas contextuais ao invés de apenas listar resultados.

---

## Explorando os Recursos de IA Generativa com Copilot e OpenAI

A IA Generativa é aplicada para criar novos conteúdos a partir de comandos em linguagem natural, como texto, código ou imagens.

### GitHub Copilot:
- Ferramenta baseada em Codex (modelo da OpenAI) integrada ao VS Code e GitHub.
- Auxilia desenvolvedores gerando código automático, sugestões, testes e até documentação.
- Ideal para aumentar a produtividade e reduzir o tempo de codificação.

### Azure OpenAI:
- Serviço que traz modelos como GPT-3.5, GPT-4 e DALL·E para o ambiente Azure.
- Permite criar aplicativos com IA generativa para:
  - Geração de texto automatizado.
  - Resumos, respostas automáticas e assistentes virtuais.
  - Criação de imagens a partir de texto com o DALL·E.
- Segurança empresarial com RBAC, redes privadas e conformidade corporativa.

---

## Conclusão

As ferramentas de IA do Azure tornam possível aplicar inteligência artificial em projetos reais de forma simples e escalável, mesmo sem escrever código. Combinando análise de sentimentos, pesquisa cognitiva e IA generativa, é possível criar soluções modernas e inteligentes para diversos contextos corporativos.


