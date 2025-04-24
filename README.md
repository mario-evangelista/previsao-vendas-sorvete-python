# 🍦 Previsão de Vendas de Sorvete com Machine Learning

Bem-vindo ao projeto **Gelato Mágico**, onde aplicamos conceitos de Machine Learning para prever as vendas diárias de sorvetes com base na temperatura ambiente! Este projeto foi desenvolvido como parte de um desafio prático da DIO e tem como objetivo mostrar a aplicação real de algoritmos de regressão, além de boas práticas de organização, reprodutibilidade e versionamento de modelos com MLflow.

---

## 🎯 Objetivo

Desenvolver um modelo de regressão preditiva que:

- 🔍 Treine com dados de temperatura e vendas de sorvete;
- 📈 Realize previsões com base na temperatura do dia;
- 🧠 Seja versionado e gerenciado com MLflow;
- ⚙️ Faça parte de um pipeline estruturado para garantir reprodutibilidade.

---

## 🧪 Tecnologias Utilizadas

- Python 3.10+
- Pandas & NumPy
- Matplotlib & Seaborn (visualização de dados)
- Scikit-learn (regressão)
- MLflow (gestão do ciclo de vida dos modelos)
- Jupyter Notebook
- Git & GitHub

---

## 🗂 Estrutura do Projeto

```bash
📦 previsao-vendas-sorvete
├── inputs/
│   └── dataset.csv                 # Base de dados simulada
├── notebooks/
│   └── exploracao.ipynb           # Análise exploratória e visualizações
├── src/
│   ├── train.py                   # Script para treinar o modelo
│   ├── predict.py                 # Script de previsão com entrada de temperatura
│   └── utils.py                   # Funções auxiliares
├── mlruns/                        # Diretório gerado pelo MLflow
├── README.md                      # Este arquivo :)
└── requirements.txt               # Bibliotecas utilizadas
```

---

## 📊 Exemplos de Uso

```bash
# Executar o treinamento
python src/train.py

# Prever vendas para uma temperatura específica
python src/predict.py --temperatura 32
```

---

## 📌 Insights

- Existe uma correlação linear forte entre a temperatura e as vendas.
- Modelos simples como Regressão Linear já oferecem bons resultados.
- O MLflow facilita o rastreamento de experimentos e reprodutibilidade.
- Um pipeline bem estruturado ajuda a manter a organização e facilita a manutenção do código.

---

## 📷 Prints

> _Adicione aqui capturas de tela dos gráficos, resultados, interface MLflow, etc._

---

## 💡 Possíveis Melhorias

- Adicionar novas variáveis (umidade, dia da semana, eventos locais).
- Testar outros algoritmos como Random Forest ou XGBoost.
- Implementar uma API com Flask/FastAPI para servir o modelo.
- Fazer deploy em nuvem (Heroku, AWS, Render, etc).

---

## 🚀 Contribuição

Sinta-se à vontade para abrir issues ou pull requests com sugestões e melhorias!

---

## 👨‍💻 Autor

Mário Evangelista  
📚 Bacharelado em Sistemas de Informação | Entusiasta de Machine Learning  
🔗 [LinkedIn](https://www.linkedin.com/in/marioevangelista) | [Portfólio](https://github.com/mario-evangelista)

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

Se quiser, posso também gerar um `requirements.txt` com as dependências iniciais ou preparar o esqueleto da pasta com arquivos `.py` e `.ipynb` iniciais. Quer?
