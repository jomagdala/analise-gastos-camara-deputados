# 📊 Análise Exploratória: Gastos da Cota Parlamentar (Câmara dos Deputados)

Análise exploratória dos gastos dos deputados federais brasileiros com a **Cota para o Exercício da Atividade Parlamentar (CEAP)**, cobrindo a 57ª Legislatura (2023–2026) — o mandato que antecede as Eleições Gerais de 2026.

## 🎯 Objetivo

Entender como o dinheiro público destinado ao exercício do mandato parlamentar foi utilizado: quais categorias de despesa mais pesam, como o gasto varia por partido e estado, e quais padrões (ou outliers) chamam atenção.

## 🗂️ Fonte dos dados

- **Câmara dos Deputados — Portal de Dados Abertos**
  Dados públicos, atualizados diariamente, disponíveis em:
  https://www2.camara.leg.br/transparencia/cota-para-exercicio-da-atividade-parlamentar/dados-abertos-cota-parlamentar

> Dados de deputados estaduais não foram incluídos porque não há uma base nacional unificada — cada Assembleia Legislativa publica seus próprios dados de forma independente.

## 🛠️ Tecnologias

- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook

## 📁 Estrutura

```
.
├── eda_gastos_camara_deputados.ipynb # Notebook principal com a análise
├── requirements.txt # Dependências do projeto
└── README.md
```

## ▶️ Como rodar

```bash
pip install -r requirements.txt
jupyter notebook eda_gastos_camara_deputados.ipynb
```

O notebook baixa os dados diretamente do site da Câmara — é necessário acesso à internet na primeira execução.

## 📌 Principais perguntas respondidas

1. Qual foi o gasto total por ano na legislatura atual?
2. Quais categorias de despesa mais pesam no orçamento?
3. Como o gasto se distribui entre partidos e estados?
4. Quem são os deputados com maior gasto?
5. Existe sazonalidade ou outliers relevantes?

## 🔭 Próximos passos

- Gasto médio por deputado (normalizado por partido/UF)
- Cruzamento com resultados eleitorais de 2022
- Inclusão de dados de produtividade legislativa (proposições, presença em votações)

