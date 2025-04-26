Este projeto realiza uma análise completa de dados de vendas de quatro lojas, incluindo métricas de faturamento, avaliações de clientes, categorias de produtos e fretes.

📋 Visão Geral
O código Python realiza as seguintes análises:

Cálculo de faturamento total por loja (preço + frete)

Análise de categorias mais vendidas

Média de avaliações dos clientes

Identificação de produtos mais e menos vendidos

Cálculo de frete médio por loja

📊 Métricas Analisadas
1. Faturamento
Faturamento total por loja

Faturamento combinado de todas as lojas

Média de faturamento por loja

Loja com maior e menor faturamento

2. Categorias de Produtos
Quantidade vendida por categoria em cada loja

Categoria mais vendida por loja

Gráficos de vendas por categoria

3. Avaliação dos Clientes
Média de avaliação por loja

Loja com melhor e pior avaliação média

Gráfico de distribuição das avaliações

4. Análise de Produtos
Produtos mais vendidos por loja (top 5)

Produtos menos vendidos por loja

Faturamento gerado por cada produto

5. Análise de Frete
Frete médio por loja

Total de fretes calculados

Percentual de valores nulos na coluna de frete

Gráfico comparativo de fretes médios

📁 Estrutura do Código
O script principal (analise_lojas.py) contém:

Importação de dados: Carrega os CSVs de cada loja a partir do GitHub

Funções auxiliares:

contar_categorias(): Analisa vendas por categoria

analisar_produtos(): Identifica produtos mais/menos vendidos

Análises principais:

Faturamento

Categorias

Avaliações

Produtos

Fretes

Visualizações:

Gráficos de barras

Gráficos de pizza

Gráficos de barras horizontais

▶️ Como Executar
Certifique-se de ter instalado:

Python 3.x

Pandas (pip install pandas)

Matplotlib (pip install matplotlib)

Execute o script:

bash
python analise_lojas.py
Os resultados serão exibidos no console e os gráficos serão mostrados em janelas separadas.

📌 Observações
Os dados são carregados diretamente do repositório GitHub da Alura

O código trata valores nulos automaticamente

Todos os valores monetários são formatados com 2 casas decimais

Os gráficos são gerados com cores distintas para cada loja

📈 Exemplo de Saída
O programa gera:

Tabelas resumidas no console

Gráficos interativos

Destaques das principais métricas

📧 Contato
Para dúvidas ou sugestões, entre em contato com o desenvolvedor.

⬆ Voltar ao topo
