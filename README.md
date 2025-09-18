#  NLP: Análise de Sentimentos em Reviews de E-commerce

Este projeto utiliza técnicas de Processamento de Linguagem Natural (NLP) para analisar e classificar o sentimento de reviews de produtos de um dataset de e-commerce brasileiro.

## Objetivo

O objetivo é construir um modelo de Machine Learning capaz de classificar automaticamente um texto de avaliação de produto como **positivo** ou **negativo**, permitindo que uma empresa possa, em escala:
* Entender a satisfação geral dos clientes.
* Identificar rapidamente produtos com problemas.
* Priorizar o atendimento ao cliente com base no sentimento da avaliação.

## Processo

O projeto seguiu as seguintes etapas:
1.  **Limpeza e Pré-processamento dos Dados:** Remoção de stopwords, pontuação e aplicação de técnicas como stemming ou lematização.
2.  **Vetorização:** Transformação do texto limpo em vetores numéricos utilizando a técnica TF-IDF.
3.  **Treinamento do Modelo:** Foram testados diferentes algoritmos de classificação, com o [Nome do Melhor Modelo, ex: Logistic Regression, Naive Bayes] apresentando o melhor resultado.
4.  **Avaliação:** O modelo final foi avaliado com base na sua acurácia, precisão e recall.

## Resultados

O modelo final alcançou uma **acurácia de XX%** na classificação de novos reviews, demonstrando sua eficácia em distinguir entre avaliações positivas e negativas.

## 🛠️ Tecnologias Utilizadas
* Python
* Pandas & NumPy
* Scikit-learn
* NLTK (ou outra biblioteca de NLP que você usou, como spaCy)
* Matplotlib & Seaborn
* Jupyter Notebook