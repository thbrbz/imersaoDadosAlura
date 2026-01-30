# 🎲 Dashboard de Análise de Salários na Área de Dados

Este projeto é uma aplicação interativa desenvolvida para explorar e visualizar tendências salariais globais no mercado de dados. Através de uma interface intuitiva, a aplicação permite analisar como diferentes fatores — como senioridade, tipo de contrato e localização — influenciam a remuneração em dólares (USD).

## 🚀 Tecnologias Utilizadas

O projeto foi construído com as seguintes ferramentas:

- **Python:** Linguagem de programação principal.
- **Streamlit:** Framework para criação de dashboards web interativos.
- **Pandas:** Biblioteca para manipulação e análise de dados.
- **Plotly Express:** Biblioteca para geração de gráficos dinâmicos e mapas.

## 📊 Funcionalidades e Componentes

### 1. Filtros Personalizados

A barra lateral oferece controles para refinar a análise conforme necessário:

- **Ano:** Filtre por períodos específicos.
- **Senioridade:** Compare níveis de experiência (Junior, Pleno, Senior, etc.).
- **Tipo de Contrato:** CLT, Freelance, Part-time ou Full-time.
- **Tamanho da Empresa:** De pequenas empresas a grandes multinacionais.

### 2. Painel de Métricas (KPIs)

Exibição instantânea de dados estatísticos baseados nos filtros selecionados:

- **Salário Médio:** A média aritmética das remunerações.
- **Salário Máximo:** O maior valor registrado na amostra filtrada.
- **Total de Registros:** Quantidade de dados analisados.
- **Cargo Mais Frequente:** Identificação da função com maior representatividade.

### 3. Visualizações Gráficas

- **Top 10 Cargos:** Gráfico de barras com as maiores médias salariais por cargo.
- **Distribuição Salarial:** Histograma para identificar a densidade de faixas salariais.
- **Proporção de Trabalho:** Gráfico de rosca detalhando a divisão entre modelos presenciais e remotos.
- **Mapa Global:** Mapa coroplético focado no cargo de _Cientista de Dados_ para análise geográfica.

### 4. Dados Detalhados

Uma seção de tabela completa (`dataframe`) que permite a inspeção minuciosa dos dados brutos após a aplicação dos filtros.

## 🛠️ Como Executar

Para rodar este projeto localmente, siga os passos abaixo:

1. **Instale as dependências:**

   ```bash
   pip install streamlit pandas plotly

   ```

2. **Execute a aplicação:**
   ```bash
   streamlit run app.py
   ```
