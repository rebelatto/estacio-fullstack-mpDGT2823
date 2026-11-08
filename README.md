# DGT2823 — Tecnologias para desenv. de soluções de big data

Trabalho prático da disciplina: leitura, exploração e limpeza de um conjunto de dados com **Python** e **pandas**.

## Arquivos

```
estacio-fullstack-mpDGT2823/
├── data/
│   └── dados.csv                 # conjunto de dados do enunciado (separador ;)
├── notebooks/
│   ├── microatividades.ipynb     # microatividades 1 a 5
│   └── trabalho_pratico.ipynb    # trabalho prático: tratamento completo dos dados
├── requirements.txt              # dependências do ambiente
├── .gitignore
└── README.MD
```

O ambiente virtual (`.venv`) não é versionado: ele contém caminhos do computador onde foi criado e não funciona em outra máquina. Para reproduzir o ambiente, use o `requirements.txt` (passo a passo abaixo).

## Como ver os resultados (sem instalar nada)

Os notebooks foram salvos **já executados**. Basta clicar em `notebooks/microatividades.ipynb` ou `notebooks/trabalho_pratico.ipynb` aqui no GitHub para ver o código, as tabelas e as mensagens de erro tratadas, exatamente como saíram na execução.

## Como executar

Desenvolvido no **Jupyter Notebook**, com Python 3.14, pandas 3.1.1 e numpy 2.5.4.

1. Baixe o repositório:
   ```bash
   git clone https://github.com/rebelatto/estacio-fullstack-mpDGT2823.git
   cd estacio-fullstack-mpDGT2823
   ```
2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv .venv
   ```
   - Windows (PowerShell): `.venv\Scripts\Activate.ps1`
   - Windows (CMD): `.venv\Scripts\activate.bat`
   - Linux/macOS: `source .venv/bin/activate`
3. Instale as dependências:
   ```bash
   python -m pip install -r requirements.txt
   ```
4. Abra o Jupyter Notebook na pasta do projeto:
   ```bash
   python -m notebook
   ```
5. O navegador abre a lista de arquivos do projeto. Entre na pasta `notebooks/`, abra um dos notebooks e use **Run > Run All Cells**.

> Execute os notebooks a partir da pasta `notebooks/`: eles leem o CSV pelo caminho `../data/dados.csv`.
