# Projeto de Modelagem dos Preços do Açúcar Cristal e Etanol Hidratado

# **Autor**
✍️ Rafael Vasconcelos Valadares
✉️ [rafaelvvaladares@hotmail.com]

# **Visão Geral**
Este projeto visa fornecer previsões precisas e exatas dos preços nacionais do açúcar cristal e do etanol hidratado. As previsões ajudam na tomada de decisão quanto à assinatura de contratos e investimentos.

# **Problema Proposto**
O objetivo é fornecer previsões precisas e exatas dos preços nacionais do açúcar cristal e do etanol hidratado. Essas previsões são essenciais para facilitar a tomada de decisão em relação à assinatura de contratos e investimentos.

# **Atributos Utilizados**
📌 **Fatores da cadeia produtiva do açúcar:**
1. Câmbio dolar, euro e libra
2. Preço açúcar internacional

📌 **Macro fatores nacionais e internacionais:**
1. Preço do petróleo
2. Balança comercial (importação/exportação)
3. PIB nacional, ipca, igpm, desemprego, etc
4. Políticas do setor
5. Preços produtos substitutos
6. Outros

📌 **Fatores idiossincráticos:**
1. Área plantada
2. TCH (Tonelada de Cana por Hectare)
3. Volume produzido
4. Açúcar e etanols produzido
5. ATR médio (Açúcares Totais Recuperáveis)
6. Produção de etanol anidro e hidratado
![image](https://github.com/RafaelVV/ML_PrecosAcucarEtanol/assets/10815345/2087b41a-3a3e-4345-bf51-60b62e898cb7)

# **Pré-processamento dos dados:**
![image](https://github.com/RafaelVV/ML_PrecosAcucarEtanol/assets/10815345/5dfd2a67-4bc8-4f05-a3a6-2031f8bd20c7)


# **Metodologia de Modelagem**
A metodologia adotada segue princípios das metodologias Canvas ML, KDD e CRISP-DM.
![image](https://github.com/RafaelVV/ML_PrecosAcucarEtanol/assets/10815345/56f5789a-f0c2-4b30-ba06-9f9fb6085c32)

# **Workflow de Modelagem**

📌 **Divisão dos Dados:**
- Dados de treino (80%)
- Dados de teste (20%)

📌 **Modelos de Regressão Utilizados:**
1. 🌳 Random Forest
2. 🔍 Support Vector Machines
3. 🚀 AdaBoost
4. 🌟 GradientBoost
5. ⚡ XGBoost
6. 💡 LightGBM
7. 🤖 Redes Neurais Artificiais

# **Otimização de Hiperparâmetros:**

Utilização de GridSearchCV com validação cruzada para otimização dos hiperparâmetros.

# **Resultados do Projeto**

🏅 O ensemble (RF+LGBM+XGB) de modelos apresentou uma performance satisfatória na predição dos preços, com os seguintes resultados:

📌 **Erro Médio Absoluto Percentual (MAPE):**

- Açúcar cristal: 1.4%
- Etanol hidratado: 1.64%

📌 **Precisão (R²):**

- Açúcar cristal: 1.00
- Etanol hidratado: 0.99

# **Conclusão**

- Este projeto demonstra uma abordagem robusta para a previsão dos preços do açúcar cristal e etanol hidratado utilizando um conjunto diversificado de modelos de regressão e técnicas de otimização. A metodologia proposta pode ser adaptada e aplicada a outros contextos de previsão de preços em mercados agrícolas ou energéticos.


