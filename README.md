# Projeto de Data Warehouse e Analytics  

Bem-vindo ao repositório do **Projeto de Data Warehouse e Analytics**! 🚀  
Este projeto demonstra uma solução completa de data warehousing e analytics, desde a construção de um data warehouse até a geração de insights acionáveis. Projetado como um projeto de portfólio, ele destaca as melhores práticas do setor em engenharia de dados e análise.  

---

## 🏗️ Arquitetura de Dados  

A arquitetura de dados deste projeto segue a Arquitetura Medallion com as camadas **Bronze**, **Silver** e **Gold**:  
![Arquitetura de Dados]()  

1. **Camada Bronze**: Armazena os dados brutos exatamente como vêm dos sistemas de origem. Os dados são ingeridos a partir de arquivos CSV no banco de dados SQL Server.  
2. **Camada Silver**: Inclui processos de limpeza, padronização e normalização dos dados, preparando-os para análise.  
3. **Camada Gold**: Contém os dados prontos para o negócio, modelados em esquema estrela para relatórios e análises.  

---

## 📖 Visão Geral do Projeto  

Este projeto envolve:  

1. **Arquitetura de Dados**: Design de um Data Warehouse moderno usando as camadas **Bronze**, **Silver** e **Gold**.  
2. **Pipelines ETL**: Extração, transformação e carga dos dados dos sistemas de origem para o data warehouse.  
3. **Modelagem de Dados**: Desenvolvimento de tabelas fato e dimensão otimizadas para consultas analíticas.  
4. **Analytics & Relatórios**: Criação de relatórios e dashboards em SQL para geração de insights acionáveis.  

🎯 Este repositório é um excelente recurso para profissionais e estudantes que desejam demonstrar habilidades em:  
- Desenvolvimento SQL  
- Arquitetura de Dados  
- Engenharia de Dados  
- Desenvolvimento de Pipelines ETL  
- Modelagem de Dados  
- Análise de Dados  

---

## 🛠️ Links & Ferramentas Importantes  

Tudo gratuito!  
- **[Datasets](datasets/):** Acesso ao conjunto de dados do projeto (arquivos CSV).  
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Servidor leve para hospedar seu banco de dados SQL.  
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** Interface gráfica para gerenciar e interagir com bancos de dados.  
- **[Repositório Git](https://github.com/):** Crie uma conta no GitHub e um repositório para gerenciar, versionar e colaborar no seu código.  
- **[DrawIO](https://www.drawio.com/):** Criação de arquitetura de dados, modelos, fluxos e diagramas.  
- **[Notion](https://www.notion.com/templates/sql-data-warehouse-project):** Template do projeto no Notion.  
- **[Etapas do Projeto no Notion](https://thankful-pangolin-2ca.notion.site/SQL-Data-Warehouse-Project-16ed041640ef80489667cfe2f380b269?pvs=4):** Acesso a todas as fases e tarefas do projeto.  

---

## 🚀 Requisitos do Projeto  

### Construção do Data Warehouse (Engenharia de Dados)  

#### Objetivo  
Desenvolver um data warehouse moderno usando SQL Server para consolidar dados de vendas, permitindo relatórios analíticos e tomada de decisão.  

#### Especificações  
- **Fontes de Dados**: Importar dados de dois sistemas de origem (ERP e CRM) fornecidos em arquivos CSV.  
- **Qualidade dos Dados**: Tratar e resolver problemas de qualidade antes da análise.  
- **Integração**: Combinar ambas as fontes em um modelo único e amigável, projetado para consultas analíticas.  
- **Escopo**: Foco apenas no conjunto de dados mais recente; não é necessário histórico.  
- **Documentação**: Fornecer documentação clara do modelo de dados para apoiar usuários de negócio e equipes de analytics.  

---

### BI: Analytics & Relatórios (Análise de Dados)  

#### Objetivo  
Desenvolver análises em SQL para fornecer insights detalhados sobre:  
- **Comportamento do Cliente**  
- **Performance de Produtos**  
- **Tendências de Vendas**  

Esses insights oferecem métricas essenciais para os stakeholders, apoiando decisões estratégicas.  

## 📂 Estrutura do Repositório  

