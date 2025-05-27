# Análise de Reclamações de Clientes

Projeto de Análise Exploratória de Dados com Python, Pandas, Matplotlib e Seaborn, usando reclamações reais do Consumidor.gov.br para entender:

- Como evolui o volume de reclamações ao longo dos meses  
- Quais empresas aparecem no topo das queixas  
- Qual a porcentagem de reclamações Resolvidas vs Não resolvidas  
- Qual a nota média que os clientes dão  
- E descobrir que resolver bem e receber boa nota são quase a mesma coisa (correlação de 0.99!)

Ferramentas: Google Colab, Python, Pandas, Matplotlib, Seaborn  

## Objetivos

- Entender tendências de volume de reclamações por mês  
- Identificar as 10 empresas com mais queixas  
- Avaliar a taxa de resolução (% Resolvido vs Não resolvido)  
- Medir a correlação entre % resolvido e nota média 

## Como abrir o projeto

Clique para rodar direto no Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SEU_USUARIO/reclamacoes-clientes/blob/main/notebook/analise_reclamacoes.ipynb)

## Principais análises que fiz

- Série temporal: quantidade de reclamações por mês  
- Top 10 empresas com mais reclamações (barra horizontal)  
- % Resolvido vs Não Resolvido (barra empilhada)  
- Cálculo da correlação (0.99) entre resolução e nota média  

## Fonte dos dados

Base pública de reclamações disponível no Kaggle:  
[Consumidor.gov.br Dataset](https://www.kaggle.com/datasets/beatrizmsarmento/relatos-de-consumidores-do-site-consumidor-gov-br)  

## O que aprendi com este projeto

- Como limpar e manipular datas com Pandas (to_datetime, to_period)  
- Uso de value_counts(), groupby() e unstack() para agregações  
- Criação de gráficos simples: linha, barras e barras empilhadas  
- Cálculo e interpretação de correlação com .corr()

## O que observei nos dados

- Empresas de aviação e telecomunicação (Azul, Vivo, Tim) resolvem a maior parte das queixas e levam notas altas  
- Hurb e 123 Milhas quase não resolvem as queixas e consequentemente têm nota média bem baixa  
- Existe uma relação quase perfeita (0.99) entre resolver reclamações e receber boa avaliação  

## Autor

Gabriel Favoretto  
[LinkedIn](https://www.linkedin.com/in/gabriel-favoretto-636a60173/)

