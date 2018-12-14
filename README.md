# Udacity Nanodegree Fundamentos de Data Science 2 - Projeto 1 (Análise de dados do Metrô de NY)

O sistema de ônibus e trens de Nova Iorque - o Metro Transit Authority (MTA) - fornece seus dados para download através de arquivos csv. Uma das informações disponíveis são os dados das catracas do metrô que contém logs semanais de entradas cumulativas e saídas por catraca por estação de metrô em algum intervalo de tempo.

O objetivo deste projeto foi explorar a relação entre os dados das catracas do metro de Nova Iorque e o clima no dia da coleta.

#### Dados utilizados:
- Catracas - http://web.mta.info/developers/turnstile.html (apenas Junho/2017)
- Previsão do tempo - https://s3.amazonaws.com/content.udacity-data.com/courses/ud359/turnstile_data_master_with_weather.csv

#### Características do projeto:
- Todo o trabalho foi realizado num Notebook [Jupyter](http://jupyter.org/).
- Dados de catracas e previsão do tempo são baixados automaticamente com o uso de bibliotecas `requests` e `BeautifulSoup`
- Uso das bibliotecas `numpy` e `pandas` para análise e arrumação dos dados
- Uso da biblioteca `matplotlib` para plotagem dos gráficos
- Criação de um `Map Reduce` para fazer agregações dos dados volumosos num ambiente [Hadoop](https://hadoop.apache.org/)
