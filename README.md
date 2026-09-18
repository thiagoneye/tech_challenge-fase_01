## Tech Challenge Fase 1 - Pós Tech FIAP

### Pipeline Preditivo de Churn com Modelagem Clássica e API REST

Este repositório contém a solução desenvolvida para o Tech Challenge da Fase 01 (Produtização de Modelos) da Pós-Graduação em Engenharia de Machine Learning da Pós Tech FIAP.

### Contexto

Uma operadora de telecomunicações está perdendo clientes em ritmo acelerado. O objetivo deste projeto é construir um modelo preditivo de churn para classificar os clientes com risco de cancelamento, cobrindo desde a análise exploratória (EDA) até o servimento do modelo via API REST.

### Estrutura do Repositório

A estrutura do projeto atende aos requisitos do desafio:

```text
.
├── data/          # Dados brutos e processados
├── docs/          # Documentação do projeto (ML Canvas, Model Card)
├── notebooks/     # Notebooks Jupyter para EDA e experimentação
├── src/           # Código-fonte produtivo (pré-processamento e predição)
├── tests/         # Testes automatizados
├── .gitignore
├── README.md      # Este arquivo
└── requirements.txt # Dependências do projeto
```

### Tecnologias Utilizadas

* **Linguagem:** Python
* **Machine Learning:** Scikit-Learn
* **API e Servimento:** FastAPI
* **Testes:** Pytest

### Como Configurar e Executar (Setup)

**1. Clonar o repositório:**

```bash
git clone git@github.com:thiagoneye/tech_challenge-fase_01.git
cd tech_challenge-fase_01
```

**2. Criar um ambiente virtual:**

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\\Scripts\\activate  # Windows
```

**3. Instalar as dependências:**

```bash
pip install -r requirements.txt
```

**4. Executar os testes unitários:**

```bash
pytest tests/
```

### Documentação Adicional e Entregas

* **ML Canvas e Model Card:** Detalhando métricas de negócio, performance e limitações do modelo. Disponíveis na pasta `docs/`.
* **Notebook de Exploração:** A análise exploratória de dados (EDA), construção da baseline e a comparação de desempenho encontram-se na pasta `notebooks/` .

### Vídeo de Apresentação



---

**Desenvolvido por:**

* greygateira
* Luiz Felipe
* Natalia Lourenço
* Pedro A. G. Teixeira
* Thiago Ney Evaristo Rodrigues
