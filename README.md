# 📚 BookWorms — Dashboard de Livros

Dashboard interativo em **Streamlit** para explorar os 100 livros em alta e as avaliações de clientes.

## ✨ Funcionalidades

- **Home:** tabela dos 100 livros mais populares com filtro de preço na barra lateral e gráficos de livros por ano de publicação e distribuição de preços.
- **Book Reviews:** seleção de um livro para ver preço, nota, ano e gênero, além das avaliações dos clientes.

## 🛠️ Tecnologias

- Python 3.9+
- [Streamlit](https://streamlit.io/)
- [pandas](https://pandas.pydata.org/)
- [Plotly Express](https://plotly.com/python/plotly-express/)
- Pillow

## 🚀 Como executar

```bash
git clone https://github.com/pedrobernardone/web-dash.git
cd web-dash

python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

pip install streamlit pandas plotly pillow
streamlit run app.py
```

A aplicação abrirá no navegador (por padrão em `http://localhost:8501`).

## 📁 Estrutura

```text
├── app.py                # Navegação e página inicial
├── pages/
│   └── book_reviews.py   # Página de avaliações
├── datasets/             # Arquivos CSV utilizados
└── assets/               # Favicon
```

## 📊 Dados

Os arquivos em `datasets/` reúnem uma lista dos 100 livros em alta e avaliações de clientes, usados aqui apenas para fins educacionais e de demonstração. Os direitos sobre os dados pertencem às suas respectivas fontes.

## 👤 Autor

**Pedro Bernardone** — [@pedrobernardone](https://github.com/pedrobernardone)
