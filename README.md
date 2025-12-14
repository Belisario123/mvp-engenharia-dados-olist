# MVP – Engenharia de Dados

**Análise Logística e Satisfação no E-commerce Brasileiro**

Este repositório contém o notebook desenvolvido para o MVP da disciplina **Sprint – Engenharia de Dados**, com foco na construção de um **pipeline de dados em nuvem** para análise de desempenho logístico e satisfação do cliente, utilizando dados públicos de e-commerce.

## Dataset
- **Brazilian E-Commerce Public Dataset by Olist**
- Fonte: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
- Período: 2016–2018

Trata-se de um conjunto de dados público amplamente utilizado em estudos acadêmicos, contendo informações sobre pedidos, clientes, produtos, vendedores, pagamentos e avaliações.

## Conteúdo do Repositório
- **`mvp_engenharia_dados_olist.ipynb`**  
  Notebook principal com todas as etapas do pipeline:
  - Coleta dos dados
  - Modelagem
  - Carga (ETL)
  - Análise de qualidade
  - Análise dos resultados

- **`README.md`**  
  Documento descritivo do projeto.

## Ambiente de Execução
- **Google Colab** (ambiente de execução em nuvem)

Embora a disciplina direcione o suporte à plataforma Databricks, o Google Colab foi adotado como alternativa em nuvem, conforme permitido pelo enunciado do MVP.

## Arquitetura do Pipeline
O pipeline foi estruturado em três camadas lógicas, seguindo boas práticas de Engenharia de Dados:

- **Bronze**: dados brutos coletados diretamente do Kaggle  
- **Silver**: dados tratados, padronizados e enriquecidos  
- **Gold**: dados integrados e modelados em **Esquema Estrela** para análise  

## Principais Análises Realizadas
- Avaliação do desempenho logístico a partir do tempo de entrega
- Relação entre atraso na entrega e avaliação dos clientes
- Análise do impacto de fatores geográficos no tempo de entrega
- Análise por categorias de produto

## Como Executar

### Opção 1 — Google Colab (recomendado)
- **Notebook no Google Colab:**  
  https://colab.research.google.com/drive/1xd-qq_gyuZMyyx5MkelarO8sdpx7G3sW?usp=sharing

Basta abrir o link acima e executar **Runtime → Run all**.  
Os dados são baixados automaticamente a partir do Kaggle, garantindo total reprodutibilidade.

### Opção 2 — Execução local
Requisitos:
- **Python 3.6 ou superior**
- Bibliotecas:
  - pandas
  - numpy

Após clonar o repositório, execute o notebook `mvp_engenharia_dados_olist.ipynb`.

## Licença
- Dataset: disponibilizado publicamente pela Olist via Kaggle  
- Código: disponibilizado publicamente neste repositório para fins acadêmicos e educacionais
