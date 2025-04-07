# Azure Databricks Exploration

## Descrição do Projeto
Este repositório tem como objetivo explorar os recursos do Microsoft Azure, com foco no Azure Databricks. As atividades estarão organizadas em subpastas, cada uma representando uma etapa diferente da exploração.

## Estrutura do Repositório

├── 1_Criacao_Resource_Group <br/> 
├── 2_copy_files_project <br/> 
├── 3_azure-databricks_notebook_project <br/> 
├── 4_...<br/>
└── README.md

### 1. Criação de Resource Group, Resource e Dashboard
Esta seção documenta o processo de criação de um Resource Group, a alocação de recursos no Azure e a configuração de um dashboard para monitoramento.

**Passos:**
1. Criar um Resource Group no Azure.
2. Provisionar um recurso (exemplo: Azure Data Factory).
3. Configurar um dashboard no Azure para monitoramento.

### 2. Criação de pipeline para cópia de arquivo usando o Azure Data Factory
Esta seção documenta a criação de um pipeline de cópia de arquivo usando recursos do Azure como Data Factory e Blob Storage.

**Passos:**
1. Criar um Storage Account e containers.
2. Abrir o Data Factory Studio.
3. Explorar o Integration Runtime para configuração de conexões com ambientes on-premisses.
4. Configurar um Linked Service.
5. Criar um pipeline configurando fonte, destino e formato.
6. Fazer validações e verificar possíveis correções.
7. Publicar as alterações.
8. Executar o pipeline.
9. Verificar detalhes de execução e resultado da operação.

### 3. Explorando o notebook do Azure Databricks
Esta seção traz prints de exploração de uso do notebook do Databricks. A exploração foi feita usando o Community Databricks, considerando a impossibilidade de criação de cluster via Azure Databricks por limitação de cotas.

**Passos:**
1. Provisionar um recurso do Azure Databricks.
2. Abrir o Databricks Studio.
3. Configurar um cluster. <br/> 
Nota: aqui não foi possível completar a criação do cluster por limitação de cotas da assinatura do Azure. Ainda assim, foi possível explorar as funcionalidades existentes no studio que se conectam com os serviços do Azure, especialmente aquelas relacionadas ao armazenamento de dados.
4. Configurar cluster via Community Databricks.
5. Explorar dataset e recurso de visualização.

### 4. [A ser preenchido]


## Pré-requisitos
- Conta no Microsoft Azure
- Permissões para criar e gerenciar recursos
- Conhecimento básico em Azure Databricks

