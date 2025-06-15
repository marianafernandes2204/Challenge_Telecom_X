# 📊 Desafio de Data Science - Análise de Evasão de Clientes (EDA) | Telecom X

Este repositório contém a solução para o desafio proposto pela **Telecom X**, com foco na **análise de evasão de clientes - EDA**. O objetivo é entender os fatores que influenciam a saída de clientes da empresa, utilizando Python e bibliotecas de análise de dados.

---

## 🎯 Objetivo

A empresa Telecom X está enfrentando um alto índice de cancelamentos de contratos. Este projeto tem como objetivo:

- **Coletar e tratar** os dados de clientes disponibilizados.
- **Explorar e entender** o comportamento dos clientes.
- **Identificar padrões** e possíveis causas de evasão de clientes.
- Oferecer **insights estratégicos** para redução da evasão de clientes.
  
---

## 🧹 Limpeza e Tratamento de Dados

As principais etapas de preparação dos dados incluíram:

- ✅ **Importação e normalização** de um arquivo JSON.
- ✅ **Separação de campos aninhados** em colunas planas.
- ✅ **Remoção** de registros com **valores ausentes** em colunas.
- ✅ **Padronização e tradução de colunas** para melhor entendimento dos analistas brasileiros.
- ✅ Criação da variável `Conta_Diarias`, baseada na fatura mensal.

---

## 🔍 Análise Exploratória de Dados (EDA)

A análise exploratória revelou importantes padrões de comportamento entre os clientes.

### 📌 Percentual Geral de Cancelamentos

- **25,8% dos clientes** cancelaram seus serviços.
- Gráficos de pizza foi utilizado para visualizar a proporção de cancelamento.

## 📊 Visualização da Evasão de Clientes

| Percentual de Cancelamentos |
|-----------------------|
| ![image](https://github.com/user-attachments/assets/d01774f4-2e60-4e96-96a0-9fe404a0752c) | 



> 📌 O gráfico acima revela que cerca de **25,8% dos clientes saíram da empresa**, enquanto **71,2% permaneceram**.

---

### 📌 Cancelamento por Variáveis Categóricas

- Clientes com **contrato mensal** têm alta taxa de cancelamento.
- Formas de pagamento como **"Electronic Check"** e o tipo de internet **'Fiber Optic'** estão mais associadas à evasão.
- Clientes que **não possuem serviços extras** tendem a sair com mais frequência.


### 📌 Cancelamento por Variáveis Numéricas

Foram analisadas variáveis e observado:

- **Clientes recém-chegados** apresentam cancelamento elevado.
- Cancelamento mais comum estão na **faixa de valor entre 70,00 e 100,00**.

---

## ✅ Recomendações

- Oferecer **incentivos para contratos de longo prazo**.
- Estimular o uso de serviços complementares.
- Adotar formas de pagamento automáticas (como débito ou cartão).
- Focar nos **primeiros meses do cliente**, com ações proativas de engajamento.

---

## 🔧 Tecnologias e Ferramentas

- Python 3.10+
- Pandas
- NumPy
- Requests
- Google Colab 
- Matplotlib
- Seaborn
- Plotly


---

## ✍️ Autor
Como parte de um desafio de análise de dados. Desenvolvido por 
| Mariana Fernandes|

---

## 📝 Licença

Este projeto foi desenvolvido apenas para fins educacionais com dados fictícios.  
Distribuído livremente sob a [MIT License](LICENSE).
