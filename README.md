# Previsao_de_Cancelamentos_em_Hoteis

#### Aluno: [Marine Patricia Chevallier] (https://github.com/marineche)
#### Orientador: [Dr. Leonardo Alfredo Forero Mendoza] (https://github.com/leofome8)

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- [Link para o código](https://github.com/marineche/mono_bimaster_marine/blob/d8d35251846415fa649a3b53bdb34ead4c148d4a/previsao_cancelamentos_hoteis.ipynb).
---


### Resumo

Nesse projeto o objetivo é extrair informações dos dados que ajudem uma rede de hotéis a evitar cancelamentos, construindo também modelos preditivos para que seja possível ter ações de retenção e identificar os clientes mais propensos a cancelar as reservas.


### Abstract

The purpose of this project is to extract insights from the dataset witch helps a hotel chain to avoid bookings cancellations, and to build predictive's models to make possible have retentions actions and to identify customers that are more will to cancel bookings. 


### 1. INTRODUÇÃO

Muitos hotéis querem diminuir a taxa de cancelamento de reservas. Para isso, devemos extrair dos dados, informações que nos ajudem a diminiur essa taxa. Como por exemplo, analisar se quando uma reserva é reembolsável, se quando o cliente é antigo, dentre outros fatores, influenciam no cancelamento de reservas.

Além disso, foi aplicado um modelo de machine learning supervisionado, que é o de classificação. Nele, temos a variável resposta categórica que é se a reserva foi ou não cancelada. 

Foi feita a leitura e tratamento dos dados, criação de novas variáveis, pré-processamento, análise exploratória e aplicação de modelos de classificação. 


### 2. MODELAGEM

A primeira etapa da modelagem é o pré-processamento dos dados, onde selecionamos as variáveis que são relevantes para o modelo, as tratamos ou até mesmo criamos novas variáveis.
Após tratar e normalizar os dados, vamos aplicar modelos de classificação: Logistic Regression, K-Nearest Neighbor, Decision Tree, Random Forest e Support Vector Classification.

### 3. RESULTADOS

Os algoritmos que tiverm a melhor performance foram a Árvore de decisão e o Random Forest, ambos com aproximadamente 76% de acurácia.
Como essa base é de cancelamentos (eventos) e não temporal/sazonal e queremos prever o cancelamento, então podemos separar a base de treino e teste aleatoriamente como foi feito nesse desafio, pois não queremos fazer uma previsão temporal e sim eventual. 
Se quiséssemos fazer uma classificação no tempo/sazonal, então a separação também seria sazonal, pegando os últimos dados (ano de 2017 por exemplo) como teste/validação.


### 4. CONCLUSÕES


Os dados fornecidos por essa base de dados são de classificação supervisionada. Contém informações de reserva para um City Hotel e um Resort Hotel, como e quando a reserva foi feita, número de hóspedes, quantas vagas de estacionamento foram requeridas, dentre outras informações.
Os algoritmos de regressão logística como KNN, Decision Tree, Random Forest, SVC, SGD e Ridge Classifier são usados para lidar com esse modelo de classificação supervisionado. Dentre esses algoritmos, o que teve o melhor desempenho em relação à precisão foi a Árvore de Decisão e Random Forest.

Matrícula: 201.110.029

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*


