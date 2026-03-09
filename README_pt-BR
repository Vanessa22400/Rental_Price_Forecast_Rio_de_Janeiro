# Previsão de Preços de Aluguel Residencial no Rio de Janeiro: Uma Análise de Séries Temporais
*Modelagem de séries temporais para compreender a dinâmica de longo prazo dos preços de aluguel e gerar insights sobre o mercado imobiliário no Rio de Janeiro.*

**Dataset:** 16 anos de dados de aluguel residencial (2010–2025)  
**Técnicas:** Análise Exploratória de Dados, Modelagem de Séries Temporais (ARIMA), Análise de Tendências  
**Resultado principal:** As previsões com ARIMA indicam que os preços de aluguel podem atingir aproximadamente **~R$60/m² até 2027**, mantendo a tendência de alta observada ao longo do período analisado.

---

## Contexto de Negócio

A acessibilidade à moradia tornou-se um tema cada vez mais discutido em grandes cidades ao redor do mundo, especialmente em centros urbanos com forte atividade turística.

Cidades como **Barcelona, Medellín e Rio de Janeiro** têm vivenciado debates públicos intensos sobre o impacto de plataformas de aluguel de curto prazo, como o Airbnb, nos mercados imobiliários locais. Em destinos altamente turísticos, a conversão de imóveis residenciais em acomodações de curto prazo pode reduzir a oferta de moradia para residentes e contribuir para o aumento dos preços de aluguel.

Tendo vivido no **Rio de Janeiro** e em outras cidades globais, observei pessoalmente como os preços de aluguel aumentaram significativamente ao longo do tempo, especialmente em bairros com forte atividade turística.

Este projeto foi inicialmente motivado pela ideia de comparar **preços de aluguel de longo prazo com plataformas de aluguel de curto prazo, como o Airbnb**. No entanto, devido a limitações de dados, a análise passou a focar na **evolução histórica dos preços de aluguel residencial** e na identificação de tendências estruturais no mercado imobiliário do Rio.

Compreender essas dinâmicas é relevante para:

• Residentes que avaliam a acessibilidade à moradia  
• Investidores imobiliários que monitoram tendências de longo prazo  
• Urbanistas e formuladores de políticas públicas que analisam pressões habitacionais em cidades turísticas  

Uma análise baseada em dados permite ir além de percepções anedóticas e oferece uma visão mais clara de como os preços de aluguel evoluem ao longo do tempo.

---

## Dataset

Fonte: Índice FipeZAP  
https://www.datazap.com.br/conteudos-fipezap/

O Índice FipeZAP é um indicador oficial que acompanha os preços do mercado imobiliário residencial no Brasil.

Para este projeto, o conjunto de dados foi filtrado para incluir:

• **Cidade:** Rio de Janeiro  
• **Tipo de imóvel:** imóveis residenciais para aluguel  
• **Frequência:** observações mensais  
• **Período:** Jan 2010 – Dez 2025  

O dataset final contém **16 anos de dados de preços de aluguel**, utilizados para análise exploratória e previsão em séries temporais.

---

## Problema de Pesquisa

Os dados históricos de preços de aluguel podem ser utilizados para identificar tendências estruturais e gerar previsões plausíveis para os preços de aluguel residencial no Rio de Janeiro?

---

## Objetivos

• Realizar uma análise exploratória estruturada dos dados históricos de aluguel  
• Identificar tendências de longo prazo e possíveis padrões sazonais  
• Aplicar técnicas de modelagem de séries temporais para prever a evolução dos preços  
• Traduzir resultados estatísticos em insights de mercado  
• Demonstrar como a análise de séries temporais pode apoiar a compreensão do mercado imobiliário

---

## Metodologia

1. **Limpeza e Pré-processamento dos Dados**  
Filtragem do dataset para incluir apenas imóveis residenciais para aluguel no Rio de Janeiro e garantir consistência nas observações mensais.

2. **Análise Exploratória de Dados**  
Identificação de tendências de preços, padrões de volatilidade e comportamentos estruturais no mercado de aluguel.

