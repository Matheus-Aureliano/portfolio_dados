# Portfólio de Análise de Dados

Este repositório reúne projetos de análise de dados e dashboards
criados no Looker Studio.

## 📊 Dashboard – População Mundial (1950–2021)
- Análise da evolução da população mundial desde 1950.
- KPIs de população total, população masculina e feminina por ano.
- Ranking dos países mais populosos.
- Análise da população adulta e idosa no Brasil.

🔗 Link do dashboard:
[Dashboard Population](https://lookerstudio.google.com/reporting/3e6f786f-8fe9-4825-a27d-0cf143da3b2f)

---

## 🦠 Dashboard – COVID-19 no Brasil (2021)
- Análise de casos, mortes e vacinação da COVID-19 no Brasil.
- KPIs de casos e mortes nas últimas 24h e média móvel de 7 dias.
- Visualização do avanço da vacinação (1ª, 2ª e 3ª dose).
- Gráficos de média de casos e mortes confirmadas e mapa geográfico.

🔗 Link do dashboard:
[Dashboard Pandemia](https://lookerstudio.google.com/reporting/2570c597-7790-41ae-abdf-cc5ffcc17d3f)

---


## 💳 Mini Projeto – Análise de Crédito (SQL)

- Análise de um dataset de crédito com informações demográficas e financeiras de clientes.

- Exploração de padrões de limite de crédito, transações e produtos adquiridos.

- Cruzamento de variáveis como sexo, estado civil, salário anual, idade e escolaridade.

 - O dataset original possuía cerca de 10 mil registros; foi utilizado um subconjunto de aproximadamente 2 mil linhas para a análise exploratória.

 - Os dados foram convertidos para Excel e carregados no Amazon S3, permitindo consultas via Amazon Athena (SQL).

🎯 Objetivo principal: explorar padrões de comportamento financeiro dos clientes.

🔗 Link do Colab:
[Mini projeto](https://colab.research.google.com/drive/1QSjTDSQrsPu8BgJob8K-BiGWDq7IzlQB?usp=sharing)

---

## 🤖 Pipeline de Dados – Chatbot do Telegram

- Construção de um pipeline completo para coletar, transformar e analisar dados gerados por um chatbot no Telegram.

- Integração com a API de Bots do Telegram para capturar mensagens e eventos em tempo quase real.

- Armazenamento de dados brutos em AWS S3 e transformação para dados analíticos em formato Parquet.

- Processos de ETL e data wrangling para padronizar campos, tratar dados opcionais e gerar tabelas consistentes para análise.

- Análises demonstrativas incluem volume de mensagens por dia e participação por usuário, extraídas via SQL e visualizadas com gráficos.

- Arquitetura organizada separando sistema transacional (Telegram) do sistema analítico (pipeline de dados), seguindo boas práticas de engenharia de dados.

🔗 Link do Colab:
[Pipeline de Dados Telegram](https://colab.research.google.com/drive/1j1g49X6StLVGSPAe-PzxBZkY5MeTNePI?usp=sharing)

