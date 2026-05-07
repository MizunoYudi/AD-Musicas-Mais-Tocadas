# Análise Exploratória — Músicas Mais Tocadas em 2024

Projeto desenvolvido para a disciplina de Análise de Dados do Instituto Federal de São Paulo (IFSP) — Câmpus Boituva.

## Integrantes
- Mateus Gois
- João Mizuno

## Objetivo

Realizar uma análise exploratória de dados (EDA) sobre músicas mais populares em 2024, utilizando métricas de plataformas digitais como Spotify, YouTube, TikTok, Apple Music, Deezer, Pandora e outras.

O projeto busca responder três desafios principais:

- Identificar padrões musicais que impulsionam popularidade
- Avaliar o impacto de diferentes mídias sociais na divulgação de músicas
- Analisar métricas de engajamento ao longo do tempo

---

# Sobre a base de dados

A base contém informações de engajamento musical em múltiplas plataformas digitais.

### Informações gerais

| Atributo | Valor |
|---|---|
| Registros | 4.600 músicas |
| Variáveis | 29 atributos |
| Período | Décadas de 1980 até 2024 |
| Artistas únicos | ~2.000 |
| Plataformas | Spotify, YouTube, TikTok, Deezer, Pandora, Shazam, Apple Music, TIDAL, AirPlay |

---

# Ferramentas utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# Etapas do projeto

## 1. Limpeza e tratamento de dados

Foram aplicados diversos processos de preparação dos dados:

- Tratamento de valores nulos com `fillna()`
- Conversão de tipos (`object → int/float`)
- Conversão de datas com `datetime`
- Identificação de duplicatas
- Criação da variável temporal `Year`
- Identificação de outliers com método IQR

---

## 2. Análise estatística e visual

### Medidas estatísticas
- Média
- Mediana
- Desvio padrão
- Quartis
- Outliers

### Visualizações utilizadas
- Histogramas
- Boxplots
- Scatterplots
- Heatmaps
- Gráficos de linha
- Barplots

---

# Principais Insights

## Spotify e YouTube apresentam correlação moderada
Músicas populares em uma plataforma tendem a performar bem na outra.

## TikTok atua principalmente como plataforma de viralização
O sucesso no TikTok não implica necessariamente alto consumo contínuo no Spotify.

## Playlists possuem forte influência nos streams
A presença em playlists do Spotify apresentou relação clara com o número de execuções.

## Track Score possui baixa correlação com streams
A nota atribuída à faixa não se mostrou um fator determinante de popularidade.

## Músicas antigas podem voltar ao topo
Plataformas como TikTok contribuem para a revalorização de músicas antigas através de trends e viralizações.

---

# Resultados

A análise demonstrou que o sucesso musical digital depende principalmente de:

- presença em playlists
- divulgação multiplataforma
- constância de lançamentos
- alcance em redes sociais

Além disso, os dados mostraram forte presença de outliers, especialmente em métricas do TikTok, refletindo o comportamento viral da plataforma.


