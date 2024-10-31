## Equipe

- **Ricardo Ramos Vergani - RM 550166**

## Objetivo do Projeto

- **Analisar o consumo de energia per capita** por continente.
- **Identificar relações entre consumo de energia e emissões de CO₂**.
- **Visualizar os tipos de energia mais utilizados** e seus impactos.
- **Experimentar diferentes modelos de Machine Learning** para prever tendências e padrões.

## Estrutura do Projeto

1. **Ask**: Definição de questões principais de pesquisa.
2. **Get**: Coleta de dados de fontes confiáveis.
3. **Explore**: Limpeza e exploração dos dados para verificar a consistência.
4. **Model**: Aplicação de modelos de Machine Learning para responder às questões estabelecidas.
5. **Communicate**: Relatório detalhado em Jupyter Notebook com visualizações e interpretações.

## Perguntas de Pesquisa

1. Qual é o consumo de energia per capita médio por continente?
2. Como o consumo de diferentes tipos de energia se distribui globalmente?
3. Qual é a relação entre o consumo de energia e as emissões de CO₂?
4. Quais continentes têm os maiores níveis de consumo de energia per capita?
5. Existe uma correlação significativa entre tipos de energia consumidos e níveis de emissão de gases de efeito estufa?
6. Como o consumo de energia está associado ao desenvolvimento econômico (se possível com dados adicionais)?
7. Quais países têm o menor e o maior consumo de energia per capita?
8. Qual é a porcentagem de participação de cada tipo de energia no consumo total?
9. Quais são os tipos de energia mais comuns em cada continente?
10. Como o consumo de energia e as emissões de CO₂ variam entre continentes e ao longo dos anos?

## Dados

- **Fonte**: Kaggle, World Bank, e outras fontes de dados públicas e confiáveis.
- **Características do Dataset**:
  - Colunas com informações sobre consumo de energia, emissões de gases, e tipos específicos de energia consumidos.
  - Dados de diferentes continentes para análise comparativa.

## Pré-processamento

### 1. Limpeza dos Dados
- **Tratamento de valores ausentes**: Filtramos valores nulos em colunas críticas.
- **Mapeamento dos Continentes**: Adicionamos uma coluna de continente aos países, permitindo uma análise agregada.

### 2. Enriquecimento dos Dados
- **API Externa**: Em progresso (pretende-se integrar uma Web API para adicionar dados relevantes, como índices econômicos ou variáveis adicionais).
- **LLMs e Copilot**: Ferramentas de IA foram exploradas para assistirem na análise e automação de partes do código, documentado como opcional.

## Metodologia de Análise

1. **Análise Descritiva**: Examinamos estatísticas básicas e correlações.
2. **Visualizações**: Criamos gráficos avançados com Seaborn e Matplotlib, como gráficos de dispersão, barras e pizza, para explorar os dados e suas relações.
3. **Modelagem**:
   - Experimentamos algoritmos de **regressão e classificação** do Scikit-Learn, com divisão de dados em 70% para treino e 30% para teste.
   - Avaliação de dois modelos diferentes, com explicações sobre o label/tag utilizados.

## Conclusão

Após realizar esta análise, encontramos padrões relevantes no consumo de energia e nas emissões de CO₂ globais. Por exemplo, [adicione insights específicos]. Observamos também que [insights adicionais]. Este projeto possibilita uma visão geral das diferentes fontes de energia, suas contribuições para o consumo total e seu impacto nas emissões, permitindo tomadas de decisões mais informadas para a sustentabilidade global.


Este README visa oferecer clareza sobre o objetivo, o processo e os resultados do projeto, além de reforçar o valor do portfólio no GitHub.
