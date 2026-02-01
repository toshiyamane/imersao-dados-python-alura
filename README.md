"# 📊 Dashboard de Análise de Salários na Área de Dados

Um dashboard interativo que permite explorar e analisar dados salariais na área de dados, com visualizações dinâmicas e filtros avançados.

## 🎯 Comandos iniciais
Criar o ambiente virtual:
    python3 -m venv .venv
Ativar o ambiente virtual em Windows:
    .venv\Scripts\Activate
Ativar o ambiente virtual em MAC/LINUX:
    source .venv/bin/activate
Criar um arquivo chamado requirements.txt e adicionar os pacotes necessários
    pandas==2.2.3
    streamlit==1.44.1
    plotly==5.24.1
Instalar as bibliotecas necessárias
    pip install -r requirements.txt

streamlit run app.py
## 🎯 Funcionalidades

- **Filtros Interativos**: Filtre dados por:
  - Ano
  - Senioridade
  - Tipo de Contrato
  - Tamanho da Empresa

- **Métricas Principais (KPIs)**:
  - Salário médio anual
  - Salário máximo
  - Total de registros
  - Cargo mais frequente

- **Visualizações**:
  - Top 10 cargos por salário médio (gráfico de barras)
  - Distribuição de salários (histograma)
  - Proporção de tipos de trabalho (gráfico de pizza)
  - Salário médio de Data Scientists por país (mapa coroplético)

- **Tabela de Dados**: Visualize todos os dados filtrados em formato tabular

## 🛠️ Tecnologias

- **Streamlit**: Framework para construção de aplicações web de dados
- **Pandas**: Manipulação e análise de dados
- **Plotly Express**: Criação de visualizações interativas
- **Python 3.x**

## 📋 Requisitos

- Python 3.8+
- pip (gerenciador de pacotes Python)

## 🚀 Como Executar

### 1. Clone o repositório
```bash
git clone <seu-repositorio>
cd imersao_python
```

### 2. Instale as dependências
```bash
pip install -r requirements.txt
```

### 3. Execute o dashboard
```bash
streamlit run app.py
```

O dashboard abrirá automaticamente em seu navegador padrão (geralmente em `http://localhost:8501`)

## 📁 Estrutura do Projeto

```
imersao_python/
├── app.py                 # Arquivo principal do dashboard
├── requirements.txt       # Dependências do projeto
└── README.md             # Este arquivo
```

## 📊 Dados

Os dados são carregados automaticamente de um repositório remoto do GitHub e contêm informações sobre salários na área de dados, incluindo:
- Ano de referência
- Cargo profissional
- Senioridade
- Tipo de contrato
- Tamanho da empresa
- Tipo de trabalho (presencial, remoto, híbrido)
- País/região
- Salário em USD

## 💡 Como Usar

1. Abra o dashboard após executar o comando acima
2. Use os filtros na barra lateral esquerda para refinar os dados
3. As métricas e gráficos serão atualizados automaticamente
4. Explore a tabela de dados detalhados na parte inferior
5. Posicione o mouse sobre os gráficos para interagir com as visualizações

## 🔗 Fonte dos Dados

Os dados são obtidos de: https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv

## 📝 Notas

- Os dados são carregados dinamicamente, portanto uma conexão com a internet é necessária
- Os filtros funcionam em conjunto (AND lógico)
- Todos os valores de salário estão em USD (dólares americanos)

## 🤝 Contribuições

Sinta-se livre para fazer fork deste projeto, criar uma branch para sua feature e enviar um pull request.

## 📄 Licença

Este projeto é de código aberto e disponível sob a licença MIT.

---

**Desenvolvido durante a Imersão Python** 🎓" 
