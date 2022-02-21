# projeto-01-modulo-06-dsd

Projeto desenvolvido para o Módulo de Machine Learning do Data Science Degree, da Let's Code


### Conteudo

**781_Projeto1_GabrielDAgosto.ipynb**: Notebook principal onde foram feitos os estudos

**finalModelPredictions.pkl**: Arquivo pickle contendo as previsões do modelo final em cima do arquivo **COVID_subm.csv**, que se encontra dentro da pasta datasets

**datasets/**: Pasta contendo o dataset original (covid.csv) e alguns arquivos pickle de estudos do optuna e do dataset tratado

**libs/**: Pasta contendo as seguintes libs:
- **utils**: Funções diversas, criadas por Gabriel d'Agosto ou por colegas
- **lyrioChartingTools**: Funções de gráfico, desenvolvidas pelo meu colega Tiago Lyrio, e adaptadas
- **inverseWeightedMetrics**: Funções para calculo de precision, recall e f1 score com média ponderada inversa, para dar mais peso as classes minoritárias. Desenvolvida por Gabriel d'Agosto
