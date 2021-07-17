# ![covid-19_0](https://user-images.githubusercontent.com/84026506/126024231-27b0c6de-f8d7-4f0d-85bd-3a3b4a7123b4.jpg)

Coronavírus é uma família de vírus que, a partir de dezembro de 2019, passou a provocar uma doença infeciosa que chamamos de COVID-19 (coronavírus). O vírus é facilmente tranmitido, podendo causar graves infecções respiratórias que podem levar a morte, tornando-o um vírus temido por toda população global.

# Introdução

Olá, meu nome é Sara Zachi, e esse é meu repositório referente ao projeto do módulo 3 do [Bootcamp De Data Science Aplicada](https://www.alura.com.br/bootcamp/data-science-aplicada/matriculas-abertas) promovido pela [Alura](https://www.alura.com.br/) sobre análise de séries temporais. O objetivo desse projeto é realizar um Modelo de Previsão para o número de casos de COVID-19 em Peranambuco (PE) e no Paraná (PA) a fim de comparar os dois modelos para determinar a direção de ações futuras contra a pandemia do coronavírus.

# Dados explorados

Nesse repositório vamos explorar os dados do número de casos de COVIS-19 disponível no Brasil.IO
* Fonte: Secretarias de Saúde das Unidades Federativas, dados tratados por Álvaro Justen e equipe de voluntários [Brasil.IO](https://brasil.io/home/)
* Brasil.IO: boletins epidemiológicos da COVID-19 por município por dia, disponível em: https://brasil.io/dataset/covid19/caso_full/ (última atualização: 02 de Julho de 2021, acesso em 02 de Julho de 2021).

# Estrutura do projeto

O repositório deste projeto contém duas pastas:
* Notebooks, ontendo os notebooks de [pré análise do banco de dados](https://github.com/SaraZachi/Modelo-Previsao_COVID19/blob/main/Notebooks/01_Primeiras_an%C3%A1lises.ipynb) e notebooks da confexão do Modelo de Previsão do [PA](https://github.com/SaraZachi/Modelo-Previsao_COVID19/blob/main/Notebooks/02_Modelo_de_valida%C3%A7%C3%A3o_PA.ipynb) e de [PE](https://github.com/SaraZachi/Modelo-Previsao_COVID19/blob/main/Notebooks/03_Modelo_de_valida%C3%A7%C3%A3o_PE.ipynb);
* Raw Data, contendo o .zip com o .csv contendo os [dados](https://github.com/SaraZachi/Modelo-Previsao_COVID19/blob/main/Raw%20Data/caso_full.csv.gz) utilizados para as análises.

Além dessas duas pastas, há um outro notebook, nomeado ['Análise_comparativa_modelos'](https://github.com/SaraZachi/Modelo-Previsao_COVID19/blob/main/An%C3%A1lise_comparativa_modelos.ipynb). Neste notebook se encontram os seguintes tópicos:
  1. Introdução, esclarecendo a motivação e objetivo do projeto;
  2. Preseting, onde são feitas as importações das bibliotécas utilizadas neste
  3. Comparações prévias, realizando algumas breves comparações entre o número de casos registrados no PA e o úmero registrado em PE;
  4. Modelos de previsão, no qual foram transcritos a versão final dos modelos realizados nos notbooks ['02_Modelo_de_validação_PA'](https://github.com/SaraZachi/Modelo-Previsao_COVID19/blob/main/Notebooks/02_Modelo_de_valida%C3%A7%C3%A3o_PA.ipynb) e ['03_Modelo_de_validação_PE'](https://github.com/SaraZachi/Modelo-Previsao_COVID19/blob/main/Notebooks/03_Modelo_de_valida%C3%A7%C3%A3o_PE.ipynb).
  5. Conclusões;
  6. Projetos futuros propostos;
  7. Referências.

# Tecnologias utilizadas 💻
O referente projeto foi realizado utilizando a linguagem Python através do google Colaboratory. 
As bibliotecas utilizadas foram:
* Pandas: biblioteca usada para manipulação de dados;
* Matplotlib: biblioteca usada para visualização de dados;
* Seaborn: biblioteca baseada no Matplotlib para visualização de gráficos estatísticos mais complexos;
* Numpy: biblioteca para computação científica em Python;
* fbprophet: Procedimento para prever dados de séries temporais com base em um modelo aditivo, onde as tendências não lineares se ajustam à sazonalidade anual, semanal e diária, além dos efeitos do feriado;
* Sklearn: biblioteca de aprendizado de máquina.

# Contatos ☎️
