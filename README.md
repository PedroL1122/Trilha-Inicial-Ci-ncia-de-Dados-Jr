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

plaintext
Copy code
.
├── vendas_cursos.csv          # Arquivo CSV gerado a partir da análise
├── analise_vendas_cursos.ipynb  # Jupyter Notebook com todo o código da análise
├── README.md                  # Descrição do projeto
└── requirements.txt           # Lista das dependências necessárias
Instalação
Pré-requisitos
Antes de começar, certifique-se de ter o Python 3.x instalado em sua máquina. Além disso, recomenda-se o uso de um ambiente virtual para instalar as dependências do projeto, como venv.

# Clonando o Repositório
bash
Copy code
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Ambiente Virtual (opcional, mas recomendado)
Crie um ambiente virtual e ative-o:

bash
Copy code
python -m venv venv
# No Windows
venv\Scripts\activate
# No macOS/Linux
source venv/bin/activate
Instalando as Dependências
As dependências do projeto estão listadas no arquivo requirements.txt. Instale-as com:

bash
Copy code
pip install -r requirements.txt
As principais bibliotecas utilizadas são:

pandas: Manipulação e análise de dados.
Matplotlib: Criação de gráficos e visualizações.
Seaborn: Estilização e gráficos estatísticos.
Uso

# Executando a Análise

Abra o Jupyter Notebook:
bash
Copy code
jupyter notebook analise_vendas_cursos.ipynb
Execute as células passo a passo para realizar a análise dos dados e gerar as visualizações gráficas.
Explicação dos Cálculos
Cálculo da Receita: Multiplicação da Quantidade de Vendas pelo Preço Unitário de cada curso.
Curso Mais Vendido: Identificação do curso com a maior quantidade de vendas usando a função idxmax() para localizar o curso.
Receita ao Longo do Tempo: Uso do resample para agrupar a receita diária e gerar um gráfico de linha que mostra a variação ao longo dos dias.
Gráfico de Barras das Vendas: Visualização da quantidade de vendas por curso usando o barplot do Seaborn.

# Exportação dos Resultados

Os resultados da análise são exportados para um arquivo CSV chamado vendas_cursos.csv. Este arquivo contém todas as informações de vendas, incluindo a receita calculada.

#Visualizações Geradas


# As visualizações incluem:

Gráfico de Linha: Receita ao longo dos dias, mostrando a tendência das vendas.
Gráfico de Barras: Quantidade de vendas por curso, facilitando a comparação do desempenho entre os cursos.
<img src="exemplo_grafico_linha.png" alt="Gráfico de Receita ao Longo do Tempo" width="500"> <img src="exemplo_grafico_barras.png" alt="Gráfico de Barras das Vendas por Curso" width="500">
Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias.


#Contato
Para dúvidas ou sugestões, entre em contato:

Nome: Pedro Henrique Cunegundes
E-mail: bangue062@gmail.com
LinkedIn: Pedro Cunegundes
