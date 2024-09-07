# Projeto de Análise de Dados Y.Afisha

## Descrição do Projeto
Esse projeto consiste em uma análise dos acessos ao site da Y.Afisha.
A tarefa é ajudar a empresa a otimizar as despesas com marketing

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

## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal
