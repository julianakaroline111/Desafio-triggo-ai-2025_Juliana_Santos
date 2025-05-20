# 🚀 Desafio Técnico – Programa Trainee Triggo.ai 2025

Este repositório apresenta a solução desenvolvida por **Juliana Karoline Santos** para o **Desafio Técnico do Programa de Excelência em Engenharia de Dados e DataOps da Triggo.ai**.

---

## 📌 Objetivo

Explorar e analisar dados reais do e-commerce brasileiro, com foco em:

- Limpeza, modelagem e conexão entre tabelas
- Análises com Python e SQL
- Criação de dashboards interativos e insights de negócio
- Resolução de problemas como retenção, atrasos e satisfação do cliente

---

## 🗂️ Dados Utilizados

O dataset utilizado foi o **Brazilian E-commerce Public Dataset by Olist**, disponível no Kaggle. Inclui:

- Pedidos (`orders`)
- Clientes (`customers`)
- Produtos (`products`)
- Vendedores (`sellers`)
- Avaliações de clientes (`reviews`)
- Pagamentos (`payments`)
- Geolocalização (`geolocation`)
- Tradução de categorias (`product_category_name_translation`)

---

## 📊 Entregas Técnicas

### ✅ 1. Preparação e Modelagem
- Leitura e inspeção dos arquivos CSV
- Tratamento de valores ausentes e tipos de dados
- Junção de tabelas (modelo relacional)

### ✅ 2. Análise Exploratória de Dados (SQL + Python)
- Evolução do volume de pedidos por mês
- Análise da distribuição de tempo de entrega
- Relação entre frete e distância geográfica
- Categorias com maior faturamento
- Estados com maior valor médio por pedido

### ✅ 3. Solução de Problemas Reais
- **Retenção de Clientes:** Identificação de clientes recorrentes
- **Predição de Atrasos:** Criação de modelo de classificação simples
- **Segmentação de Clientes:** Clusterização por comportamento
- **Satisfação do Cliente:** Relação entre nota, entrega e produto

### ✅ 4. Dashboards Interativos

| Visualização            | Descrição |
|-------------------------|-----------|
| 📈 **Evolução das Vendas** | Linha do tempo de pedidos por mês, com filtros por estado e categoria |
| 🗺️ **Mapa de Calor**         | Distribuição dos pedidos por estado brasileiro |
| 📦 **Nota vs Entrega**       | Boxplot relacionando tempo de entrega com nota de avaliação |
| 🧑‍💼 **Análise de Vendedores** | Comparação entre volume de vendas, tempo médio de entrega e satisfação |

---

## 🧠 Principais Insights

- Clientes com nota 5 tendem a receber mais rápido
- SP, RJ e MG concentram a maior parte das vendas
- Categorias como `bed_bath_table` e `health_beauty` lideram em faturamento
- Vendedores mais bem avaliados têm maior volume e menor tempo médio de entrega

---

## 💡 Ferramentas e Bibliotecas

- Python (Pandas, NumPy, Seaborn, Matplotlib, Plotly)
- SQL (via `pandasql`)
- Google Colab

---

## 👩‍💻 Sobre Mim

**Juliana Karoline Santos**  
Estagiária de Engenharia de Dados • Volvo do Brasil  
📍 Araucária – PR  
📧 juhkaroline10@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/julianakarolinesantos)

---

## 📝 Como Executar

1. Clone este repositório:
```bash
git clone https://github.com/julianakaroline111/Desafio-triggo-ai-2025_Juliana_Santos.git
