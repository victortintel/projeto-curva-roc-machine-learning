# Projeto - CURVA ROC / AUC - Victor Tintel<br>
## 📌 Descrição do Projeto<br>
Este projeto tem como objetivo demonstrar, de forma prática e descomplicada, como utilizar a Curva ROC (Receiver Operating Characteristic) e a métrica AUC (Area Under the Curve) para avaliar a performance de modelos de Machine Learning em problemas de classificação.<br>

Muitas vezes, essas métricas são apresentadas de maneira complexa, mas aqui vamos simplificar seu entendimento e aplicação, mostrando como interpretá-las e utilizá-las para comparar modelos e tomar decisões mais assertivas.<br>

## 📊 O que é a Curva ROC e a Métrica AUC?<br><br>
### 📈 Curva ROC:
A Curva ROC é uma representação gráfica que ilustra o desempenho de um modelo de classificação em diferentes limiares de decisão. Ela plota:<br>

- Taxa de Verdadeiros Positivos (True Positive Rate - TPR / Recall) no eixo Y.

- Taxa de Falsos Positivos (False Positive Rate - FPR) no eixo X.

- Quanto mais a curva se aproximar do canto superior esquerdo do gráfico, melhor será o desempenho do modelo.

## 🔢 Métrica AUC (Area Under the Curve):<br>
- A AUC mede a área sob a Curva ROC e fornece um valor único que resume a capacidade do modelo de distinguir entre classes:

- AUC = 1.0: Modelo perfeito (classificação ideal).

- AUC = 0.5: Modelo equivalente a um chute aleatório.

- AUC entre 0.5 e 1.0: Quanto maior, melhor a discriminação entre classes.

## 🛠️ Como o Projeto Foi Desenvolvido?: <br>
### Neste projeto, utilizamos:

- Python e bibliotecas como scikit-learn, matplotlib e seaborn.

- Dados de classificação binária para exemplificar.

- Comparação de diferentes modelos (Regressão Logística, Random Forest, SVM, etc.).

- Geração da Curva ROC e cálculo da AUC para cada modelo.
