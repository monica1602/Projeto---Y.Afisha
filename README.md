# Projeto de Análise de Dados Y.Afisha

## Descrição do Projeto
Este projeto consiste na análise dos dados de acesso ao site da Y.Afisha, com o objetivo de fornecer informações que permitam à empresa otimizar suas despesas com marketing. A análise é baseada nos diários do servidor, que contêm informações sobre os acessos à plataforma durante o período de janeiro de 2017 a dezembro de 2018, além de arquivos de pedidos, que detalham as transações realizadas pelos usuários, e nas estatísticas relacionadas às despesas com marketing. O foco da análise foi entender o comportamento dos usuários ao utilizar a plataforma, identificar o momento em que eles iniciam as compras, calcular o valor que cada cliente contribui para a empresa e estimar o ponto de equilíbrio financeiro, ou seja, quando as despesas com marketing começam a ser compensadas pelas receitas geradas.

## As tarefas são:
Em relação aos produtos:
- Quantas pessoas usam o site cada dia, semana e mês?
A análise será focada na quantidade de usuários distintos que acessam o site em diferentes intervalos de tempo, seja diariamente, semanalmente ou mensalmente. Isso ajuda a medir o tráfego e entender os padrões de engajamento.
- Quantas sessões ocorrem por dia?
Cada vez que um usuário acessa o site, uma nova sessão é registrada. A contagem de sessões diárias permitirá avaliar o volume de interações com o site ao longo do tempo, considerando que um único usuário pode ter várias sessões em um dia.
- Qual é o comprimento de cada sessão?
O tempo médio de duração das sessões, desde o momento que o usuário entra no site até a sua saída, é um dado relevante para medir o engajamento do usuário e a eficiência do site em reter visitantes.
- Com que frequência os usuários voltam?
A análise da frequência de retorno dos usuários permite identificar o nível de fidelidade e engajamento do público com o site, observando quantos usuários retornam após a primeira visita.

Em relação às vendas:
- Quando as pessoas começam a comprar?
Analisar o momento em que os usuários iniciam suas compras no site, incluindo o tempo entre o primeiro acesso e a primeira compra, ajudará a entender o comportamento de conversão dos usuários.
- Quantos pedidos os clientes fazem durante um determinado período de tempo?
A análise do número de pedidos feitos por cada cliente ao longo de um período específico (semanal, mensal, etc.) permite entender o comportamento de compra repetida e as tendências de consumo.
- Qual é o volume médio de uma compra?
O valor médio de cada pedido permitirá avaliar o ticket médio de vendas e ajudar a identificar o perfil de gasto dos consumidores.
- Quanto dinheiro eles trazem para a empresa (LTV)?
O Life Time Value (LTV) de um cliente representa a receita total gerada por um cliente durante seu tempo de relacionamento com a empresa. A análise do LTV é essencial para avaliar o valor de um cliente ao longo do tempo.

Em relação ao marketing:
- Quanto dinheiro foi gasto? No total, por origem e ao longo do tempo?
O rastreamento dos gastos com marketing, tanto no total quanto segregados por origem (ex: anúncios pagos, marketing orgânico, campanhas específicas), ajudará a entender a distribuição do orçamento e a evolução do investimento ao longo do tempo.
- Quanto custou a aquisição de clientes para cada origem?
A análise do Custo de Aquisição de Clientes (CAC) por origem permitirá entender a eficiência das diferentes estratégias de marketing utilizadas pela empresa.
- Os investimentos valeram a pena? (ROI)
O Retorno sobre o Investimento (ROI) será calculado para avaliar a eficácia das campanhas de marketing, comparando o custo com a receita gerada, para determinar se os investimentos realmente trouxeram retornos positivos.

Essas questões são cruciais para a otimização das operações e estratégias de marketing da Y.Afisha, fornecendo insights valiosos sobre o comportamento dos clientes, o desempenho das vendas e a eficiência dos investimentos em marketing.

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
- Python: Linguagem principal utilizada para análise de dados, muito versátil e com várias bibliotecas específicas para análise estatística e visualização de dados.
- Pandas: Biblioteca essencial para a manipulação e análise de dados, proporcionando estruturas de dados eficientes como DataFrames, que facilitam a limpeza e análise de grandes volumes de informações.
- Matplotlib: Biblioteca amplamente utilizada para a criação de gráficos estáticos, permitindo a visualização de dados de forma clara e acessível.
- Numpy: Biblioteca poderosa para trabalhar com arrays e matrizes multidimensionais, essencial para cálculos numéricos e operações matemáticas rápidas.
- Math: Biblioteca matemática padrão de Python, que fornece funções para cálculos matemáticos mais avançados, como operações trigonométricas, exponenciais, logaritmos, entre outras.
- Seaborn: Biblioteca baseada no Matplotlib, com foco na criação de gráficos mais estéticos e informativos, permitindo explorar e visualizar os dados de maneira mais eficaz.
- Scipy: Biblioteca para manipulação avançada de arrays N-dimensionais, além de fornecer funções úteis para integração, otimização, álgebra linear e estatísticas.
- Plotly.express: Biblioteca para criação de gráficos interativos de forma rápida e eficiente, sendo uma excelente opção para dashboards e relatórios dinâmicos.
- Datetime: Biblioteca que oferece diversas funcionalidades para manipulação de datas e horas, permitindo realizar operações como cálculos de tempo, formatação e extração de partes específicas de datas.

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
<img src="https://github.com/user-attachments/assets/15d32c21-fa5b-4185-9c51-8243f2143341" alt="Projeto 8" width="200"/>

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
<img src="https://github.com/user-attachments/assets/c66c95ba-7bcc-4fc8-bdf5-480922c937ae" alt="Projeto 8" width="200"/>

