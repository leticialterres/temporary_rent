# Plataforma de aluguéis temporários em Nova York: Uma Jornada Detalhada

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) e modelagem para prever os preços de aluguel temporário em uma plataforma de imóveis em Nova York. Utilizamos sistema operacional Linux e ambiente de desenvolvimento Jupyter Notebook. 

A nossa jornada começa importando os dados e fazendo uma limpeza básica, onde foram tratados valores nulos, duplicados e caracteres especiais nos nomes dos imóveis. Depois, realizamos numa análise mais aprofundada, olhando médias de preço por bairro, tipos de quarto e distrito.

Exploramos visualmente a relação entre diferentes variáveis, como a disponibilidade de quartos, mínimo de noites e preço. Gráficos de dispersão, barras e treemaps foram utilizados para dar uma olhada nos lugares com aluguéis mais caros ou mais baratos. Além disso, foram criadas nuvens de palavras para identificar um padrão no nome de locais com preços mais altos.

Preparar os dados para os modelos é a próxima etapa, foi realizada a conversão de variáveis categóricas em numéricas usando LabelEncoder e padronização das variáveis com StandardScaler e também a divisão do conjunto de dados em treino e teste. Diferentes modelos de regressão foram testados, incluindo Regressão Linear, Support Vector Regression (SVR), RandomForestRegressor e XGBoost. As métricas de avaliação, como MAE, MSE, RMSE e R², foram utilizadas para comparar o desempenho dos modelos.

Os resultados indicaram que o modelo XGBoost teve o melhor desempenho, alcançando um R² de 0.18. No entanto, é importante destacar que a previsão de preços em ambientes dinâmicos, como o mercado imobiliário, pode ser desafiadora e depende de uma variedade de fatores externos.


# Bibliotecas Utilizadas:
pandas: Para manipulação e análise dos dados.
numpy: Para operações matemáticas.
matplotlib e seaborn: Para visualizações gráficas.
plotly.express: Utilizado para criar visualizações interativas.
re: Para manipulação de expressões regulares.
emoji: Para lidar com emojis no processamento de texto.
scikit-learn: Para pré-processamento de dados, modelagem e métricas.
warnings: Para controlar avisos durante o código.
WordCloud: Para criar nuvens de palavras.
xgboost: Implementação do algoritmo XGBoost.
pickle: Para salvar e carregar objetos Python.

# Como Rodar o Projeto:
Ambiente Python:
Certifique-se de ter um ambiente Python instalado em sua máquina.
Instalação das Bibliotecas:
Execute o seguinte comando para instalar as bibliotecas necessárias:
pip install pandas numpy matplotlib seaborn plotly emoji scikit-learn xgboost wordcloud

Execução do Código:
Faça o download do arquivo CSV contendo os dados da plataforma de aluguéis.
Abra o script Python em um ambiente como Jupyter Notebook ou VSCode.
Execute o código linha por linha ou célula por célula para visualizar os resultados passo a passo.
Lembrando que este é um guia geral e a execução pode variar dependendo do ambiente e configuração específicos. Tenha certeza de ter as dependências instaladas e faça ajustes conforme necessário.
