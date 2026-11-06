# PCA e K-Means no Dataset Iris

Este projeto tem como objetivo realizar uma análise comparativa utilizando o algoritmo de Análise de Componentes Principais (PCA) para redução de dimensionalidade, explorando diferentes números de componentes. Após o processo de redução, os dados são aplicados ao algoritmo de clusterização K-Means para formar agrupamentos, com o intuito de identificar as 3 espécies de flores do conjunto de dados Iris.

O trabalho também inclui uma análise exploratória inicial para verificar a distribuição dos dados, identificar correlações e detetar possíveis inconsistências, como outliers, valores nulos e duplicações.

Tecnologias e Bibliotecas Utilizadas

O código foi desenvolvido em Python (Jupyter Notebook/Google Colab) e requer as seguintes bibliotecas:
```
pandas

numpy

matplotlib

seaborn

plotly-express

scikit-learn (PCA, KMeans, StandardScaler, métricas de avaliação)
```

## Estrutura da Análise

Instalação e Importação: Instalação do plotly-express e importação de todos os pacotes necessários.

## Análise Exploratória de Dados (EDA):

* Carregamento do conjunto de dados Iris clássico através do sklearn.datasets.

* Criação de um DataFrame detalhando as dimensões das sépalas e pétalas, juntamente com a variável alvo (espécie).

* Verificação de informações gerais do DataFrame e análise estatística descritiva básica.

* Visualização da correlação entre as variáveis através de um heatmap (mapa de calor) e de um gráfico de dispersão emparelhado (pairplot).

* Aplicação de PCA e K-Means: (Conforme descrito no objetivo inicial, o código prepara o terreno para a aplicação destes algoritmos nas etapas seguintes).

## Como Executar

Certifique-se de que tem o Python 3 instalado no seu ambiente.

Instale as dependências necessárias executando o comando pip install plotly-express pandas numpy matplotlib seaborn scikit-learn.

Execute as células do notebook sequencialmente para observar a análise exploratória e os resultados das modelagens.
