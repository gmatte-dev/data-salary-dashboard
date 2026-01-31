<div align="center">

# Dashboard de Análise de Salários na Área de Dados

### Visualização interativa de dados salariais para profissionais de Data Science, Analytics e Engenharia de Dados

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://data-salary-dashboard-imersaoalura.streamlit.app/)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-1.44-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.2-150458?style=flat&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-5.24-3F4F75?style=flat&logo=plotly&logoColor=white)

[**Acessar Dashboard**](https://data-salary-dashboard-imersaoalura.streamlit.app/)

</div>

---

## Sobre o Projeto

Este projeto foi desenvolvido durante a **Imersão Dados com Python II da Alura 2026**, uma experiência intensiva de aprendizado focada em análise de dados e visualização interativa.

O dashboard oferece uma análise completa do mercado de trabalho na área de dados, permitindo explorar salários por cargo, senioridade, tipo de contrato e localização geográfica. Ideal para profissionais que desejam entender o cenário salarial global e tomar decisões de carreira mais informadas.

---

## Funcionalidades

- **Filtros Interativos** - Refine análises por ano, senioridade, tipo de contrato e tamanho da empresa
- **KPIs em Tempo Real** - Visualize métricas como salário médio, máximo e cargo mais frequente
- **Top 10 Cargos** - Ranking dos cargos mais bem remunerados na área de dados
- **Distribuição Salarial** - Histograma interativo mostrando a dispersão de salários
- **Análise de Modalidade** - Proporção entre trabalho remoto, híbrido e presencial
- **Mapa Global** - Visualização geográfica do salário médio de Data Scientists por país
- **Tabela Detalhada** - Acesso aos dados brutos filtrados para análise aprofundada

---

## Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| **Python 3.10+** | Linguagem principal do projeto |
| **Streamlit** | Framework para criação de aplicações web interativas |
| **Pandas** | Manipulação e análise de dados |
| **Plotly Express** | Visualizações interativas e responsivas |

---

## Como Executar Localmente

```bash
# Clone o repositório
git clone https://github.com/gmatte-dev/data-salary-dashboard.git

# Acesse o diretório
cd data-salary-dashboard

# Instale as dependências
pip install -r requirements.txt

# Execute a aplicação
streamlit run app.py
```

---

## Estrutura do Projeto

```
data-salary-dashboard/
├── app.py                      # Aplicação principal do Streamlit
├── dados-imersao-final.csv     # Dataset com dados salariais
├── requirements.txt            # Dependências do projeto
└── README.md                   # Documentação
```

---

## Dataset

O dataset contém informações salariais de profissionais da área de dados, incluindo:

| Campo | Descrição |
|-------|-----------|
| `ano` | Ano de referência do salário |
| `senioridade` | Nível do profissional (junior, pleno, senior, executivo) |
| `contrato` | Tipo de contrato (integral, parcial, freelance) |
| `cargo` | Título do cargo |
| `usd` | Salário anual em dólares americanos |
| `residencia` | País de residência do profissional |
| `remoto` | Modalidade de trabalho (remoto, híbrido, presencial) |
| `tamanho_empresa` | Porte da empresa (pequena, média, grande) |

---

## Preview

<div align="center">

**[Acesse o Dashboard ao Vivo](https://data-salary-dashboard-imersaoalura.streamlit.app/)**

</div>

---

## Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados conceitos de:

- Análise exploratória de dados com Pandas
- Criação de visualizações interativas com Plotly
- Desenvolvimento de aplicações web com Streamlit
- Boas práticas de organização de código e documentação
- Deploy de aplicações na Streamlit Cloud

---

## Autor

Desenvolvido por **Gabriel Matte**

[![GitHub](https://img.shields.io/badge/GitHub-gmatte--dev-181717?style=flat&logo=github)](https://github.com/gmatte-dev)

---

<div align="center">

**Projeto desenvolvido durante a Imersão Dados com Python II - Alura 2026**

</div>
