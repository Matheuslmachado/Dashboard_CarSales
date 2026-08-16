# 🚗 AutoDrive Motors --- Sales Analytics

Projeto de **Análise de Dados e Business Intelligence** desenvolvido
para simular um cenário real de uma rede de concessionárias.

## 🎯 Objetivo

Transformar dados brutos de vendas de veículos em informações para
apoiar decisões comerciais, analisando:

-   Faturamento e volume de vendas
-   Desempenho por região e revendedor
-   Marcas e modelos mais vendidos
-   Perfil dos clientes
-   Preço médio e ticket médio
-   Oportunidades de negócio

## 🛠️ Tecnologias

-   **Python / Pandas** --- ETL, limpeza e tratamento dos dados
-   **BigQuery** --- armazenamento e consulta dos dados
-   **Power BI** --- indicadores e dashboard
-   **Figma** --- design e UX/UI

## 🔄 Fluxo do projeto

``` text
Dados brutos
    ↓
Python / ETL
    ↓
BigQuery
    ↓
Power BI
    ↓
Dashboard Executivo
```

## 📊 Resultado esperado

Um dashboard executivo capaz de transformar os dados de vendas em
**insights acionáveis**, permitindo que gestores acompanhem a
performance comercial e identifiquem oportunidades de crescimento.

> Projeto desenvolvido para portfólio, com foco na aplicação prática de
> conceitos de **ETL, análise de dados, BI e tomada de decisão
> baseada em dados**.


## Estrutura do repositório
 
```
├── config/
│   ├── GBQ.json
├── dashboard/
│    ├── img/
│    │   ├── Capa.png
│    │   ├── Cliente.png
│    │   ├── Performance.png
│    │   ├── Produto.png
│    │   └── Revendedores.png
│    └── CarSales.pbix
├── data/
│   ├── sales_car_tratada.csv
│   └── sales_car.csv
├── python/
│   └── etl.ipynb
├── .gitignore
└── README.md
```
