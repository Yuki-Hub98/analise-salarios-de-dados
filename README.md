# 📊 Análise de Salários na Área de Dados e Programação

Este documento descreve **os gráficos e análises presentes no dashboard**, cujo objetivo é explorar salários de profissionais da área de **Dados e Programação** com base em diferentes recortes, como cargo, tipo de trabalho, país e faixa salarial.

O dashboard foi desenvolvido em **Streamlit**, utilizando **Pandas** para tratamento dos dados e **Plotly** para visualizações interativas.

---

## ⚙️ Execução local do projeto

Para rodar o projeto localmente, é necessário:

* Criar um ambiente virtual Python (**venv**)
* Instalar as dependências listadas no arquivo **requirements.txt**

```bash
pandas==2.2.3 
streamlit==1.44.1 
plotly==5.24.1
```

Esses passos garantem que o projeto funcione corretamente e de forma isolada do restante do sistema.

---

## 📈 Visão geral das análises

O dashboard permite analisar salários anuais (em USD) de profissionais da área de dados, como:

* Data Scientist
* Data Analyst
* Data Engineer
* Machine Learning Engineer
* Outros cargos técnicos relacionados

Os dados podem ser filtrados por:

* Ano
* Senioridade
* Tipo de contrato
* Tamanho da empresa

Esses filtros permitem uma análise comparativa e personalizada dos salários.

---

## 📊 Gráfico 1 — Top 10 cargos por salário médio

Este gráfico apresenta os **10 cargos com maior salário médio anual**.

### Objetivo da análise:

* Identificar quais cargos da área de dados/programação são mais bem remunerados
* Comparar a média salarial entre diferentes funções técnicas

### Tipo de gráfico:

* Gráfico de barras horizontais

### Interpretação:

Cargos mais especializados e estratégicos tendem a apresentar salários médios mais altos, refletindo maior demanda de mercado e complexidade técnica.

---

## 📊 Gráfico 2 — Distribuição de salários anuais

Este gráfico mostra a **distribuição dos salários anuais** considerando todos os registros filtrados.

### Objetivo da análise:

* Visualizar a concentração salarial
* Identificar faixas de salário mais comuns
* Observar possíveis outliers (salários muito altos ou muito baixos)

### Tipo de gráfico:

* Histograma

### Interpretação:

A maior parte dos profissionais se concentra em faixas intermediárias de salário, enquanto salários muito elevados aparecem com menor frequência.

---

## 🥧 Gráfico 3 — Proporção dos tipos de trabalho

Este gráfico apresenta a proporção entre os diferentes **modelos de trabalho**, como:

* Remoto
* Presencial
* Híbrido

### Objetivo da análise:

* Entender a distribuição dos regimes de trabalho na área de dados
* Avaliar a presença do trabalho remoto no mercado

### Tipo de gráfico:

* Gráfico de pizza (donut)

### Interpretação:

O gráfico evidencia a relevância do trabalho remoto na área de tecnologia, especialmente em cargos ligados a dados e programação.

---

## 🌍 Gráfico 4 — Salário médio de Data Scientists por país

Este gráfico mostra o **salário médio de Data Scientists por país**, considerando o local de residência do profissional.

### Objetivo da análise:

* Comparar salários entre diferentes países
* Identificar regiões com maior remuneração média

### Tipo de gráfico:

* Mapa coroplético

### Interpretação:

Países com mercados de tecnologia mais maduros tendem a apresentar salários médios mais elevados, refletindo custo de vida, demanda e investimento em dados e inovação.

---

## 📋 Tabela de dados detalhados

Além dos gráficos, o dashboard disponibiliza uma **tabela com os dados filtrados**, permitindo:

* Visualização detalhada dos registros
* Análise individual de salários, cargos e características

---

## ✅ Conclusão

O dashboard fornece uma visão clara e interativa sobre:

* Salários de profissionais de dados e programação
* Diferenças entre cargos, países e modelos de trabalho
* Tendências do mercado ao longo dos anos

Essa análise é útil tanto para **estudos acadêmicos** quanto para **entendimento do mercado de trabalho em tecnologia**.

