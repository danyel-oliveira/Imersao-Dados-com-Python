# 📊 Imersão Dados com Python

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Alura](https://img.shields.io/badge/Alura-Imersão-ff6900.svg)](https://www.alura.com.br/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **Análise completa de dados salariais de profissionais de tecnologia utilizando Python e Pandas**
> 
> 🎯 **Projeto desenvolvido durante a Imersão Dados da Alura** | 🚀 **Demonstrando skills em Data Science para recrutadores**

Este repositório documenta minha jornada durante a **Imersão em Análise de Dados com Python da Alura**, onde explorei um dataset real de salários de profissionais da área de dados, aplicando técnicas fundamentais de data science com foco no mercado de trabalho atual.

## 🎯 Objetivo do Projeto

**Para Recrutadores**: Este projeto demonstra competências técnicas essenciais em Data Science, evidenciando capacidade de trabalhar com dados reais do mercado de tecnologia.

**Skills Demonstradas**:
- 🐍 **Python**: Programação orientada a dados
- 📊 **Pandas**: Manipulação avançada de DataFrames
- 🧹 **Data Cleaning**: Tratamento profissional de dados inconsistentes
- 📈 **EDA**: Análise exploratória estruturada
- 📊 **Data Visualization**: Comunicação visual de insights
- 🎓 **Continuous Learning**: Participação ativa na Imersão Dados Alura

## 📊 Dataset Analisado

**Fonte**: [Data Jobs Salary Dataset](https://raw.githubusercontent.com/guilhermeonrails/data-jobs/refs/heads/main/salaries.csv)

**Características do Dataset**:
- **Período**: Dados de salários por ano
- **Escopo**: Profissionais da área de dados globalmente
- **Variáveis**: 11 colunas incluindo cargo, senioridade, tipo de contrato, localização e salários

**Colunas principais**:
- `ano`: Ano de referência
- `senioridade`: Nível de experiência (Júnior, Pleno, Senior, Executivo)
- `contrato`: Tipo de contrato (Integral, Parcial, Freelance, Contrato)
- `cargo`: Título do cargo
- `salario`/`usd`: Valores salariais
- `remoto`: Modalidade de trabalho (Presencial, Híbrido, Remoto)
- `tamanho_empresa`: Porte da empresa (Pequena, Média, Grande)

## 🚀 Estrutura do Projeto

```
📁 Imersao-Dados-com-Python/
├── 📄 Imersão_Dados_com_Python.ipynb    # Notebook principal
├── 📄 README.md                         # Este arquivo
└── 📄 requirements.txt                  # Dependências (recomendado)
```

## 📚 Conteúdo das Aulas

### 📖 Aula 1 - Fundamentos da Análise com Pandas

**Objetivos**: Primeiros passos com manipulação de dados

**Principais conceitos abordados**:
- ✅ Carregamento de dados externos via URL
- ✅ Exploração inicial do DataFrame (`head()`, `info()`, `describe()`)
- ✅ Renomeação estratégica de colunas para português
- ✅ Análise de categorias e valores únicos
- ✅ Mapeamento e padronização de valores categóricos

**Destaque técnico**:
```python
# Padronização das categorias para melhor legibilidade
senioridade_map = {
    'SE': 'senior', 'MI': 'pleno', 
    'EN': 'junior', 'EX': 'executivo'
}
df['senioridade'] = df['senioridade'].replace(senioridade_map)
```

### 🧹 Aula 2 - Limpeza e Preparação dos Dados

**Objetivos**: Garantir qualidade e consistência dos dados

**Técnicas implementadas**:
- 🔍 Identificação sistemática de valores nulos
- 🛠️ Múltiplas estratégias de preenchimento:
  - **Imputação estatística**: Média e mediana
  - **Forward/Backward Fill**: Propagação de valores
  - **Valores padrão**: Para categorias não informadas
- 🗑️ Remoção estratégica de linhas inconsistentes
- 🔄 Conversão e padronização de tipos de dados

**Resultado**: DataFrame limpo e consistente para análises posteriores

### 📈 Aula 3 - Visualização e Insights

**Objetivos**: Transformar dados em insights visuais

**Implementações**:
- 📊 Gráficos de barras para distribuição categórica
- 📋 Análise de frequências por senioridade
- 🎨 Customização de visualizações com títulos descritivos

## ⚡ Como Executar o Projeto

### Pré-requisitos
```bash
Python 3.7+
Jupyter Notebook ou JupyterLab
```

### Instalação

1. **Clone o repositório**:
```bash
git clone https://github.com/danyel-oliveira/Imersao-Dados-com-Python.git
cd Imersao-Dados-com-Python
```

2. **Instale as dependências**:
```bash
pip install pandas matplotlib numpy jupyter seaborn
```

3. **Execute o notebook**:
```bash
jupyter notebook "Imersão_Dados_com_Python.ipynb"
```

### 🌐 Executar Online
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jstd7jeaxkOa-dyVKuaqSb4tg-yoP49O)

## 💡 Principais Aprendizados

### 🎓 Competências Técnicas Desenvolvidas (Alura)
- **Pandas Mastery**: Domínio das principais funções para manipulação de DataFrames
- **Data Cleaning**: Estratégias eficazes para tratamento de dados inconsistentes
- **EDA Best Practices**: Metodologia estruturada para exploração de dados
- **Storytelling with Data**: Tradução de dados técnicos em insights compreensíveis

### 💼 Diferenciais para o Mercado
- **Projeto Hands-on**: Experiência prática com dados reais de salários tech
- **Metodologia Estruturada**: Aplicação de boas práticas da indústria
- **Documentação Profissional**: Código limpo e bem documentado
- **Continuous Learning**: Participação ativa em formação reconhecida (Alura)

## 🔄 Próximos Passos

- [ ] Análise estatística mais profunda
- [ ] Implementação de gráficos interativos com Plotly
- [ ] Análise de correlações entre variáveis
- [ ] Dashboard interativo com Streamlit
- [ ] Machine Learning para predição salarial

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Uso |
|------------|---------|-----|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=yellow) | 3.x | Linguagem principal |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) | Latest | Manipulação de dados |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=python&logoColor=white) | Latest | Visualização |
| ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) | Latest | Ambiente de desenvolvimento |

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Danyel Oliveira**
- 🌐 GitHub: [@danyel-oliveira](https://github.com/danyel-oliveira)
- 💼 LinkedIn: [Conecte-se comigo](https://linkedin.com/in/danyel-b-oliveira-746471242/)
- 🎓 **Certificação**: Imersão Dados - Alura (2025)

### 💬 Para Recrutadores
Estou sempre aberto a discutir oportunidades na área de dados! Este projeto demonstra minha capacidade de:
- Trabalhar com datasets reais e complexos
- Aplicar metodologias profissionais de análise
- Comunicar insights de forma clara e visual
- Manter aprendizado contínuo através de cursos reconhecidos

**📧 Vamos conversar sobre Data Science!**

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Sinta-se à vontade para:
- 🐛 Reportar bugs
- 💡 Sugerir melhorias
- 🔧 Enviar pull requests

---

### 🌟 **Destaque Profissional**
> *Este projeto foi desenvolvido como parte da **Imersão Dados da Alura**, demonstrando aplicação prática de conceitos de Data Science em um contexto real de mercado. Ideal para demonstrar competências técnicas a recrutadores e gestores da área de dados.*

⭐ **Se você é recrutador e este projeto despertou seu interesse, vamos conversar!**

> *"Dados são o novo petróleo, mas apenas quando refinados se tornam valiosos."* 💎
