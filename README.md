# KFC | Desempenho Comercial e Marketing

**[Explore o Dashboard interativo](https://app.powerbi.com/view?r=eyJrIjoiNjkxN2E4YTMtMjEyNy00NTMxLWFhMTEtMWM4ZDRhZjAwZWI2IiwidCI6ImY0NmY3ZGY2LTMwZDgtNDg0MS1iZDk0LTU2NzAxNDMwODZiOCJ9)**

## Pipeline

**Base CSV → Power Query → Organização dos dados e KPIs com DAX → Dashboard e storytelling → Power BI Service**

## Problema de negócio

Como entender as diferenças de desempenho entre países e filiais e acompanhar a relação entre investimento em marketing e vendas? O projeto reúne essas informações para apoiar a investigação e a priorização de ações.

## Objetivo

Analisar vendas, clientes, ticket médio e investimento em marketing de **2018 a 2024**, comparando períodos e operações para identificar pontos de atenção e orientar propostas de negócio.

## Ferramentas utilizadas

- **Power BI Desktop:** KPIs, gráficos, filtros, tooltips e navegação.
- **Power Query:** preparação dos dados.
- **DAX:** cálculos dos indicadores e comparações.
- **Figma:** apoio ao layout e à identidade visual.
- **Power BI Service:** publicação do Dashboard.

## Perguntas respondidas

### Página 1 | Desempenho Comercial

- Quanto foi vendido, quantos clientes foram contabilizados e qual foi o ticket médio?
- Quais meses apresentaram maiores e menores vendas?
- Quais países concentraram mais vendas?
- Como as vendas variaram em relação ao ano anterior?

### Página 2 | Filiais e Marketing

- Quanto foi investido em marketing e qual foi seu peso sobre as vendas?
- Qual foi a relação entre vendas totais e investimento?
- Como as filiais se posicionaram em vendas e marketing?
- Em quais operações vendas e marketing variaram em direções diferentes?
- Como a proporção de marketing sobre vendas mudou entre os meses?

## Análises realizadas

**Página 1:** leitura dos KPIs comerciais, comportamento mensal, ranking de países e evolução anual das vendas.

**Página 2:** análise do investimento e de sua proporção sobre vendas, comparação das filiais na dispersão e aprofundamento das variações anuais na matriz.

Os filtros de período, país e filial permitem aprofundar o contexto; os tooltips acrescentam informações sobre o ponto selecionado.

## Principais achados

### Visão do período completo

De 2018 a 2024, sem filtros: **$1,19 Bi em vendas**, **29,90 Mi de clientes contabilizados** e **ticket médio de $39,82**. Marketing somou **$140,46 Mi**, equivalentes a **11,8% das vendas**, com relação vendas/marketing de **8,48×**.

O ticket representa uma média por cliente contabilizado. A relação 8,48× expressa vendas totais por unidade investida, não lucro ou vendas comprovadamente geradas pelo marketing.

### 1. As vendas se recuperaram?

- **Resultado:** todos os países e filiais; 2023 registrou $164,98 Mi, queda de 2,84% sobre 2022. Em 2024, foram $174,95 Mi, alta de 6,04% sobre 2023.
- **Interpretação:** houve recuperação no total, cuja distribuição entre operações merece análise.
- **Proposta:** localizar os países e filiais que sustentaram o avanço e investigar suas práticas.
- **Acompanhar:** Vendas Totais e Variação Anual de Vendas %.

### 2. Quais meses e países se destacaram?

- **Resultado:** 2018-2024, sem filtros; fevereiro liderou os totais mensais com $107,53 Mi, e dezembro teve o menor total, $90,65 Mi. O Canadá liderou os países com $247,34 Mi.
- **Interpretação:** os resultados indicam onde aprofundar a comparação. Cada mês reúne os valores de todos os anos selecionados.
- **Proposta:** verificar o padrão mensal em cada ano e comparar práticas das filiais canadenses com outras operações antes de propor ações.
- **Acompanhar:** Vendas por mês, Clientes Totais e Ticket médio.

### 3. Mais marketing foi acompanhado de mais vendas?

- **Resultado:** Austrália, 2023, todas as filiais; marketing aumentou 8,1%, enquanto vendas caíram 1,3%, frente a 2022.
- **Interpretação:** os indicadores seguiram direções diferentes; a causa não foi demonstrada.
- **Proposta:** revisar a distribuição do investimento e investigar as ações realizadas antes de ampliar o orçamento. Avaliar uma redistribuição em teste controlado.
- **Acompanhar:** variações anuais de Vendas e Marketing e Marketing sobre Vendas %.

### 4. Como interpretar o peso mensal do marketing?

- **Resultado:** agosto, reunindo 2018-2024, todos os países e filiais; $96,18 Mi em vendas e $11,13 Mi em marketing, cerca de $11,57 de marketing para cada $100 em vendas.
- **Interpretação:** a proporção pode mudar por alterações no investimento, nas vendas ou em ambos.
- **Proposta:** comparar meses do mesmo ano, lendo os valores absolutos antes de sugerir cortes ou aumentos.
- **Acompanhar:** Marketing sobre Vendas %, Investimento em Marketing e Vendas Totais.

## Storytelling

**Página 1:** dimensão do resultado → comportamento mensal → comparação dos países → evolução anual. A leitura sai do total e chega às operações e períodos que merecem atenção.

**Página 2:** investimento → proporção sobre vendas → comparação das filiais → aprofundamento na matriz. Ela retoma os recortes comerciais para investigar como o investimento se relaciona com os resultados.

Juntas, as páginas ajudam a transformar um resultado geral em uma pergunta específica e em uma proposta de ação acompanhada por KPIs.

## Recomendações e próximos passos

1. **Priorizar a investigação da Austrália em 2023.** A hipótese de ajuste na distribuição do orçamento deve ser investigada, não assumida como causa da queda.
2. **Entender a recuperação de 2024.** Identificar as operações que avançaram e avaliar práticas para pequenos testes em outros locais.
3. **Apoiar o planejamento mensal.** Confirmar padrões por ano antes de direcionar ações a meses específicos.
4. **Acompanhar os testes.** Definir operação, mudança e período de comparação; observar vendas, clientes, ticket e marketing sobre vendas antes e depois. Quando possível, comparar com uma operação semelhante sem a mudança.

As propostas não são ações já executadas. Não há promessa de economia ou crescimento, nem recomendação de corte ou aumento geral de orçamento.

## Contribuição do projeto

O Dashboard conecta desempenho comercial e investimento em marketing para ajudar a gestão a localizar pontos de atenção, comparar operações e priorizar investigações e testes de negócio.

---

**Autor:** Felipe Mageste. Projeto de portfólio com temática KFC, sem vínculo institucional. Números fixos, em $ conforme o relatório, conferidos em 25/10/2026. Apresentação reformulada em 26/10/2026. Mi = milhões; Bi = bilhões.

