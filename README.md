# Projeto de Análise de Dados Y.Afisha

## Descrição do Projeto
Esse projeto consiste em uma análise dos acessos ao site da Y.Afisha. A tarefa é ajudar a empresa a otimizar as despesas com marketing. Para isso, será utilizado os diários do servidor com dados sobre os acessos a Y.Afisha de janeiro de 2017 até dezembro de 2018, arquivo de despejo com todos os pedidos feitos durante o período e estatísticas de despesas com marketing. Foi feito uma análise de como as pessoas usam o produto, quando elas começam a comprar, quanto dinheiro  cada cliente traz para a empresa e quando as despesas serão cobertas.

## As tarefas são:
Em relação aos produtos:
- Quantas pessoas usam o site cada dia, semana e mês?
- Quantas sessões ocorrem por dia? (um usuário pode realizar várias sessões)
- Que comprimento tem cada sessão?
- Com que frequência os usuários voltam?
Em relação as vendas:
- Quando as pessoas começam a comprar?
- Quantos pedidos os clientes fazem durante um detereminado período de tempo?
- Qual é o volume médio de uma compra?
- Quanto dinheiro eles trazem para a empresa (LTV)?
Em relação a marketing:
- Quanto dinheiro foi gasto? No total/ por origem/ ao longo do tempo
- Quanto custou a aquisição de clientes para cada origem?
- Os investimentos valeram a pena? (ROI)

## Dicionário de dados
- visits: os diários do servidor com dados sobre os acessos ao site
  - 'Uid': identificados unívoco do usuário
  - 'Device': dispositivos do usuário
  - 'Start Ts': data e hora do início da sessão
  - 'End Ts': data e hora do final da sessão
  - 'Source Id': identificador da origem do anúncio através do qual o usuário chegou
- orders: dados sobre os pedidos
  - 'Uid': identificador unívoco do usuário que faz um pedido
  - 'Buy Ts': data e hora do pedido
  - 'Revenue': a receita da Y.Afisha do pedido
- costs: dados sobre as despesas com marketing
  - 'source_id': identificador da origem do anúncio
  - 'dt': data
  - 'costs': despesas com esta origem de anúncio neste dia
 
## Ferramentas e Bibliotecas utilizadas
- Pyhton: Linguagem principal utilziada para a análise
- Pandas: Biblioteca para manipulação e análise de dados
- Matplotlib: Biblioteca para gerar gráficos
- Numpy: Biblioteca que permite trabalhar com objetos multidimensionais, como matrizes e sequências
- Math: Biblioteca que permite usar funções matemáticas
- Seaborn: Biblioteca de visualização de dados
- Scipy: Biblioteca que fornece uma manipulação conveniente e rápida de um array N-dimensional
- Ploty.express: Biblioteca que permite criar visualizações rápidas e eficientes
- Datetime: Biblioteca para manipulação de datas e horas

## Imagens

### Tabela visitas
<img src="https://github.com/user-attachments/assets/b12c4f14-2478-4c3c-ab67-80688658cbf5" alt="Projeto 8" width="200"/>

### Visitas por ano, por mês e por semana
<img src="https://github.com/user-attachments/assets/8574652d-a86a-43d6-8d44-4160b73ec848" alt="Projeto 8" width="200"/>

### Tabela visitas por dia
<img src="https://github.com/user-attachments/assets/9aa0d3e7-48da-4bf9-a929-d72dff1a0b5a" alt="Projeto 8" width="200"/>

### Visitas por ano e por mês
<img src="https://github.com/user-attachments/assets/ab14dd95-4b92-4f7e-9878-5d3d4fc4f149" alt="Projeto 8" width="200"/>

### Visitas por data
<img src="https://github.com/user-attachments/assets/2aa6a20f-470f-480a-b35b-de99669aa493" alt="Projeto 8" width="200"/>

### Frequência de visitas
<img src="https://github.com/user-attachments/assets/15d32c21-fa5b-4185-9c51-8243f2143341" alt="Projeto 8" width="200"->

### Dados das visitas
<img src="https://github.com/user-attachments/assets/816d40d9-9609-4272-bb76-9eb4f023e129" alt="Projeto 8" width="200"/>

### Taxa de retenção
<img srsc="https://github.com/user-attachments/assets/966e6ebc-cd76-42b3-ad6a-b3a46265c63b" alt="Projeto 8" width="200"/>

