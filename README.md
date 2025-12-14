# MVP – Engenharia de Dados

**Análise Logística e Satisfação no E-commerce Brasileiro**

Este repositório contém o notebook desenvolvido para o MVP da disciplina **Sprint – Engenharia de Dados**, com foco na construção de um pipeline de dados em nuvem para análise de desempenho logístico e satisfação do cliente.

## Dataset
- **Brazilian E-Commerce Public Dataset by Olist**
- Fonte: [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Período: 2016–2018

## Conteúdo
- **`mvp_engenharia_dados_olist.ipynb`**: notebook principal com todas as etapas do pipeline (coleta, modelagem, carga e análise).
- **`README.md`**: Descrição do projeto.

## Ambiente
- **Google Colab** (ambiente de execução em nuvem)

## Arquitetura do Pipeline
O pipeline foi estruturado em três camadas lógicas:

- **Bronze**: dados brutos coletados diretamente do Kaggle
- **Silver**: dados tratados, padronizados e enriquecidos
- **Gold**: dados integrados e modelados em **Esquema Estrela** para análise

## Resultados principais
- **Análises** de atraso na entrega, custo de frete, e avaliação dos clientes.
- **Relacionamento** entre fatores logísticos e satisfação do cliente.
- **Relação** entre localização geográfica e tempo de entrega.

## Como executar
Para rodar localmente, é necessário ter:

- **Python 3.6 ou superior**
- **Bibliotecas**: pandas, numpy, matplotlib, seaborn

No **Google Colab**, basta abrir o notebook e executar `Runtime → Run all`.

## Licença
- Dataset original: **Olist**
- Código do notebook: Disponibilizado publicamente para fins acadêmicos.

---

## Como reproduzir
1. Abra o **notebook** `mvp_engenharia_dados_olist.ipynb` no Google Colab.
2. Execute as células de código para replicar a análise.
3. O dataset será **baixado automaticamente** através do Kaggle API.
