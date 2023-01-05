[![author](https://img.shields.io/badge/autor-ismailymendes-red)](https://www.linkedin.com/in/ismailytm/) [![python](https://img.shields.io/badge/python-3.11%2B-blue)](https://www.python.org/downloads/release/python-3111/) ![pandas](https://img.shields.io/badge/pandas-1.5.2-blue) ![numpy](https://img.shields.io/badge/numpy-1.24.1-blue) ![matplotlib](https://img.shields.io/badge/matplotlib-3.6.2-blue)

# Análise das Cotas para Exercício da Atividade Parlamentar dos Senadores
### Análise dos gastos dos senadores entre os anos de 2018 à 2021.

## Tecnologias utilizadas:

* [Jupyter Notebook](https://jupyter.org/)
* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [Power BI](https://pypi.org/project/gTTS/)

## Como rodar o projeto e fazer alterações:

1. Abra o projeto no Google Colab por [esse link](https://colab.research.google.com/drive/1lY2apmN0bx-TUW2I-DyvoOkYCgnwUsli?usp=sharing)
2. Crie uma pasta chamada *data* e adicione os arquivos abaixo:  
   `despesa_ceaps_2018.csv`,  
   `despesa_ceaps_2019.csv`,  
   `despesa_ceaps_2020.csv`,  
   `despesa_ceaps_2021.csv`,  
   `lista_senadores_55leg.csv`,  
   `lista_senadores_56leg.csv`,  
   `dados_geograficos.csv`
4. Execute todas as células com ctrl+F9
5. Baixe o arquivo gerado despesa_ceaps_final.csv
6. Faça o download do Power BI por [este link](https://powerbi.microsoft.com/pt-br/downloads/) e importe o arquivo despesa_ceaps_final.csv
7. Na importação o Power BI realiza a transformação dos campos para os tipos corretos automaticamente, porém deve-se alterar o tipo do campo "Valor Reembolsado"
8. Clique em ***Transformar Dados***, apague o valor ***{"Valor Reembolsado", Int64.Type}***, clique com o botão direito no campo ***Valor Reembolsado***, ***Alterar tipo*** ***utilizando a localidade*** e selecione ***Número decimal*** e ***Inglês (Estados Unidos)***
9.  Ou se preferir execute o arquivo ceaps_dashboard.pbix para visualizar o dashboard já montado