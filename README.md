#  Dashboard de Logística

## Visão Geral

Este dashboard foi desenvolvido para **monitorar e otimizar o desempenho logístico** de uma empresa que opera com múltiplas transportadoras e centros de distribuição. A visualização dos dados permite uma **tomada de decisão rápida**, baseada em **indicadores-chave (KPIs)** como **OTIF**, **entregas no prazo**, e **faturamento por cliente**.

🔗 **Acesse o Dashboard no Power BI:**  
> [Clique aqui para visualizar](https://app.powerbi.com/links/EqBAevfc5w?ctid=da49a844-e2e3-40af-86a6-c3819d704f49&pbi_source=linkShare)
---

##  Objetivos do Dashboard

- Acompanhar o desempenho logístico ao longo do tempo
- Identificar transportadoras com melhor ou pior performance
- Analisar o impacto dos desvios operacionais
- Visualizar os principais clientes por volume de faturamento
- Facilitar filtros por transportadora, tipo de envio, UF e datas

---

##  Storytelling dos Dados

###  Performance ao Longo do Tempo

O gráfico de linha com área representa o desempenho logístico mensal com dois indicadores:

- **% In Full (laranja):** pedidos entregues de forma completa
- **% On Time (roxo):** pedidos entregues no prazo

#### Evolução

- De **jan a set/2022**, a performance foi estável: entregas completas acima de 80%, mas pontualidade entre 40-50%.
- Em **out/nov**, houve leve queda no % On Time, possivelmente relacionada à sobrecarga da operação.
- Em **dez/2022**, uma **queda significativa** ocorreu em ambos os indicadores, sugerindo impacto da alta demanda de fim de ano.

### OTIF (On Time In Full)

- O KPI OTIF aparece no centro com **60,84%**, indicando que **apenas 6 em cada 10 pedidos foram entregues no prazo e de forma completa**.

### Desempenho por Transportadora

- **Expresso Gardênia** e **Maersk** são as transportadoras com melhor entrega no prazo (~64%).
- **Viação Ouro e Prata** tem o pior desempenho, com 43,28% de atrasos.
- A escolha da transportadora impacta diretamente o desempenho logístico.

### Desvios Operacionais

- **97,47% das entregas ocorreram sem desvios**, o que mostra que a **operação interna é eficiente**.
- O principal gargalo está na **última milha (entrega final)**.

### Conclusão

O dashboard revela que, apesar de um bom desempenho em completar entregas, ainda há um **desafio crítico com a pontualidade**. Isso reforça a importância de:

- Melhorar a gestão das transportadoras
- Planejar antecipadamente períodos de pico
- Estabelecer SLAs claros e mecanismos de cobrança de performance

---

## Tecnologias Utilizadas

Este dashboard foi construído utilizando:

- **Power BI**: Visualizações dinâmicas, KPIs e painéis interativos
- **Microsoft Excel**: Pré-processamento de dados, integração com planilhas operacionais
- **Microsoft Power Query**: ETL de dados
- **DAX (Data Analysis Expressions)**: Cálculos e medidas personalizadas
- **Mapas Interativos e gráficos combinados** para visualização espacial e comparativa

---

## ✅ Conclusão

Este dashboard é uma ferramenta poderosa para **tomar decisões baseadas em dados** no setor logístico. Ele oferece **transparência operacional**, promove **responsabilidade entre transportadoras**, e destaca **oportunidades de melhoria contínua**.
