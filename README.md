# ds_urbanchaos_sp

Análise exploratória e modelagem com Machine Learning aplicada a dados urbanos da cidade de São Paulo.
Este projeto investiga padrões de criminalidade, inundações e comportamentos sazonais com suporte de geodados.
O objetivo deste estudo é correlacionar os incidentes mapeados para auxiliar na avaliação do valor de imóveis

## Objetivos

- Realizar EDA sobre dados de criminalidade e inundações em SP
- Estudar sazonalidades baseadas em cultura, clima e histórico
- Aplicar técnicas de Machine Learning com PyTorch
- Utilizar GeoPandas para relacionar distância entre eventos e regiões

## Estrutura de Diretórios

```
ds_urbanchaos_sp/
├── data/             # Dados brutos, tratados e externos
├── notebooks/        # Notebooks de EDA e estudos
├── src/              # Código-fonte do projeto
├── tests/            # Testes automatizados
├── experiments/      # Resultados, modelos e relatórios
├── scripts/          # Entrypoints e automações
├── requirements.txt  # Bibliotecas usadas
└── README.md         # Documentação do projeto
```

## Tecnologias

- Python 3.10+
- Pandas, GeoPandas, Matplotlib, Seaborn
- PyTorch

## Setup rápido + Jupyter

```bash
# Clone o repositório
git clone https://github.com/seu_usuario/ds_urbanchaos_sp.git
cd ds_urbanchaos_sp

# 1. Crie e ative o ambiente virtual
python -m venv .venv
source .venv/bin/activate        # Linux/macOS
.venv\Scripts\activate           # Windows

# 2. Crie o ambiente e instale as dependências
pip install -r requirements.txt

# 3. Instale o kernel jupy
pip install jupyterlab ipykernel

# 4. Registre o venv como kernel do Jupyter
python -m ipykernel install --user --name=ds_urbanchaos_sp --display-name="Python (ds_urbanchaos_sp)"

# 5. Rode o JupyterLab
jupyter lab
```

## Autor

Caio Marques  
Especialista em Qualidade de Software & Data Science
