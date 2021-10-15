# Projeto utilizando Databricks

Projeto desenvolvido na Pós-Graduação de Big Data, com o intuito de pegar uma grande base, dividi-la e fazer análise de um grande volume.

## Ferramentas Utilizadas

- Databricks
- AWS

Para o AWS será necessário criar uma conta e adicionar a chave no código para testar.

A base foi utilizada está no link:
https://www.kaggle.com/chaitanyahivlekar/large-movie-dataset?select=movies_dataset.csv

## Divisão

Foi feito um pequeno arquivo (python-para-dividir-arquivos) em python utilizando dask para a quebra de múltiplos arquivos. 

## AWS

No AWS subi os arquivos quebrados para servirem como leitura.

## Databricks

Apenas foi criado um cluster e utilizado o código  (databricks.ipynb) para leitura, analise e testes.

## License

MIT