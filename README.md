# 📊 Dashboard de Vendas

## 📝 Descrição

Este projeto é um **dashboard interativo de vendas** desenvolvido com [Streamlit](https://streamlit.io/), trazendo visualizações dinâmicas criadas com [Plotly](https://plotly.com/python/). Ele permite explorar dados de vendas por 🌍 região, 📅 ano, 🧑‍💼 vendedores e categorias de 🛒 produtos, tornando as análises intuitivas e úteis para tomadas de decisão.

### Funcionalidades principais:
- Exibição de **💰 receita total e mensal**;
- Contagem de **#️⃣ quantidade de vendas**;
- Análises detalhadas por 🌍 região, 🗺️ estados, 🛒 categorias e 🧑‍💼 vendedores;
- Visualizações gráficas como 🗺️ mapas, 📊 gráficos de barras e 📉 gráficos de linha.

---

## ⚙️ Funcionalidades

### 🎛️ Filtros Dinâmicos
- 🌍 Filtrar por região (ex.: 🇧🇷 Brasil, Nordeste, Sul).
- Selecionar 📅 anos específicos ou todos os disponíveis.
- Escolher 🧑‍💼 vendedores específicos para análise.

### 📊 Análises de Dados
- Comparação de 💰 receita e #️⃣ quantidade de vendas por:
  - 🗺️ Estado;
  - 🌍 Região;
  - 🛒 Categoria.
- Tendências de 💰 receita e vendas mensais.
- 🏆 Identificação dos 🧑‍💼 vendedores com maior 💰 receita ou #️⃣ vendas.

### 📉 Visualizações Gráficas
- 🗺️ Mapas interativos destacando vendas por 🗺️ estado.
- 📈 Gráficos de linha ilustrando tendências mensais.
- 📊 Gráficos de barras para rankings de 🛒 categorias, 🗺️ estados e 🧑‍💼 vendedores.

---

## 🛠️ Tecnologias Utilizadas

- **💻 Linguagem**: 🐍 Python
- **📚 Bibliotecas**:
  - [Streamlit](https://streamlit.io/): criação da interface 🌐 web.
  - [Pandas](https://pandas.pydata.org/): manipulação e análise de dados.
  - [Plotly](https://plotly.com/python/): visualização interativa de dados.
  - [Requests](https://docs.python-requests.org/): consumo de dados via API.

---

## ▶️ Como Executar

1. **📥 Clonar o Repositório**:

   ```bash
   git clone <url-do-repositorio>
   cd <nome-do-repositorio>
   ```

2. **⚙️ Criar um Ambiente Virtual (opcional)**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate   # Windows
   ```

3. **📦 Instalar as Dependências**:

   ```bash
   pip install -r requirements.txt
   ```

4. **🚀 Executar o Aplicativo Streamlit**:

   ```bash
   streamlit run app.py
   ```

5. **🌐 Abrir o Navegador**:

   O aplicativo estará disponível no endereço [http://localhost:8501](http://localhost:8501).

---

## 🗂️ Estrutura do Código

- **`app.py`**: arquivo principal do aplicativo contendo:
  - 🎛️ Filtros na barra lateral.
  - 📊 Processamento e formatação de dados.
  - 📉 Criação de gráficos interativos com Plotly.
  - 🗂️ Organização de abas para diferentes visualizações.
- **`requirements.txt`**: lista de dependências do projeto.

---

## 🖼️ Exemplos de Visualizações

- **🗺️ Mapa de Receita por Estado**:
- **📈 Receita Mensal**:
- **🏆 Top Vendedores**:

---

## 📁 Dados

Os dados são obtidos por meio de uma API externa:

- 🌐 URL da API: `https://labdados.com/produtos`
- 🔧 Parâmetros:
  - `regiao`: 🌍 região desejada.
  - `ano`: 📅 ano específico (opcional).

---

## 🌟 Melhorias Futuras

- ➕ Implementar análise preditiva de vendas.
- 🔗 Integrar com outras fontes de dados.
- 🎨 Ampliar a personalização das visualizações gráficas.

---

## 🙌 Contribuições

Contribuições são muito bem-vindas! Para colaborar:

1. Faça um 🍴 fork do repositório.
2. Crie uma 🛠️ branch para sua 🆕 feature ou correção.
3. Envie um 🤝 pull request.

---

Projeto desenvolvido para fins educacionais no curso de desenvolvimento de dashboards com Streamlit. 🚀

