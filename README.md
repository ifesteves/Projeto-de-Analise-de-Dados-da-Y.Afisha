# Projeto de Análise de Dados da Y.Afisha

## Introdução
Neste projeto, iremos analisar os dados da Y.Afisha, uma empresa de marketing online, para otimizar suas despesas com marketing. Utilizaremos logs do servidor, registros de pedidos e estatísticas de despesas para entender como as pessoas usam o produto, quando elas começam a comprar e quanto dinheiro cada cliente traz para a empresa. Nosso objetivo final é fornecer recomendações aos especialistas de marketing sobre onde e quanto investir.

## Conjuntos de Dados
Os conjuntos de dados fornecidos são os seguintes:

1. `visits_log_us.csv`: Contém dados sobre os acessos ao site, incluindo o identificador único do usuário, dispositivo usado, início e fim da sessão, e identificador da origem do anúncio.
2. `orders_log_us.csv`: Contém dados sobre os pedidos, incluindo o identificador único do usuário, data e hora do pedido, e receita gerada.
3. `costs_us.csv`: Contém dados sobre as despesas com marketing, incluindo o identificador da origem de anúncio, data e valor dos custos.

## Passos do Projeto

### Passo 1: Preparação dos Dados
Nesta etapa, carregaremos os dados de acesso, pedidos e despesas em variáveis e os otimizaremos para análise. Certificaremos de que cada coluna contenha o tipo correto de dados.

### Passo 2: Relatórios e Cálculo de Métricas
Realizaremos análises sobre o produto, vendas e marketing, calculando métricas importantes, tais como:
- Uso do produto por dia, semana e mês
- Volume de sessões por dia e duração média das sessões
- Início de compras por período de tempo
- Número de pedidos e volume médio de compra
- Receita total e LTV (Lifetime Value) dos clientes
- Despesas totais, por origem e ao longo do tempo
- Custo de aquisição de clientes por origem
- ROI (Return on Investment)

Construiremos gráficos para visualizar essas métricas e entender as tendências ao longo do tempo e entre diferentes dispositivos e origens de anúncios.

### Passo 3: Conclusões e Recomendações
Com base nas análises realizadas, elaboraremos recomendações aos especialistas de marketing sobre onde e quanto investir, fundamentando nossas escolhas nas métricas relevantes.

