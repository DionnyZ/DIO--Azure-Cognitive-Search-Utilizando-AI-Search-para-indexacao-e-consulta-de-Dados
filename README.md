# Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

O objetivo desse desafio foi escrever um resumo do que foi apresentado sobre a mineração de conhecimento e do serviço AI Search da Azure.

## Mineração de conhecimento

Devido a grande quantidade de documentos das organizações, o acesso aos documentos pode ser demorado.
Com a mineração de conhecimento, é possível agilizar o retorno das informações.

**Alguns serviços de pesquisa cognitiva da Azure, incluem:**
- Azure Blob Storage Containers
- Azure Data Lake Storage Gen2
- Azure Table Storage

O enriquecimento de uma IA permite uma compreensão mais profunda do conteúdo pesquisado. Para isso é necessário analisar qual o modelo de treinamento e pesquisa utilizar em cada caso. E os dados utilizados na pesquisa devem estar no formato JSON.

Para o enriquecimento da IA é necessário ter muitos dados, que podem ser adquiridos realizando pesquisas do público, concorrentes, etc. A avaliação de sentimento de texto, agiliza o processo de análise da satisfação dos clientes.


## AI Search

**Na criação de um serviço AI Search, e necessário:**
- Selecionar a assinatura
- Selecionar o grupo de recurso
- Nome do serviço
- Localização
- Nível de preço

Depois criar um recurso de IA que possui os mesmos campos.

**Em seguida criar um Storage account com:**
- Nome do Storage account: é necessário ser único em toda a Azure, o que inclui contas de outros usuário
- Opção de redundância

Depois realizar a configuração para permitir o acesso anônimo, adicionar um novo container e fazer o upload dos documentos no container.

No serviço de AI Search que foi criado, importar o container com os documentos.
É possível realizar buscas filtradas do conteúdo dos documentos, e será exibido o sentimento do texto analisado.
