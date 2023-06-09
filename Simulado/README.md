# Simulados Senai e Microsoft e Algunas perguntas de outros Simulado.

Link Simulado Microsoft: https://learn.microsoft.com/pt-br/certifications/exams/dp-900/practice/assessment?assessment-type=practice&assessmentId=24


# Pontuaçoes e tentativas:

- Simulado Microsoft: 80% - Media </p>
- Simulados Senai: 1°90% 2°100% 3°100% 4°100% e Final: 1-2-3-4 - 90% de media </p>
- Provas 680 pontos minha ultima tentativa - 2022 </p>
- Prova 716 pontos PASS -2023

# Perguntas que tenho duvidas ainda. Simulados DP-900

# Pergunta 1

Qual das tarefas a seguir é responsabilidade de um administrador de banco de dados?

Fazer backup e restaurar bancos de dados (Correto) </P>
Criar painéis e relatórios </P>
Criar pipelines para processar dados em um data lake </P>

# Pergunta 2

Qual função provavelmente usará o Azure Data Factory para definir um pipeline de dados para um
processo ETL?

Administrador de Banco de Dados </P>
Engenheiro de Dados (Correto) </P>
Analista de Dados </P>

# Pergunta 3

Qual serviço único você usaria para implementar pipelines de dados, análise de SQL e análise do
Spark?

Banco de Dados SQL do Azure </P>
Microsoft Power BI </P>
Azure Synapse Analytics (Correto) </P>

# Pergunta 4

O que é totalmente gerenciado e não requer alterações em um banco de dados para migração?

Selecione apenas uma resposta.

Banco de Dados SQL do Azure </P>
Instância Gerenciada SQL do Azure (correta) </P>
SQL Server em Máquinas Virtuais do Azure executando o Windows </P>
SQL Server em Máquinas Virtuais do Azure executando Linux </P>

- Feedback : Azure SQL Managed Instance é um serviço de plataforma como serviço (PaaS) que dá suporte à maioria dos mesmos recursos do Azure SQL. O Azure SQL não oferece suporte a tantos recursos SQL quanto a SQL Managed Instance. SQL Server em Máquinas Virtuais do Azure executando Windows e Linux não são gerenciados.

# Pergunta 5

Escolha a opção correta para completar a frase: ___________________ é um objeto associado a uma tabela que classifica e armazena as linhas de dados com base em seus valores de chave.

Uma tabela de arquivos  </p>
Um procedimento armazenado  </p>  </p>
Uma chave estrangeir  </p>
Um índice clusterizado (correta) </p>


# Pergunta 6

Você precisa modificar uma exibição em um banco de dados relacional adicionando uma nova coluna. Qual declaração você deve usar?

MERGE </p>
INSERT  </p>
UPDATE </p>
ALTER  (correta) </p>

# Pergunta 7

Escolha a opção correta para completar a frase: ___________________ suportam nativamente a análise de relacionamentos entre entidades.

Bancos de dados de família de colunas
 
Bancos de dados de gráficos (correta) </p>
Bancos de dados de documentos </p>
Armazenamentos de valores-chave </p>


Link: https://docs.microsoft.com/pt-br/azure/architecture/guide/technology-choices/data-store-overview


# Pergunta 8

Quais serviços do Azure você pode usar para criar um pipeline para ingestão e processamento de dados?

Banco de Dados SQL do Azure e Azure Cosmos DB </p>
Azure Synapse Analytics e Azure Data Factory (correta) </p>
Azure HDInsight e Azure Databricks </p>

# Pergunta 9

O que você precisa definir para implementar um pipeline que lê dados do Armazenamento de Blobs do Azure?

Um serviço vinculado para sua conta de Armazenamento de Blobs do Azure (correta)  </p>
Um pool de SQL dedicado em seu workspace do Azure Synapse Analytics </p>
Um cluster do Azure HDInsight em sua assinatura </p>

# Pergunta 10

Qual mecanismo de processamento distribuído de código aberto é incluído no Azure Synapse Analytics?

Apache Hadoop </p>
Apache Spark (correta) </p>

# Pergunta 11

Como você pode permitir que usuários distribuídos globalmente trabalhem com uma réplica local própria de um banco de dados do Cosmos DB?
 
Crie uma conta de Azure Cosmos DB em cada região em que você tenha usuários. </p>
Use a API de Tabela para copiar dados para o Armazenamento de Tabelas do Azure em cada região em que você tenha usuários. </p>
Habilite gravações de várias regiões e adicione as regiões onde você tem usuários. (correta) </p>


# Pergunta 12

No fluxo de trabalho comum do Power BI, qual das seguintes etapas vem primeiro?

