# Conceitos de Data Science: Data Lake

## O que é um Data Lake?

Um **Data Lake** é um repositório de dados de grande escala onde é possível armazenar praticamente qualquer tipo de informação, seja ela **estruturada**, **semiestruturada** ou **não estruturada**.  
Exemplos incluem **tabelas**, **arquivos CSV**, **JSON**, **XML**, **imagens**, **vídeos** e **áudios**.

Suas principais características são:

- **Baixo custo** de armazenamento
- **Alta capacidade** de expansão
- **Grande flexibilidade** no uso e tratamento dos dados

Data Lakes são amplamente utilizados em projetos de:

- **Machine Learning**
- **Business Intelligence (BI)**
- **Big Data**
- **Análises Avançadas**

Entre suas aplicações práticas, destacam-se:

- Empresas que recebem milhões de linhas de logs diariamente
- Projetos de aprendizado de máquina que combinam diferentes tipos de dados (imagens, tabelas, textos)
- Sistemas que necessitam armazenar dados históricos por longos períodos

# Conceitos de Data Science: OneLake e Microsoft Fabric

## O que é o OneLake?

O **OneLake** é o **Data Lake unificado** do **Microsoft Fabric**.

Ele funciona como um **repositório centralizado** para armazenar todos os dados utilizados dentro da plataforma Fabric. É comparável a um "OneDrive dos dados corporativos", mas voltado para projetos de Business Intelligence (BI), Engenharia de Dados, Ciência de Dados e Inteligência Artificial (IA).

**Principais benefícios do OneLake:**

- Armazena todos os dados em um único local.
- Integração nativa com ferramentas do Microsoft Fabric (Power BI, Synapse, Data Factory, Machine Learning, etc.).
- Utiliza o formato **Delta Lake** como padrão, garantindo versionamento e alta performance.
- Governança, segurança e compartilhamento centralizados.
- Evita cópias desnecessárias de dados.

---

## O que é o Microsoft Fabric?

O **Microsoft Fabric** é uma **plataforma completa de dados e análises** que unifica diversas soluções da Microsoft, como:

- **Power BI** (Business Intelligence)
- **Azure Synapse Analytics** (Data Engineering e Data Warehousing)
- **Azure Data Factory** (Integração e ETL)
- **Azure Machine Learning** (Data Science e Modelagem)

**Objetivos do Microsoft Fabric:**

- Facilitar a construção de projetos analíticos completos de ponta a ponta.
- Reduzir a complexidade da integração de múltiplas ferramentas.
- Centralizar o armazenamento, a segurança, a governança e a escalabilidade dos dados.

**Principais componentes do Fabric:**

- **Data Engineering**: Construção de pipelines de dados.
- **Data Science**: Modelagem e experimentação de Machine Learning.
- **Data Warehouse**: Armazenamento de dados transacionais.
- **Real-Time Analytics**: Processamento e análise de dados em tempo real.
- **Business Intelligence**: Criação de dashboards e relatórios.
- **Data Activator**: Automatizações baseadas em eventos de dados.

---

## Resumo

| Termo | Definição |
|:------|:----------|
| **Data Lake** | Repositório bruto e massivo de dados |
| **OneLake** | Data Lake central do Microsoft Fabric |
| **Microsoft Fabric** | Plataforma unificada de análise e armazenamento de dados |

---

