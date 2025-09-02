# 🤖 IA Faculty - Machine Learning Projects

Este repositório contém projetos práticos de Machine Learning desenvolvidos como parte do curso de Inteligência Artificial. Os projetos abrangem diferentes tipos de aprendizado de máquina: supervisionado (classificação e regressão) e não supervisionado.

## 📋 Conteúdo do Projeto

### 📊 Datasets

- **`Diabetes.csv`** - Conjunto de dados para classificação de diabetes gestacional

  - Variáveis: Gravidez, Glicose, Pressão Arterial, Espessura do Tríceps, Insulina, IMC, Predisposição Genética, Idade
  - Target: Diabética (0 = Não, 1 = Sim)
  - ~10.000 registros

- **`Energia Solar.csv`** - Conjunto de dados para regressão de energia solar
  - Variáveis: Fotoperíodo, TAR (Temperatura do Ar), UR (Umidade Relativa), Vento, Radiação Extraterrestre
  - Target: Energia Solar (MJ/m²)
  - ~1.900 registros

### 📓 Notebooks

#### 1. 🔍 ML-Diabetes.ipynb - Classificação

**Objetivo:** Prever a probabilidade de desenvolvimento de diabetes gestacional em pacientes.

**Técnicas utilizadas:**

- Regressão Logística
- Support Vector Machine (SVM)
- Avaliação: Acurácia, Matriz de Confusão
- Visualizações: Gráficos de dispersão, histogramas

**Principais bibliotecas:**

- Pandas, Scikit-Learn, Matplotlib, Seaborn

#### 2. ☀️ ML-Energia-Solar.ipynb - Regressão

**Objetivo:** Prever a energia solar disponível na superfície terrestre usando dados climáticos.

**Técnicas utilizadas:**

- Regressão Linear
- Gradient Boosting Regressor
- Avaliação: MAE, MSE, RMSE, R²
- Visualizações: Gráficos de dispersão, análise de resíduos

**Principais bibliotecas:**

- Pandas, Scikit-Learn, Matplotlib

#### 3. 🎯 ML-NaoSupervisionado.ipynb - Aprendizado Não Supervisionado

**Objetivo:** Explorar técnicas de clustering e reinforcement learning.

**Técnicas utilizadas:**

- K-Means Clustering (usando dataset Iris)
- Reinforcement Learning com Gym
- Visualizações: Gráficos de clusters, centroids

**Principais bibliotecas:**

- Scikit-Learn, Matplotlib, Gym

### 📄 Documentação

- **`ATIVID_1.PDF`** - Primeira atividade prática
- **`Atividade 2.pdf`** - Segunda atividade prática

## 🚀 Como Executar

### Pré-requisitos

```bash
# Instalar as bibliotecas necessárias
pip install pandas scikit-learn matplotlib seaborn gym
```

### Execução dos Notebooks

1. Abra o Jupyter Notebook ou VS Code
2. Execute os notebooks na seguinte ordem recomendada:
   - `ML-Diabetes.ipynb` (Classificação)
   - `ML-Energia-Solar.ipynb` (Regressão)
   - `ML-NaoSupervisionado.ipynb` (Não supervisionado)

## 📊 Metodologia dos Projetos

### Fluxo Geral de Trabalho

1. **Ingestão de Dados** - Carregamento e exploração inicial
2. **Pré-processamento** - Limpeza, normalização e seleção de features
3. **Separação dos Dados** - Train/Test split (80/20)
4. **Treinamento do Modelo** - Aplicação de algoritmos de ML
5. **Validação** - Métricas estatísticas e gráficos
6. **Avaliação Final** - Comparação de modelos

### Boas Práticas Implementadas

- ✅ Separação adequada de dados de treino/teste
- ✅ Normalização/padronização quando necessária
- ✅ Validação cruzada
- ✅ Análise de resíduos
- ✅ Visualizações informativas
- ✅ Comparação de múltiplos modelos

## 🎯 Objetivos de Aprendizado

- Compreender os diferentes tipos de aprendizado de máquina
- Aplicar técnicas de pré-processamento de dados
- Implementar e comparar diferentes algoritmos
- Interpretar métricas de avaliação de modelos
- Criar visualizações efetivas para análise de dados
- Seguir boas práticas de desenvolvimento em ML

## 📈 Resultados Esperados

### Classificação (Diabetes)

- Acurácia > 75%
- Análise da matriz de confusão
- Identificação de features mais importantes

### Regressão (Energia Solar)

- R² > 0.8
- RMSE minimizado
- Análise de resíduos bem distribuídos

### Clustering

- Visualização clara dos clusters
- Interpretação dos grupos formados
- Aplicação prática do K-Means

## 🛠️ Tecnologias Utilizadas

- **Python** - Linguagem principal
- **Jupyter Notebook** - Ambiente de desenvolvimento
- **Pandas** - Manipulação de dados
- **Scikit-Learn** - Algoritmos de ML
- **Matplotlib/Seaborn** - Visualizações
- **Gym** - Reinforcement Learning

## 📝 Estrutura do Projeto

```
IA-faculty/
├── 📊 Datasets/
│   ├── Diabetes.csv
│   └── Energia Solar.csv
├── 📓 Notebooks/
│   ├── ML-Diabetes.ipynb
│   ├── ML-Energia-Solar.ipynb
│   └── ML-NaoSupervisionado.ipynb
├── 📄 Documentação/
│   ├── ATIVID_1.PDF
│   └── Atividade 2.pdf
└── README.md
```

## 🤝 Contribuição

Este é um projeto educacional. Sugestões de melhorias são bem-vindas:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto é parte de um curso educacional e está disponível sob a licença MIT.

## 👨‍💻 Autor

**Renan Rodrigues** - _Desenvolvimento dos projetos_

---

⭐ **Nota:** Este projeto serve como portfólio de aprendizado em Machine Learning e demonstra a aplicação prática de conceitos teóricos em problemas reais.
