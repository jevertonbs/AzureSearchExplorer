# Azure Search Explorer

**Passo a Passo - Configuração do Azure AI Search Explorer**

1. **Criação de Recursos no Azure:**
   - Criar um recurso Azure AI Search para gerenciar indexação e consultas.
   - Criar um recurso Azure AI Services na mesma localização do Azure AI Search para fornecer serviços de IA.

2. **Criação de Conta de Armazenamento:**
   - Criar uma conta de armazenamento com contêineres de blob.
   - Configurar o acesso anônimo a blobs.

3. **Upload de Documentos para o Armazenamento:**
   - Baixar e extrair arquivos de revisões de clientes.
   - Criar um contêiner no armazenamento chamado "coffee-reviews".
   - Fazer upload dos documentos para o contêiner.

4. **Indexação de Documentos com Azure AI Search:**
   - No portal Azure, acessar o recurso Azure AI Search.
   - Utilizar o Assistente de Importação de Dados para criar um índice, especificando fonte de dados e habilidades cognitivas.

5. **Consulta no Índice:**
   - Utilizar o Search Explorer para escrever e testar consultas.
   - Visualizar resultados em JSON, filtrar por localização e sentimento.

6. **Revisão do Knowledge Store:**
   - Explorar o armazenamento e visualizar dados enriquecidos pela IA, incluindo projeções, imagens e tabelas.

*Observação:* Certificar-se de que os recursos Azure AI Search e Azure AI Services estão na mesma localização.