## Resultados
- Foi possível concluir que há diferenças significativas entre as diferentes fontes de tráfego, impactando diretamente no comportamento dos usuários e nas métricas de aquisição.
- O investimento em marketing mostrou-se vantajoso, pois o retorno sobre o investimento (ROI) indicou que os custos foram compensados pelos lucros gerados.
- Há diferenças notáveis no comportamento dos usuários em relação à frequência de uso do produto: enquanto alguns usuários acessam o site diariamente, outros fazem isso semanal ou mensalmente.
- A análise de uso revelou padrões de frequência, com um número significativo de usuários retornando para sessões regulares, enquanto outros têm interações esporádicas.
- O tempo médio de cada sessão foi analisado e revelou-se um fator importante na avaliação da experiência do usuário, com variações dependendo da origem de tráfego e do comportamento do cliente.
- A data de início de uso do produto foi identificada, permitindo traçar o momento exato em que os usuários começaram a interagir mais ativamente com o site.
- O LTV (Lifetime Value) dos clientes foi calculado para entender quanto dinheiro cada cliente gera para a empresa ao longo do tempo, permitindo ajustes nas estratégias de aquisição.
- A diferença entre os ROIs de diferentes canais foi analisada, indicando quais fontes de tráfego e campanhas publicitárias tiveram um impacto mais positivo nas finanças da empresa.

## Aprendizados
- Análise de dados: A primeira etapa do processo envolveu a exploração e análise dos dados disponíveis, visando identificar padrões e insights relevantes para otimização das despesas com marketing.
- Qualidade dos dados: A verificação da qualidade dos dados foi essencial para garantir que as conclusões tiradas fossem precisas e confiáveis. Isso incluiu verificar a consistência dos dados, identificar valores ausentes e valores duplicados.
- Tratar os dados modificando tipos de colunas, valores ausentes, valores duplicados: Durante o pré-processamento, os tipos de dados das colunas foram ajustados conforme necessário, e valores ausentes e duplicados foram tratados adequadamente para não comprometer a análise.
- Criação de novas colunas com dados referentes aos dias, meses e semana: Para facilitar a análise temporal, novas colunas foram criadas com informações sobre os dias da semana, meses e semanas, permitindo observar padrões de comportamento dos usuários ao longo do tempo.
- Agrupar dados: Dados foram agrupados por diferentes períodos (diário, semanal, mensal) e outras características relevantes (origem do tráfego, por exemplo) para entender melhor as tendências e insights relacionados aos comportamentos dos usuários e métricas de marketing.
- Análise de coortes: A análise de coortes foi realizada para segmentar usuários com base no momento em que começaram a utilizar o site, permitindo identificar diferenças de comportamento entre grupos de usuários ao longo do tempo.
- Construção e análise de gráficos: Foram gerados gráficos para visualizar a distribuição dos dados e entender padrões de comportamento de forma clara e eficiente.
- Construção e análise de mapas de calor: Mapas de calor foram utilizados para identificar padrões geográficos e horários de maior atividade no site, ajudando a otimizar campanhas de marketing e entender os pontos de maior interesse para os usuários.
- Calcular ROI, LTV, CAC, ROMI: O retorno sobre o investimento (ROI), valor do tempo de vida do cliente (LTV), custo de aquisição de cliente (CAC) e retorno sobre o marketing (ROMI) foram calculados para avaliar a eficácia das campanhas publicitárias e investimentos em marketing. Esses cálculos ajudaram a otimizar os gastos e aumentar a rentabilidade.

## Contexto real
- Empresas de marketing: Agências e consultorias que buscam otimizar campanhas e investimentos, utilizando dados detalhados para entender o comportamento do cliente e o retorno das campanhas.
- Novas campanhas de marketing: Empresas que estão planejando ou já executando campanhas de marketing e desejam mensurar a eficácia dessas campanhas, seja por origem de tráfego ou por ROI.
- Empresas que querem melhorar sua área de marketing: Organizações que têm áreas de marketing em operação, mas buscam insights sobre como melhorar sua eficiência, segmentar melhor os públicos e tomar decisões mais embasadas em dados.
- Novas empresas que querem lançar campanhas de marketing eficientes: Startups e empresas que estão começando e desejam estabelecer campanhas de marketing bem estruturadas e mensuráveis desde o início, maximizando o retorno sobre o investimento.
  
## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal
