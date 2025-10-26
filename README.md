# Análise do Catálogo da Netflix

## Descrição
Este projeto analisa o dataset público da Netflix disponível no Kaggle, contendo informações sobre filmes e séries da plataforma.  
O objetivo é explorar o conteúdo disponível, estudar e aprender melhor sobre análise de dados e das bibliotecas panda e matplotlib, gerar visualizações e obter insights sobre tendências de produção e distribuição.

## Análises realizadas

### 1. Distribuição de Filmes e Séries
Gráfico de pizza mostrando a proporção de títulos por tipo e gráfico de barras mostrando essa proporção de forma numérica.

**Insight:**  
A Netflix possui aproximadamente 70% de filmes e 30% de séries no catálogo, evidenciando o foco maior em longas-metragens.

### 2. Distribuição de Produções por País
Gráfico de pizza mostrando a distribuição percentual de produções por país e gráfico de barras para análise com valores numéricos

**Insight:**
A Netflix possui filmes de diversos países. São tantos países que foi necessários reduzir a quantidade de amostras a serem analisadas para as 5 com maior número de produções.

Além disso, os EUA são os líderes no catálogo da Netflix com sobras para o segundo, que é a Índia. Os dois primeiros levam os sucessos da Hollywood e de Bollywood, respectivamente, como base para o sucesso.

### 3. Lançamentos por Ano
Gráfico de barras mostrando quantas produções foram lançadas em cada ano.

**Insight:**
A Netflix traz uma gama muito grande de variedade de épocas, tendo em vista que o mesmo tratamento que os gráficos do tópico 2 tiveram que ter, a redução do espaço amostral.

Fora isso, ela leva como auge dos filmes os anos por volta de 2018, tendo em vista que são os anos com mais produções no catálogo da plataforma, além de 2018, que é o ano com mais filmes lançados na Netflix.

### 4. Duração Média dos Filmes
Gráfico de barras mostrando a minutagem dos filmes no catálogo da Netflix. Nessa análise só foram comparados filmes, tendo em vista que as séries são contadas por temporadas e os filmes por minutagem.

**Insight:**
O mesmo tratamento de dados teve que ser feito, a gama de filmes com minutagens diferentes é bem alta.

A Netflix e seus usuários devem achar que a faixa de 90 a 100 minutos a melhor de assistir, pois é a faixa onde há a maior quantidade de filmes no catálogo.

## Dataset
- Fonte: [Netflix Movies and TV Shows – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Arquivo: `netflix_titles.csv`

## Ferramentas utilizadas
- Python  
- Pandas  
- Matplotlib  
- Google Colab
