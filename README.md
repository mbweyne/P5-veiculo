![Banner do Projeto](Banner.png)

# 📊 Dashboard de Vendas de Veículos

Dashboard interativo desenvolvido com **Streamlit** para visualização de dados de anúncios de veículos nos EUA.  
O objetivo do projeto é praticar tarefas de engenharia de software, como:  
- criação de ambiente virtual Python  
- uso de Git/GitHub  
- desenvolvimento de aplicativo web com Streamlit  
- deploy em nuvem com Render  

## 🚗 Funcionalidades

- 📈 Visualização de histograma da coluna `odometer` (quilometragem dos veículos)
- 💰 Gráfico de dispersão entre `odometer` e `price` (preço)
- 📊 Dados interativos com **Plotly Express**
- 🌐 Aplicativo disponível online via **Render**

## 🛠️ Tecnologias

- Python 3.8+
- Streamlit
- Plotly Express
- Pandas

## ▶️ Como executar localmente

1. Clone o repositório:

```bash
git clone https://github.com/mbweyne/P5-veiculo.git
cd P5-veiculo
Crie e ative um ambiente virtual:

bash
Copy
Edit
python -m venv vehicles_env
.\vehicles_env\Scripts\activate    # Windows
Instale as dependências:

bash
Copy
Edit
pip install -r requirements.txt
Execute o app:

bash
Copy
Edit
streamlit run app.py
📂 Estrutura do projeto
arduino
Copy
Edit
.
├── app.py
├── vehicles_us.csv
├── requirements.txt
├── README.md
├── EDA.ipynb
└── .streamlit/
    └── config.toml
🌍 Aplicação online
Acesse o app no Render:
👉 https://p5-veiculo.onrender.com

👩‍💻 Autor(a)
Marcia Weyne
🔗 GitHub: https://github.com/mbweyne/P5-veiculo.git
🔗 LinkedIn: https://www.linkedin.com/in/marcia-weyne