   # Dashboard de Vendas de Veículos

Dashboard interativo em Streamlit para explorar dados de anúncios de vendas de veículos nos EUA.

## 🔍 Descrição

Este projeto tem como objetivo criar um aplicativo web simples utilizando **Streamlit**, com visualizações interativas construídas com **Plotly Express**. A aplicação permite ao usuário visualizar:

- Um **histograma** da quilometragem (`odometer`) dos veículos
- Um **gráfico de dispersão** entre quilometragem e preço (`price`)

O foco do projeto é a prática de engenharia de software, incluindo o uso de ambientes virtuais, versionamento com Git/GitHub, criação de dashboards com Streamlit e deploy na nuvem com Render.

## 📁 Estrutura do Projeto

.
├── README.md
├── app.py
├── vehicles_us.csv
├── requirements.txt
├── notebooks/
│ └── EDA.ipynb
└── .streamlit/
└── config.toml


## 🚀 Acesse o Aplicativo

Aplicativo online hospedado no Render:  
👉 [https://sprint-5-veiculos-6j0h.onrender.com](https://sprint-5-veiculos-6j0h.onrender.com)

## ⚙️ Como Executar Localmente

1. Clone o repositório:

git clone https://github.com/mbweyne/P5-VEICULO.git
cd nome-do-repositorio
Crie e ative um ambiente virtual:


python -m venv vehicles_env
source vehicles_env/bin/activate   # ou .\vehicles_env\Scripts\activate no Windows
Instale as dependências:


pip install -r requirements.txt
Execute o app:


streamlit run app.py
📦 Requisitos
Python 3.8+

pandas

plotly_express

streamlit

📊 Dataset
O conjunto de dados vehicles_us.csv contém informações sobre anúncios de vendas de veículos nos EUA, incluindo colunas como price, odometer, model_year, transmission, entre outras.

✍️ Autor
Marcia Weyne
GitHub | LinkedIn