3. **Preparação da Série Temporal**  
Agregação e transformação dos dados em uma série temporal mensal adequada para previsão.

4. **Modelagem de Séries Temporais**  
Aplicação de modelos ARIMA para capturar padrões históricos e estimar trajetórias futuras dos preços de aluguel.

5. **Geração de Insights**  
Interpretação dos resultados do modelo no contexto da dinâmica urbana do mercado habitacional.

---

## Ferramentas e Tecnologias

• Python (Pandas, NumPy)  
• Statsmodels (ARIMA)  
• Matplotlib  
• Seaborn  
• Métodos de Análise de Séries Temporais

---

## Principais Resultados da Análise Exploratória

A análise exploratória revelou vários padrões estruturais no mercado de aluguel:

• **Tendência consistente de alta:** os preços de aluguel aumentaram significativamente ao longo do período analisado, indicando pressão estrutural no mercado habitacional.

• **Períodos de crescimento acelerado:** alguns intervalos de tempo apresentam aumentos mais rápidos de preços, possivelmente associados a ciclos macroeconômicos e à demanda relacionada ao turismo.

• **Volatilidade de mercado:** flutuações de curto prazo sugerem sensibilidade a fatores externos, como condições econômicas e oferta de moradia.

• **Choques macroeconômicos:** a série reflete eventos econômicos importantes no Brasil, incluindo a desaceleração econômica entre **2015–2017** e a **pandemia de COVID-19 (2020–2021)**, ambos associados a mudanças visíveis na dinâmica dos preços de aluguel.

Esses insights motivaram a aplicação de modelos de séries temporais para compreender melhor a evolução dos preços.

![Rental price time series](Images/2Annual_Variation.png)

**Figura:** Variação percentual anual dos preços de aluguel residencial no Rio de Janeiro (2010–2025), destacando períodos de desaceleração econômica e o impacto da COVID-19.

---

## Abordagem de Modelagem

Este projeto utiliza **técnicas de previsão em séries temporais** para estimar a evolução dos preços de aluguel ao longo do tempo.

A estratégia de modelagem busca capturar:

• **Componentes de tendência**, refletindo o crescimento de longo prazo dos preços imobiliários  
• **Sazonalidade**, potencialmente associada a ciclos de turismo e demanda habitacional  
• **Flutuações aleatórias**, representando variabilidade de curto prazo no mercado

Modelos ARIMA foram escolhidos por sua forte interpretabilidade e adequação para previsões estruturadas em séries temporais.

---

## Desempenho do Modelo

Um modelo univariado **ARIMA(1,1,1)** foi utilizado para prever os preços mensais de aluguel com base nas tendências históricas.

Os parâmetros estimados foram estatisticamente significativos:

- **Coeficiente AR(1):** 0.89 (p < 0.001)  
- **Coeficiente MA(1):** 0.17 (p = 0.018)

Esses resultados indicam **forte persistência temporal**, ou seja, movimentos passados de preços influenciam fortemente valores futuros.

Testes diagnósticos apoiam a adequação do modelo:

- **Teste Ljung-Box (p = 0.56):** ausência de autocorrelação significativa nos resíduos  
- A análise dos resíduos sugere que a principal estrutura temporal da série foi capturada

Embora o ARIMA não incorpore fatores econômicos externos, o modelo fornece uma **projeção estável baseada em tendência** para a dinâmica futura dos preços de aluguel.

---

## Visualização da Previsão

A figura a seguir compara os preços históricos de aluguel com a previsão baseada em ARIMA para os próximos 24 meses.

![Rental price forecast](Images/3Rental_Price_Forecast.png)

A previsão sugere que os preços de aluguel podem atingir aproximadamente **~R$60 por metro quadrado até 2027**, caso a tendência observada na última década continue.

Relatórios recentes do mercado indicam que os preços de aluguel em grandes cidades brasileiras já superam **R$50 por metro quadrado**, o que sugere que a trajetória projetada pelo modelo permanece economicamente plausível.

---

## Principais Insights

A análise revela diversas dinâmicas estruturais no mercado de aluguel do Rio de Janeiro:

