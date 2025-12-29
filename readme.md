# Amazon Product Scraper (Brasil) — Cafeteira Barista

Projeto em Python para coletar informações de produtos na Amazon Brasil a partir de uma busca (ex: **"cafeteira barista"**).  
O script acessa a página de resultados, captura os links dos produtos e entra em cada página para extrair dados como **título, preço, marca, avaliação e número de reviews**, salvando tudo em um arquivo **CSV**.

## Funcionalidades

- Coleta links de produtos na página de resultados da busca
- Extrai de cada produto:
  - **Title** (título)
  - **Price** (preço)
  - **Brand** (marca)
  - **Rating** (avaliação)
  - **Reviews** (quantidade de avaliações)
- Exporta os dados para `amazon_data.csv`

## Tecnologias

- `Python`
- `Pandas`
- `Jupyter Notebook`
- `DataFrames`
