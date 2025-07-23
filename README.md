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
- PyTorch para ML puro

## Setup rápido

```bash
# Clone o repositório
git clone https://github.com/seu_usuario/ds_urbanchaos_sp.git
cd ds_urbanchaos_sp

# Crie o ambiente e instale as dependências
pip install -r requirements.txt
```

## Autor

Caio Marques  
Especialista em Qualidade de Software & Data Science
