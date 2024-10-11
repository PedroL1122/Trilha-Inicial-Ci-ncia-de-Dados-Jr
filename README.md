### Análise de Vendas de Cursos

Descrição do Projeto
Este projeto realiza uma análise detalhada das vendas de cursos de uma plataforma online. A partir de dados sobre vendas, como nome do curso, quantidade vendida, preço unitário e data de venda, são gerados insights importantes e visualizações gráficas que permitem entender melhor o desempenho dos cursos ao longo do tempo.

# A análise inclui:

Cálculo da receita total gerada pela venda dos cursos.
Identificação do curso com o maior número de vendas.
Visualização da receita ao longo do tempo.
Gráficos de barras para a quantidade de vendas por curso.
Exportação dos resultados para um arquivo .csv para análise futura.

# Estrutura do Projeto


.
├── vendas_cursos.csv     Arquivo CSV gerado a partir da análise

├── analise_vendas_cursos.ipynb  Jupyter Notebook com todo o código da análise

├── README.md                  Descrição do projeto

└── requirements.txt           Lista das dependências necessárias


# Explicação dos Cálculos

Cálculo da Receita: Multiplicação da Quantidade de Vendas pelo Preço Unitário de cada curso.
Curso Mais Vendido: Identificação do curso com a maior quantidade de vendas usando a função idxmax() para localizar o curso.
Receita ao Longo do Tempo: Uso do resample para agrupar a receita diária e gerar um gráfico de linha que mostra a variação ao longo dos dias.
Gráfico de Barras das Vendas: Visualização da quantidade de vendas por curso usando o barplot do Seaborn.

# Exportação dos Resultados

Os resultados da análise são exportados para um arquivo CSV chamado vendas_cursos.csv. Este arquivo contém todas as informações de vendas, incluindo a receita calculada.

# Visualizações Geradas
As visualizações incluem:

Gráfico de Linha: Receita ao longo dos dias, mostrando a tendência das vendas.
Gráfico de Barras: Quantidade de vendas por curso, facilitando a comparação do desempenho entre os cursos.
<img src="exemplo_grafico_linha.png" alt="Gráfico de Receita ao Longo do Tempo" width="500"> 

<img src="exemplo_grafico_barras.png" alt="Gráfico de Barras das Vendas por Curso" width="500">
Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias.


# Contato
Para dúvidas ou sugestões, entre em contato:

Nome: Pedro Henrique Cunegundes
E-mail: bangue062@gmail.com
LinkedIn: Pedro Cunegundes
