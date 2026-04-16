# 📊 Dashboard de Vendas 2026 — Power BI

Dashboard interativo de vendas desenvolvido no Power BI, conectado a uma planilha de dados que atualiza as métricas automaticamente conforme novos registros são inseridos.

![Dashboard de Vendas 2026](dashboard_preview.png)

---

## 🚀 Sobre o Projeto

Este projeto foi criado para centralizar e visualizar os principais indicadores de desempenho comercial de uma equipe de vendas. Com atualização dinâmica dos dados, o dashboard permite acompanhar resultados em tempo real sem necessidade de ajustes manuais.

---

## 📌 Métricas Exibidas

- **Total de Vendas 2026** — Receita total acumulada no período
- **Número de Pedidos** — Quantidade total de pedidos realizados
- **Ticket Médio** — Valor médio por pedido
- **Cancelamentos** — Total de pedidos cancelados no período

---

## 📈 Visualizações

| Gráfico | Descrição |
|---|---|
| Vendas por Vendedor | Ranking de desempenho individual em R$ |
| Vendas por Região | Distribuição percentual por região do país |
| Vendas por Categoria | Gráfico de rosca com proporção por categoria de produto |
| Top Produtos | Tabela com quantidade vendida e receita por produto |

---

## 🔧 Filtros Disponíveis

- **Data** — Intervalo de datas personalizável
- **Região** — Filtro por região (Nordeste, Centro-Oeste, Sul, Sudeste, Norte)
- **Vendedor** — Filtro por vendedor individual

---

## 🗂️ Estrutura do Repositório

```
📁 Dashboard-Vendas/
├── 📊 dashboard_vendas_2026.pbix   
├── 📄 vendas_topstore_v2.xlsx           
├── 🖼️ dashboard_preview.png       
└── 📝 README.md
```

---

## ▶️ Como Usar

Siga os passos abaixo para executar o dashboard localmente:

## 1. Clonar ou baixar o repositório

  - `git clone https://github.com/Gabriel-Orlandi-Portes/Dashboard-Vendas.git`
  - Ou baixe o .zip diretamente pelo GitHub.

## 2. Abrir o projeto no Power BI
  - Abra o arquivo dashboard_vendas_2026.pbix no Power BI Desktop

## 3. Verificar conexão com os dados
  - O dashboard utiliza como fonte o arquivo vendas_topstore_v2.xlsx
    
  **3.1 Caso o caminho esteja quebrado:**
  - Página inicial  
  - Transformar Dados  
  - Clique na engrenagem da Fonte  
  - Atualize o caminho do arquivo Excel

## 4. Atualizar os dados
  - Clique em Atualizar
  - Todas as métricas e visuais serão recalculados automaticamente

## 5. Usar com seus próprios dados (Opcional) 

  - Para adaptar o dashboard para outra base de dados:

Mantenha a mesma estrutura de colunas:

Data  
ID  
Produto  
Categoria    
Regiao  
Qtd  
Preco_Unit_R$  
Status  

  - Substitua o arquivo Excel original (passo 3.1)
  - Clique em Atualizar
---

## 🛠️ Tecnologias Utilizadas

- Power BI Desktop
- Microsoft Excel (.xlsx) como fonte de dados

---

## 📋 Pré-requisitos

- Power BI Desktop
- Microsoft Excel ou qualquer editor de planilhas compatível com `.xlsx`

---

## 📬 Contato

Desenvolvido por **Gabriel Orlandi Portes**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gabriel-orlandi-portes)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gabriel-Orlandi-Portes)

---

- 📌 Projeto para fins educacionais.