Exiba e interaja com dashboards compartilhados e relatórios nos aplicativos do Power BI Mobile. </P>
Compartilhe seus dashboards com outras pessoas, especialmente as que estiverem trabalhando </P>
Traga dados para o Power BI Desktop e crie um relatório (correta) </P>
Publique no serviço do Power BI, no qual você pode criar novas visualizações ou criar dashboards. </P>


# Pergunra 13

Qual das afirmações a seguir descreve melhor um dashboard do Power BI?

Uma coleção de dados que o Power BI usa para criar visualizações </P>
Uma representação visual dos dados, como um gráfico, um mapa codificado por cores ou outros itens interessantes que você pode criar para representar seus dados </P> visualmente.
Uma coleção de visualizações que aparecem juntas em uma ou mais páginas. </P>
Uma página de um relatório ou coleção de visualizações. (correta) </P>


# Pergunta 14

Qual serviço você usaria para capturar continuamente dados de um Hub IoT, agregá-los em períodos temporais e armazenar os resultados no Banco de Dados SQL do Azure?

Azure Cosmos DB </P>
Stream Analytics do Azure (correta) </P>
Armazenamento do Azure </P>

# Pergunta 15


Escolha a opção correta para completar a frase: Um processo de extração, carregamento e transformação (ELT) requer ___________________

1- um armazenamento de dados de destino poderoso o suficiente para transformar dados. (correto) </p>
2- um pipeline de dados que inclui um mecanismo de transformação. </p>
3- dados que são totalmente processados ​​antes de serem carregados no armazenamento de dados de destino. </p>
4- um motor de transformação separado. </p>

Explicação: </p>
Com o ELT, o armazenamento de dados usado para realizar a transformação é o mesmo armazenamento de dados em que os dados são consumidos. </p>
Link: https://docs.microsoft.com/pt-br/azure/architecture/data-guide/relational-data/etl </p>


# Pergunta 16

Qual das alternativas não é verdadeira?

1- Extrair, carregar e transformar (ELT) minimiza o tempo necessário para copiar grandes volumes de dados para os sistemas de destino. (correto) </p>
2- Extrair, transformar e carregar (ETL) pode reduzir o tempo de transferência de dados para sistemas de destino. </p>
3- Extrair, carregar e transformar (ELT) transforma dados usando um recurso de computação independente do sistema de origem e do sistema de destino. </p>

Explicação: </p>
Resposta falsa: Extrair, carregar e transformar (ELT) transforma dados usando um recurso de computação independente do sistema de origem e do sistema de destino. </p>
ETL: ...a transformação de dados que ocorre geralmente envolve várias operações, como filtragem... </p>
ELT: ...Esta abordagem ignora a etapa de cópia de dados presente no ETL, que pode ser uma operação demorada para grandes conjuntos de dados... Load e Trasformation estão no mesmo destino </p>

- Referência: https://docs.microsoft.com/pt-br/azure/architecture/data-guide/relational-data/etl </p>


# Pergunta 17

Escolha a opção correta para completar a frase: ___________________ é uma tabela virtual que contém conteúdo definido por uma consulta.

1- Um procedimento armazenado </p>
2- Uma view (correto) </p>
3- Um heap </p>
4- Um Índice </p>
 
Explicação: </p>
Resposta correta: Uma View </p>
é uma tabela que está sendo criada com base em uma consulta do usuário </p>
Referência: https://docs.microsoft.com/pt-br/sql/relational-databases/views/views </p>

# Pergunta 18

Escolha a opção correta para completar a frase: A transcrição de arquivos de áudio é um exemplo de análise ___________________

1- preditiva </p>
2- cognitiva </p>
3- prescritiva </p>
4- descritiva (Correta) </p>


# Pergunta 19

Escolha a opção correta para completar a frase: ___________________ classifica fisicamente os dados em uma tabela com base nos valores em uma coluna especificada.

1- Um índice clusterizado (Clustered Index)
2- Um índice não clusterizado (Non-Clustered Index)
3- Um procedimento armazenado (Procedure) 
4- Uma vista (View)

Explicação:
Resposta Correta: Índices clusterizados.

Referência: https://docs.microsoft.com/pt-br/sql/relational-databases/indexes/clustered-and-nonclustered-indexes-described?view=sql-server-ver15

# Pergunta 20

Qual API do Azure Cosmos DB permite implementar um banco de dados não relacional e nós de modelo que têm relacionamentos entre eles?

R: Apache Gremilin

Link:  https://learn.microsoft.com/pt-br/azure/cosmos-db/gremlin/introduction
