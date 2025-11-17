# Agente para extração de dados de jogos

## Necessário criar um arquivo .env com uma api key do mistral antes de usar o agente.
## Necessário também instalar as dependencias no requirements.txt

Este agente extrai os dados vgsales.csv, o qual contém informações sobre vendas de diversos jogos e responde perguntas do usuário. 
O agente está preparado para responder perguntas como:

- Qual o jogo mais vendido 
- Quais os 5 (ou N) jogos mais vendidos 
- Qual o jogo menos vendido 
- Quais os N jogos menos vendidos 
- Qual a soma das vendas dos N jogos mais vendidos 
- Qual a soma das vendas dos N jogos menos vendidos 
- Quantos jogos a publisher X publicou 
- Qual o jogo que mais vendeu no pais X (estados unidos, japao ou europa) 
- Qual o ano com mais jogos lancados 
- Qual a plataforma com mais jogos lancados 
- Qual o genero com mais jogos lancados 
- Qual o ano com menos jogos lancados 
- Qual a plataforma com menos jogos lancados 
- Qual o genero com menos jogos lancados