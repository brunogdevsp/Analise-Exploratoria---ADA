Análise Exploratória de Dados — Curso ADA
Este repositório contém um projeto desenvolvido como parte do curso de Análise Exploratória de Dados (EDA) da plataforma ADA. O objetivo é aplicar os conhecimentos adquiridos em uma análise superficial e introdutória de um conjunto de dados reais, utilizando ferramentas comuns na ciência de dados, como Jupyter Notebook e a linguagem Python.

📊 Dataset Utilizado: Cuisine_rating (Kaggle)
O conjunto de dados utilizado para este projeto é o cuisine_rating, disponível na plataforma Kaggle. Esse dataset reúne avaliações de diversos tipos de culinária feitas por usuários, contendo colunas como o tipo de cozinha (Cuisines), a nota atribuída (Rating), entre outras informações relevantes.

A Kaggle é uma das maiores plataformas online voltadas para ciência de dados e aprendizado de máquina. Lá, é possível encontrar competições de modelagem preditiva, tutoriais, códigos prontos e principalmente uma grande variedade de datasets públicos que servem como base para aprendizado, pesquisa e experimentação em projetos de análise e modelagem de dados.

O dataset cuisine_rating foi escolhido por conter dados simples e organizados, ideais para uma introdução à exploração de dados. Ele permite visualizar como diferentes tipos de cozinha são avaliados, identificar padrões e gerar insights iniciais com base em estatísticas descritivas.

🛠 Ferramentas Utilizadas
📌 Jupyter Notebook
Ambiente interativo que permite escrever código, visualizar saídas e adicionar anotações em texto de forma organizada. Ideal para projetos de análise exploratória, pois facilita a combinação de código com interpretação.

📌 Linguagem Python
Python é uma das linguagens mais utilizadas em ciência de dados devido à sua simplicidade e ampla gama de bibliotecas específicas para análise, visualização e modelagem de dados.

📚 Bibliotecas
NumPy
A biblioteca NumPy (Numerical Python) é usada principalmente para trabalhar com arrays e operações matemáticas de alto desempenho. Ela permite realizar cálculos numéricos de forma eficiente, sendo a base de muitas outras bibliotecas na área de dados.

Pandas
A biblioteca Pandas fornece estruturas de dados como DataFrame e Series, que facilitam a manipulação, limpeza, filtragem e análise de dados tabulares. É a principal ferramenta para análise exploratória em Python, tornando o trabalho com dados estruturados rápido e intuitivo.

🔍 Conteúdo do Projeto
Neste projeto, você encontrará:

Carregamento e visualização inicial do dataset

Análise superficial dos dados (tipos, valores ausentes, estatísticas descritivas)

Filtros e agrupamentos básicos com Pandas

Insights iniciais baseados nas avaliações das diferentes culinárias

📁 Arquivo Anexo
O arquivo com toda a análise está disponível no formato Jupyter Notebook (.ipynb) e pode ser aberto com o Jupyter localmente ou no Google Colab.

🔍 Funções Utilizadas na Análise
Durante a análise, foram utilizadas algumas funções essenciais da biblioteca Pandas para inspecionar e compreender melhor o conjunto de dados:

read_csv()
Função usada para ler arquivos CSV e convertê-los em um DataFrame, estrutura principal de dados no Pandas.
Exemplo: pd.read_csv('Cuisine_rating.csv')

head()
Exibe as primeiras linhas do DataFrame (por padrão, as 5 primeiras). É útil para uma visão inicial do conteúdo dos dados.
Exemplo: df.head()

info()
Mostra um resumo do DataFrame, incluindo o número de entradas (linhas), número de colunas, tipo de dado em cada coluna e se há valores nulos.
Exemplo: df.info()

value_counts()
Conta a frequência de cada valor distinto em uma coluna. Útil para entender a distribuição de categorias, como os diferentes tipos de culinária.
Exemplo: df['Cuisines'].value_counts()

mean()
Calcula a média dos valores numéricos em uma coluna. Pode ser usada, por exemplo, para saber a média das notas atribuídas.
Exemplo: df['Rating'].mean()