• **Crescimento persistente dos preços:** os valores passaram de aproximadamente **R$22/m² em 2010 para mais de R$55/m² em 2025**, indicando forte valorização de longo prazo.

• **Recuperação pós-pandemia:** após uma interrupção visível durante **2020–2021**, os preços retomaram uma forte tendência de alta a partir de 2022.

• **Forte persistência temporal:** o modelo ARIMA confirma que movimentos passados de preços influenciam significativamente valores futuros, sugerindo um impulso estrutural no mercado.

• **Crescimento projetado:** a previsão indica que os preços de aluguel podem alcançar aproximadamente **R$60/m² até 2027** se as tendências atuais persistirem.

• **Pressão estrutural de demanda:** unidades menores, especialmente **apartamentos de um quarto**, apresentam consistentemente preços mais altos por metro quadrado, refletindo forte demanda em áreas urbanas densas.

• **Pressão do turismo sobre a moradia:** cidades com forte atividade turística, como o Rio de Janeiro, frequentemente enfrentam pressão adicional no mercado habitacional, à medida que aluguéis de curto prazo competem com a oferta residencial de longo prazo.

---

## Impacto de Negócio e Aplicações

Os resultados desta análise podem apoiar diversas aplicações no mundo real:

**Monitoramento do mercado imobiliário**  
Agentes do setor podem acompanhar a dinâmica de preços ao longo do tempo.

**Planejamento de investimentos**  
Investidores podem utilizar padrões históricos para avaliar oportunidades de mercado.

**Análise de políticas urbanas**  
Planejadores urbanos podem avaliar pressões de longo prazo sobre a acessibilidade à moradia.

**Inteligência de mercado**  
Plataformas de aluguel e empresas imobiliárias podem integrar monitoramento de tendências de preços em suas decisões estratégicas.

---

## Limitações

* A análise utiliza um **modelo univariado de séries temporais (ARIMA)** e não incorpora fatores externos como taxas de juros, inflação ou indicadores macroeconômicos.

* Embora o projeto discuta a possível influência de **plataformas de aluguel de curto prazo (ex.: Airbnb)**, esse fator não foi modelado diretamente devido à disponibilidade de dados.

* Mudanças estruturais no mercado imobiliário podem influenciar a dinâmica futura de preços além dos padrões históricos observados.

---

## Próximos Passos

Possíveis extensões deste projeto incluem:

* Incorporar variáveis macroeconômicas (inflação, taxas de juros)  
* Incluir segmentação por bairros  
* Expandir o modelo com técnicas adicionais de previsão  
* Construir dashboards interativos para monitorar a dinâmica do mercado de aluguel  
* Comparar preços de aluguel de longo prazo com plataformas de aluguel de curto prazo (ex.: Airbnb) para quantificar o impacto potencial da demanda turística no mercado habitacional.

---

## Estrutura do Repositório

```
.
├── data
├── notebooks
├── images
├── requirements.txt
└── README.md
```

---

## Perspectiva Estratégica

Neste projeto, busquei combinar **análise técnica de séries temporais com interpretação contextual da dinâmica urbana do mercado habitacional**.

Minha abordagem analítica também é influenciada por experiências pessoais vivendo em diferentes cidades e países. Observar como mercados imobiliários evoluem localmente ajudou a questionar pressupostos e conectar padrões estatísticos ao contexto do mundo real.

Essa perspectiva contribui para transformar análises de dados em **insights relevantes para tomada de decisão**.

---

## Conclusão

Este projeto demonstra como a análise de séries temporais pode ajudar a compreender a dinâmica de longo prazo do mercado imobiliário.

Utilizando aproximadamente **15 anos de dados de aluguel**, a análise identificou uma forte tendência de alta nos preços residenciais no Rio de Janeiro e gerou uma previsão de curto prazo indicando continuidade desse crescimento.

Além do exercício de previsão, o projeto mostra como análises estruturadas podem transformar dados históricos em insights relevantes para **análise de mercado imobiliário, economia urbana e discussões sobre políticas habitacionais**.
