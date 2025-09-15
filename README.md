# Fake News Classifier - Machine Learning

## Descrição
Este repositório contém todo o pipeline de Machine Learning para o projeto **Fake News Classifier**. Aqui desenvolvemos, treinamos e avaliamos um modelo capaz de classificar notícias como **verdadeiras** ou **falsas**, usando dados públicos. O modelo será consumido por uma API separada e por um frontend web.

---

## Estrutura do Repositório
```
├── datasets/ # Datasets utilizados (Fake.csv, True.csv)
├── models/ # Modelos treinados e vetorizadores (joblib)
├── main.ipynb # código que cria o modelo
├── requirements.txt # requisições do código
└── README.md
```

## Tecnologias e Bibliotecas
- Python 3.x
- pandas
- scikit-learn (Logistic Regression, TfidfVectorizer)
- joblib (para salvar modelos)
- Jupyter Notebook (notebooks interativos)

## Como usar

1. **Instalar dependências**:

```bash 
  pip install -r requirements.txt
```

2. **Rodar o código**:

```bash
jupyter notebook main.ipynb
```

## Métricas do Modelo
Após treinamento, o modelo atingiu:
- Accuracy: 99%
- Precision (Fake/True): 0.99 / 0.99
- Recall (Fake/True): 0.99 / 0.99
- F1-score (Fake/True): 0.99 / 0.99

Esses resultados indicam que o modelo é altamente confiável para esse dataset.

Próximos Passos

Integração do modelo com a API FastAPI (repositório separado)

Criação de frontend que consome a API (repositório separado)

Deploy do modelo na AWS para consumo online

## Referências
- [Dataset de Fake New](https://www.kaggle.com/datasets)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [TF-IDF Tutorial](https://scikit-learn.org/stable/modules/feature_extraction.html#text-feature-extraction)

