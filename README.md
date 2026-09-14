<img width="974" height="134" alt="image" src="https://github.com/user-attachments/assets/0a53a0bf-93ba-4ff5-a853-cf0914d6eb95" />

<div align="center">

# <h1 align="center"> Cubo Gelationoso - Classificação de clientes bancários com o K-Nearest Neighbors
</div>

## Descrição do Projeto 
<p align="justify">  O projeto consistiu em utilizar o conjunto de dados disponibilizado pelos autores no repositório de aprendizado de máquina da University of California Irvine(UCI)[3] para treinar um modelo preditivo através do algoritmo K-Nearest Neighbors(KNN) para prever a adesão dos clientes a um empréstimo a longo prazo. Esse trabalho foi desenvolvido como atributo da nota parcial da disciplina de Aprendizado de Máquina, lecionada pelo professor Daniel Roberto Cassar. Diferentemente do uso dos autores do artigo, esse modelo vai utilizar somente 7 atributos como alvo para o treinamento e previsões do modelo. O target continua sendo mesmo: o target categórico binário y. Para a utilização devida do algoritmo, foram realizados tratamentos nos dados utilizados como atributos. Dente eles, haviam dados categóricos nominais e dados numéricos, sendo os categóricos contemplados com dados nominais binário. Após o tratamento, esse conjunto de dados foi dividido em dados de treino e teste, bem como foram selecionados atributos, já tratados, e o alvo para formar um novo dataframe, que vai ser utilizado no treinamento do algoritmo. Os dados também foram normalizados para garantir futuras analises quanto ao comportamento desses dados no treinamento do algoritmo. Feitas tais análises, foi realizado o treinamento do modelo baseline, com intuito de comparar sua eficácia com os modelos KNN treinados com a variação dos hiperparâmetros. 

## Conteúdo do repositório
<p align="justify"> Este repositório contém todos os códigos utilizados - presentes no notebook Jupyter, que apresenta a explicação detalhada de cada célula do código - bem como a descrição do trabalho (presente no README)

## Bibliotecas utilizadas
- pandas
- matplotlib.pyplot
- sklearn.model_selection
- sklearn.processing
- sklearn.neighbors
- sklearn.metrics
- searborn
- sklearn.inspection
- itertools
- sklearn.dummy
     
## **Referências**
[1] FACELI, Katti; LORENA, Ana Carolina; GAMA, João; et al. Inteligência Artificial: uma abordagem de Aprendizado de Máquina. 2. ed. Rio de Janeiro: LTC, 2021.

[2] MORO, Sérgio; CORTEZ, Paulo; RITA, Paulo. A data-driven approach to predict the success of banl telemarketing. Decision Support System, v. 62, p. 22-31, 2014. DOI: <https://doi.org/10.1016/j.dss.2014.03.001>. Acesso em 13 set. 2026. 

[3] SCIKIT-LEARN. KNeighbrosClassifier. Disponível em: <https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html>. Acesso em: 13 set. 2026.

[4] WIKIPEDIA. Euclidian distance. Disponível em: <https://en.wikipedia.org/wiki/Euclidean_distance>. Acesso em: 13 set. 2026. 

[5] WIKIPEDIA. Taxicab geometry. Disponível em: <https://en.wikipedia.org/wiki/Taxicab_geometry>. Acesso em: 13 set. 2026.

[6] WIKIPEDIA. Chebshev distance. Disponível em: <https://en.wikipedia.org/wiki/Chebyshev_distance>. Acesso em: 13 set. 2026.

[7] MORO, Sérgio; CORTEZ, Paulo; RITA, Paulo. Bank Marketing [dataset]. UCI Machine Learning Repository, 2014. DOI:10.24432/C5K306. Disponível em: <https://uci-ics-mlr-prod.aws.uci.edu/dataset/222/bank+marketing>. Acesso em: 13 set. 2026.

[8] SCIKIT-LEARN. sklearn.model_selection.train_test_split. Disponível em: <https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html>. Acesso em: 13 set. 2026. 

[9] SCIKIT-LEARN. 8.3. Preprocessing data: Encoding categorical features. Disponível em: <https://scikit-learn.org/stable/modules/preprocessing.html#encoding-categorical-features>. Acesso em: 13 set. 2026. 

[10] THE PANDAS DEVELOPMENT TEAM. GroupBy: split-apply-combine. In: pandas documentation. Disponível em: <https://pandas.pydata.org/docs/user_guide/groupby.html>. Acesso em: 13 set. 2026.

[11] SCIKIT-LEARN. 3.4. Metrics and scoring: quantifying the quality of predictions — Confusion matrix. Disponível em: <https://scikit-learn.org/stable/modules/model_evaluation.html#confusion-matrix>. Acesso em: 13 set. 2026.

[12] WIKIPEDIA. Confusion matrix. Disponível em: <https://en.wikipedia.org/wiki/Confusion_matrix>. Acesso em: 13 set. 2026.

[13] SCIKIT-LEARN. sklearn.metrics.accuracy_score. Disponível em: <https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html>. Acesso em: 13 set. 2026.

[14] SCIKIT-LEARN. sklearn.metrics.f1_score. Disponível em: <https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html>. Acesso em: 13 set. 2026.

[15] SCIKIT-LEARN. sklearn.inspection.permutation_importance. Disponível em: <https://scikit-learn.org/stable/modules/generated/sklearn.inspection.permutation_importance.html>. Acesso em: 13 set. 2026.

[16] SCIKIT-LEARN. sklearn.metrics.make_scorer. Disponível em: <https://scikit-learn.org/stable/modules/generated/sklearn.metrics.make_scorer.html>. Acesso em: 13 set. 2026.

[17] SCIKIT-LEARN. sklearn.dummy.DummyRegressor. Disponível em: <https://scikit-learn.org/stable/modules/generated/sklearn.dummy.DummyRegressor.html>. Acesso em: 13 set. 2026.

[18] SCIKIT-LEARN. 3.2. Tuning the hyper-parameters of an estimato. Disponível em: <https://scikit-learn.org/stable/modules/grid_search.html>. Acesso em: 13 set. 2026. 

## Desenvolvedora do Projeto
- **Bruna Fujihashi** - [Bruna Fujihashi](https://github.com/buruna087)<br>
Estudante do Bacharelado em Ciência e Tecnologia na Ilum Escola de Ciência.

## Professores 
| <img loading="lazy" src="https://github.com/user-attachments/assets/17dfa7bf-5ca9-42df-b63e-917827fc6308" width=115><br><sub> [Prof. Dr. Daneiel Roberto Cassar](http://lattes.cnpq.br/1717397276752482) | 
| :--: |

