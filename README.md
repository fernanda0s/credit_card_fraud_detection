# Projeto: Detecção de Anomalias em Transações em Python

### Credit Card Fraud Detection
Problema: É importante que as empresas de cartão de crédito sejam capazes de reconhecer transações fraudulentas de cartão de crédito para que os clientes não sejam cobrados por itens que não compraram. Fraude é qualquer ação deliberada de enganar ou ludibriar em benefício próprio (ex.: uso indevido de cartão de crédito).
Solução: A análise de dados ajuda a combater fraudes ao identificar comportamentos atípicos (outliers) em grandes volumes de transações. Por meio de técnicas estatísticas e de aprendizado de máquina, é possível detectar padrões suspeitos e alertar sobre possíveis fraudes de forma mais rápida e precisa, reduzindo perdas financeiras e melhorando a segurança.

Disponível em: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

O conjunto de dados contém transações feitas por cartões de crédito em setembro de 2013 por titulares de cartão europeus. Este conjunto de dados apresenta transações que ocorreram em dois dias, onde temos 492 fraudes de 284.807 transações. O conjunto de dados é altamente desbalanceado, a classe positiva (fraudes) é responsável por 0,172% de todas as transações.

## Importação das bibliotecas
<img width="411" height="133" alt="image" src="https://github.com/user-attachments/assets/6cfb9163-966e-4168-b060-418ab16199c8" />

## Carregamento do dataset
<img width="411" height="131" alt="image" src="https://github.com/user-attachments/assets/0ffea51e-45f9-4bed-92f1-b065ae617a70" />
<img width="411" height="61" alt="image" src="https://github.com/user-attachments/assets/f8eb4337-882f-42fa-a11d-4025c9b67b19" />
<img width="434" height="175" alt="image" src="https://github.com/user-attachments/assets/1a106f1d-ebeb-4c65-a3d3-812001ffb417" />
<img width="421" height="26" alt="image" src="https://github.com/user-attachments/assets/f2ca500d-3fcf-40d2-8750-fd7568719c56" />

<class 'pandas.core.frame.DataFrame'>
RangeIndex: 284807 entries, 0 to 284806
Data columns (total 31 columns):
 #   Column  Non-Null Count   Dtype  
---  ------  --------------   -----  
 0   Time    284807 non-null  float64
 1   V1      284807 non-null  float64
 2   V2      284807 non-null  float64
 3   V3      284807 non-null  float64
 4   V4      284807 non-null  float64
 5   V5      284807 non-null  float64
 6   V6      284807 non-null  float64
 7   V7      284807 non-null  float64
 8   V8      284807 non-null  float64
 9   V9      284807 non-null  float64
 10  V10     284807 non-null  float64
 11  V11     284807 non-null  float64
 12  V12     284807 non-null  float64
 13  V13     284807 non-null  float64
 14  V14     284807 non-null  float64
 15  V15     284807 non-null  float64
 16  V16     284807 non-null  float64
 17  V17     284807 non-null  float64
 18  V18     284807 non-null  float64
 19  V19     284807 non-null  float64
 20  V20     284807 non-null  float64
 21  V21     284807 non-null  float64
 22  V22     284807 non-null  float64
 23  V23     284807 non-null  float64
 24  V24     284807 non-null  float64
 25  V25     284807 non-null  float64
 26  V26     284807 non-null  float64
 27  V27     284807 non-null  float64
 28  V28     284807 non-null  float64
 29  Amount  284807 non-null  float64
 30  Class   284807 non-null  int64  
dtypes: float64(30), int64(1)
memory usage: 67.4 MB

<img width="417" height="31" alt="image" src="https://github.com/user-attachments/assets/4c51a506-c060-49a3-a5cf-a35617ba820b" />



##

