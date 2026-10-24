# 🏎️ Dashboard de Vendas Porsche
<img width="1365" height="390" alt="image" src="https://github.com/user-attachments/assets/36a97a0a-f1f2-4a43-bd7b-c26c3b4f4f2d" />

📊 Projeto de análise de dados desenvolvido com auxílio do ChatGPT, utilizando HTML, CSS e JavaScript para transformar uma planilha de vendas em uma dashboard interativa.

O objetivo é explorar os dados, visualizar padrões e gerar informações que ajudem na análise das vendas de veículos Porsche.

---

## 🎯 Objetivo do projeto

- 📈 Analisar o comportamento das vendas.
- 🚘 Identificar os modelos mais vendidos.
- 🌎 Comparar as vendas entre cidades.
- 💰 Acompanhar o faturamento registrado.
- 🔎 Explorar tendências e possíveis oportunidades de negócio.

## 💡 1. Perguntas de negócio

A dashboard foi criada para responder às seguintes perguntas:

- 🚗 Quais são os modelos Porsche mais vendidos?
- 📍 Quais modelos se destacam em cada cidade?
- 📅 Qual ano de modelo aparece com maior frequência?
- 📈 Como as vendas evoluem ao longo do tempo?
- 💵 Como o faturamento varia entre os períodos?
- 💳 Quais formas de pagamento são mais utilizadas?
- 🚚 Qual é a situação das entregas?
- 🔍 Existe alguma relação entre quilometragem e preço?

Essas perguntas ajudam a analisar diferentes aspectos do negócio, como volume de vendas, distribuição geográfica, valores financeiros e informações operacionais.

## 📊 2. O que a dashboard apresenta?

### Indicadores (KPIs)

- 🧾 Quantidade de registros de vendas.
- 💰 Receita identificada.
- 🎯 Ticket médio.
- 🏆 Modelo com maior número de vendas.
  
### Filtros interativos

- 🚘 Modelo Porsche.
- 📅 Ano do modelo.
- 📍 Cidade.
- 🗺️ Estado.
- 💳 Forma de pagamento.

### Gráficos e análises

- 🚗 Comparação entre modelos
- 📅 Distribuição das vendas por ano
- 📈 Evolução mensal das vendas e do faturamento
- 📍 Análise por cidade
- 💳 Formas de pagamento
- 🚚 Situação das entregas
- 🛣️ Relação entre quilometragem e preço
  
Os filtros permitem explorar diferentes recortes da base e visualizar os dados de acordo com os critérios selecionados.

## 🤖 3. Prompt utilizado

O prompt foi desenvolvido para orientar a criação da dashboard e definir as principais funcionalidades, visualizações e características do projeto.

> Crie uma dashboard interativa em HTML para analisar os dados de vendas de veículos Porsche utilizando a planilha fornecida como base.
>
> Utilize um design moderno e sofisticado, com fundo escuro, detalhes em vermelho, indicadores e gráficos organizados.
>
> Inclua filtros por modelo, ano do modelo, cidade, estado e forma de pagamento.
>
> Apresente indicadores de quantidade de vendas, receita identificada, ticket médio e modelo mais vendido.
>
> Inclua gráficos para analisar os modelos mais vendidos, os resultados por cidade, os anos de modelo, a evolução mensal das vendas, o faturamento, as formas de pagamento, a situação das entregas e a relação entre quilometragem e preço.
>
> Adicione insights automáticos e uma tabela com informações por cidade. Os filtros devem atualizar os indicadores e os gráficos correspondentes.
>
> Analise a planilha antes de utilizar os dados. Verifique inconsistências, padronize categorias quando necessário e sinalize limitações relevantes.
>
> Entregue o resultado em um único arquivo HTML, pronto para ser aberto em um navegador.

### 🔧 Evolução do projeto

- 🧩 **Estrutura inicial:** definição das perguntas de negócio, dos filtros e dos indicadores.
- 📊 **Novas análises:** inclusão de gráficos para modelos, cidades, anos, faturamento e formas de pagamento.
- 🚚 **Análises complementares:** inclusão da situação das entregas e da relação entre quilometragem e preço.
- 🎨 **Melhorias visuais:** ajustes nas cores, nos cartões, no layout e na organização dos gráficos.
- 🏁 **Versão final:** manutenção do tema escuro, detalhes em vermelho e imagem do Porsche no cabeçalho.

## 🧹 4. Tratamento dos dados

A base utilizada foi a planilha `Planilha base Porshe.xlsx`, com 100 registros de vendas.

Entre os campos disponíveis estão data, modelo, ano do modelo, preço, cidade, estado, forma de pagamento, quilometragem e situação da entrega.

Antes de apresentar os dados na dashboard, foram considerados os seguintes cuidados:

- 📅 Verificação dos formatos de data.
- 🏷️ Padronização de categorias quando necessário.
- 🔢 Conferência dos campos numéricos.
- ⚠️ Identificação de possíveis dados ausentes ou inconsistentes.
- 💲 Manutenção da identificação dos preços em dólares americanos (USD).

O tratamento busca reduzir problemas de interpretação e permitir a construção dos gráficos. Nem todas as inconsistências da base necessariamente foram corrigidas, por isso os resultados devem ser interpretados considerando as limitações dos dados originais.

## 🛠️ 5. Tecnologias e ferramentas

- 🤖 ChatGPT com Canvas: apoio na criação e no aprimoramento do código e do layout.
- 🌐 HTML: estrutura da dashboard.
- 🎨 CSS: cores, organização e identidade visual.
- 💻 JavaScript: filtros, cálculos e interatividade.
- 📊 Chart.js: criação dos gráficos.
- 📗 Excel: base de dados utilizada na análise.
  
O desenvolvimento foi realizado com o ChatGPT e o Canvas. Não foi utilizado um agente com skill específica neste projeto.


## 📌 Considerações finais

Este projeto demonstra como a análise de dados e a inteligência artificial podem auxiliar na criação de dashboards interativas para transformar dados em informações visuais.

Além de praticar a organização e a interpretação de dados, o projeto permitiu explorar perguntas de negócio, desenvolver indicadores e utilizar gráficos para facilitar a identificação de padrões.

**🚀 Projeto desenvolvido para fins de estudo e aprendizado em análise de dados.**
