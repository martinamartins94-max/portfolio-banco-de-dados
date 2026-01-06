# Portfólio – Banco de Dados e Análise de Dados

Portfólio de projetos da graduação em Tecnologia em Banco de Dados (PUCRS).

Olá! Eu sou a Martina Martins Pereira e atualmente curso **Tecnologia em Banco de Dados na PUCRS**.  
Este repositório reúne projetos da graduação e estudos pessoais nas áreas de:

- Coleta e preparação de dados  
- Integração de fontes (API REST, CSV, JSON, etc.)  
- Análise exploratória e estatística  
- Uso de Python, pandas e bibliotecas para ciência de dados

---

## Estrutura do portfólio

- `paises-pib-api/` – Integração de dados de países obtidos via API REST com dados de PIB de um arquivo CSV.

Novos projetos serão adicionados conforme eu for avançando na graduação e em estudos práticos.

---

## Projetos

### 1. Integração de dados de países e PIB (API REST + CSV)

**Objetivo:**  
Criar um conjunto de dados consolidado em formato CSV contendo informações de países (código, nome, moeda, população, capital e área) obtidas via **API REST**, integradas com os dados de **PIB (GDP)** coletados de um arquivo CSV.

**Principais etapas do projeto:**

- Consumo de uma API REST desenvolvida em Flask para obter os dados dos países.  
- Leitura e exploração do arquivo `gdp_data.csv` com o histórico de PIB dos países.  
- Tratamento e seleção das colunas relevantes.  
- Junção dos dados de países com os dados de PIB em um único `DataFrame` pandas.  
- Geração do arquivo final `paises_api_com_pib_concat.csv` para uso em análises posteriores.

**Tecnologias usadas:**

- Python  
- Flask / API REST  
- pandas  
- requests  
- Jupyter Notebook

Os arquivos desse projeto estão na pasta `paises-pib-api/` deste repositório.
