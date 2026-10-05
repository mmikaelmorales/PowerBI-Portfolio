# 🚚 Dashboard Executivo de Logística

## Objetivo

Projeto desenvolvido para simular uma operação logística corporativa utilizando Python, Power Query, DAX e Power BI.

O objetivo foi reproduzir um cenário próximo ao encontrado em empresas reais, incluindo geração de dados, problemas de qualidade, tratamento, modelagem dimensional e construção de dashboards gerenciais.

## Tecnologias Utilizadas

- Python
- Pandas
- Power BI
- Power Query
- DAX
- Excel

## Geração dos Dados

A base foi criada em Python contendo:

- 2.000 pedidos
- 500 clientes
- 18 produtos
- Transportadoras
- Datas de pedido e entrega
- Valores de frete
- Status de entrega

## Problemas de Qualidade Simulados

- 40 Pedidos Duplicados
- 80 Fretes Nulos
- 60 Datas Ausentes
- 100 Status Inconsistentes
- 100 Transportadoras Inconsistentes
- 50 CEPs Ausentes
- 50 UFs Inconsistentes

## Tratamentos Aplicados

- Remoção de duplicidades
- Padronização de status
- Padronização de transportadoras
- Correção de UFs inconsistentes
- Tratamento de valores ausentes
- Criação das dimensões analíticas

## Estrutura do Dashboard

- Dashboard Executivo
- Qualidade dos Dados
- Análise Operacional

## Considerações

Este projeto demonstra um fluxo completo de Business Intelligence e Analytics:

Python → Geração dos Dados → Problemas Simulados → Power Query → Tratamento → Modelagem Estrela → DAX → Power BI
