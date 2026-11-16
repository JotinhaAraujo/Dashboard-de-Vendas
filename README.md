<div align="center">

# Painel Analítico de Vendas
### Análise Exploratória de Dados e Inteligência de Negócios

Transformando dados comerciais em informações estratégicas para apoio à tomada de decisão.

</div>

---

## Sobre o Projeto

Este projeto tem como objetivo estruturar, analisar e visualizar dados comerciais para acompanhar o desempenho de vendas e identificar oportunidades de negócio.

A solução foi dividida em duas frentes complementares: a **Análise Exploratória de Dados**, voltada ao saneamento e diagnóstico da base, e a **Inteligência de Negócios**, focada na entrega de um painel gerencial interativo para acompanhamento contínuo dos resultados.

---

## Resumo das Entregas

### 01. Análise Exploratória e Tratamento de Dados
*Ferramentas: Python, Pandas, Numpy, Matplotlib, Seaborn e Ambiente Jupyter*

Etapa dedicada à auditoria, saneamento e compreensão estatística da base histórica de vendas:
* **Diagnóstico e Saneamento:** Mapeamento da estrutura dos dados, verificação de consistência e tratamento de registros ausentes.
* **Análise Estatística:** Estudo do comportamento das variáveis e distribuição dos volumes comerciais.
* **Desempenho e Sazonalidade:** Avaliação do faturamento segmentado por categoria e produto, além do mapeamento da evolução temporal das receitas.
* **Síntese Executiva:** Consolidação das principais descobertas para orientar a camada visual.

### 02. Inteligência de Negócios e Visualização
*Ferramentas: Power BI*

Construção de uma interface gerencial interativa para monitoramento estratégico dos resultados:
* **Indicadores de Desempenho:** Estruturação de métricas-chave para acompanhamento direto das metas comerciais.
* **Visão Comparativa e Geográfica:** Mapeamento da receita por categoria de produto e distribuição regional das vendas.
* **Segmentação Dinâmica:** Implementação de filtros interativos por Unidade Federativa (UF), modelo de assinatura e categoria, permitindo análises sob demanda.

---

## Fluxo de Trabalho

<div align="center">

```mermaid
flowchart LR
    A["Base de Dados"] --> B["Análise Exploratória"]
    B --> C["Saneamento e Tratamento"]
    C --> D["Modelagem Analítica"]
    D --> E["Painel Gerencial"]
    E --> F["Tomada de Decisão"]