### Taxa de retenção porcentagem
<img src="https://github.com/user-attachments/assets/29d3760b-7d2e-446a-801c-031cfe2dc4af" alt="Projeto 8" width="200"/>

### Tabela primeira visita e primeira venda
<img src="https://github.com/user-attachments/assets/cd371a52-025e-4e5d-85ed-068e32de3454" alt="Projeto 8" width="200"/>

### Diferença primeira visita e primeira venda
<img src="https://github.com/user-attachments/assets/f6977f10-de36-470b-8400-a9ab723ec3e9" alt="Projeto 8" width="200"/>

### Média de pedidos por semana
<img src="https://github.com/user-attachments/assets/0606084d-e919-4dd5-a4f7-6f05507ecf52" alt="Projeto 8" width="200"/>

### Pedidos dentro de um pedido
<img src="https://github.com/user-attachments/assets/4d14bef8-5336-46cc-bb7d-c85480f19c0b" alt="Projeto 8" width="200"/>

### Volume médio de compras
<img src="https://github.com/user-attachments/assets/32d1cfad-aed1-4918-a04e-e479da6e08b9" alt="Projeto 8" width="200"/>

### LTV
<img src="https://github.com/user-attachments/assets/3e3641f1-1843-42ba-9c80-49809f4ffbef" alt="Projeto 8" width="200"/>

### Custos
<img src="https://github.com/user-attachments/assets/79ed2d18-c4d3-4cc2-b129-419aae855a1a" alt="Projeto 8" width="200"/>

### Custos por mês
<img src="https://github.com/user-attachments/assets/54a0086f-6e29-4a98-b5db-9629b2f60462" alt="Projeto 8" width="200"/>

### Custo de aquisição
<img src="https://github.com/user-attachments/assets/37a6055d-f8a7-4c95-aa5c-16683a4da102" alt="Projeto 8" width="200"/>

### Média CAC por mês
<img src="https://github.com/user-attachments/assets/edb84666-cdf6-40ca-b3c2-e4b8c401b8b5" alt="Projeto 8" width="200"/>

### Pedidos
<img src="https://github.com/user-attachments/assets/3fbad79b-c832-4af1-b398-28cf19c71968" alt="Projeto 8" width="200"/>

### ROI fonte 1
<img src="https://github.com/user-attachments/assets/4e8cb6ca-8964-4be9-a6d9-b321dbf79c1a" alt="Projeto 8" width="200"/>

### ROI fonte 2
<img src="https://github.com/user-attachments/assets/eebc74eb-d06f-4d40-a9d3-227ed2f8eab2" alt="Projeto 8" width="200"/>

### ROI fonte 3
<img src="https://github.com/user-attachments/assets/72954bef-26bd-44cb-b966-8221b6d86fcd" alt="Projeto 8" width="200"/>

### ROI fonte 4
<img src="https://github.com/user-attachments/assets/c55fea45-c8dd-4c46-b6a9-561fd3ff2e45" alt="Projeto 8" width="200"/>

### ROI fonte 5
<img src="https://github.com/user-attachments/assets/3c9244c8-b5d6-4f38-aaf1-c3deee8c71d0" alt="Projeto 8" width="200"/>

### ROI fonte 9
<img src="https://github.com/user-attachments/assets/7c97dc56-ac7e-425a-ab3b-ae29a48e8a56" alt="Projeto 8" width="200"/>

### ROI fonte 10
<img src="https://github.com/user-attachments/assets/c66c95ba-7bcc-4fc8-bdf5-480922c937ae" açt="Projeto 8" width="200"/>

## Resultados
- Foi possível concluir que existe diferença entre os diferentes source
- O investimento vale a pena
- Existe diferença entre como as pessoas usam o produto diariamente, semanalmente e mensalmente
- Com que frequência as pessoas usam
- O tempo que dura cada sessão
- A data de início que as pessoas começaram a usar
- Dinheiro que os clientes trazem para a empresa
- A diferença entre os ROIs

## Aprendizados
- Análise de dados
- Qualidade dos dados
- Tratar os dados modificando tipos de colunas, valores ausentes, valores duplciados
- Criação de novas colunas com dados referentes aos dias, meses e semana
- Agrupar dados
- Análise de coortes
- Construção e análise de gráficos
- Construção e análise de mapas de calor
- Calcular ROI, LVT, CAC, ROMI

## Contexto real
- Empresas de marketing
- Novas campanhas de marketing
- Empresas que querem melhorar sua área de marketing
- Novas empresas que querem lançar campanhas de marketing eficientes
  
## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal
