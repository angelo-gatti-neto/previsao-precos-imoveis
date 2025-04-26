# 🏠 Projeto: Previsão de Preços de Imóveis

## 📋 Descrição
Este projeto tem como objetivo prever o preço de venda de imóveis utilizando dados do conjunto **Ames Housing Dataset**. Aplicamos técnicas de regressão para construir e avaliar modelos preditivos.

## 📚 Etapas do Projeto

### 1. 📥 Importação dos Dados
Carregamos o conjunto de dados que contém diversas informações sobre características de imóveis.

### 2. 🧹 Limpeza e Tratamento dos Dados
- Remoção de valores ausentes.
- Ajustes em variáveis categóricas e numéricas.
- Separação entre variáveis de entrada (X) e variável alvo (y).

### 3. 📊 Análise Exploratória
- Entendimento da distribuição das variáveis.
- Análise de correlação entre atributos.

### 4. ✂️ Divisão dos Dados
Separarão dos dados em conjuntos de treino e teste (80% treino, 20% teste).

### 5. ⚙️ Treinamento dos Modelos
Modelos aplicados:
- **Regressão Linear**
- **Random Forest Regressor**

### 6. 🧪 Avaliação dos Modelos
Métricas usadas:
- **MAE** (Erro Absoluto Médio)
- **MSE** (Erro Quadrático Médio)
- **R2** (Coeficiente de Determinação)

Resultados:

**Regressão Linear:**
- **MAE**: 1.443.976.037,32
- **MSE**: 1.21919026290776e+21
- **R2**: -152065229095.76

**Random Forest:**
- **MAE**: 15.893,30
- **MSE**: 691.499.897,60
- **R2**: 0.9137

✅ O modelo **Random Forest** apresentou desempenho muito superior, sendo escolhido como modelo final.

### 7. 📈 Análise de Importância das Variáveis
Foram geradas análises sobre quais variáveis mais impactam o preço final dos imóveis.

---

## 📂 Estrutura de Arquivos

- `notebook_previsao_precos.ipynb` → Análise completa em Jupyter Notebook.
- `requirements.txt` → Bibliotecas necessárias para executar o projeto.

---

## 🛠️ Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

---

## 👨‍💻 Autor

**Ângelo Gatti Neto**

- [LinkedIn](https://www.linkedin.com/in/angelo-gatti-neto/)
- [GitHub](https://github.com/angelo-gatti-neto)

---

# 🚀 Obrigado por acompanhar!



```python

```
