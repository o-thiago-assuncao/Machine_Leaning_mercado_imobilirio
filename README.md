🧠 Machine Learning – Mercado Imobiliário
📋 Descrição do Projeto

Este projeto tem como objetivo aplicar Machine Learning supervisionado para prever o preço de imóveis com base em variáveis como área, número de quartos, localização, idade do imóvel e outros atributos relevantes.
O trabalho foi desenvolvido inteiramente no Google Colab, utilizando um conjunto de dados realista para o mercado imobiliário e explorando todas as etapas essenciais de um pipeline de aprendizado de máquina.

🧩 Objetivo e Funcionamento do Modelo

O modelo implementado é uma Regressão Linear, um dos algoritmos mais fundamentais e interpretáveis do aprendizado supervisionado.
Seu funcionamento pode ser resumido em três etapas principais:

Entrada (Input)
O modelo recebe variáveis quantitativas e qualitativas — como metragem, número de quartos, localização e estado de conservação.

Processamento (Treinamento)

Os dados passam por limpeza e tratamento de valores ausentes.

Variáveis categóricas são transformadas em numéricas via encoding.

O modelo aprende uma relação matemática entre os atributos (X) e o preço (y).

Saída (Output)

A partir de novas entradas, o modelo estima o valor previsto do imóvel.

São avaliadas métricas de desempenho como:

R² (Coeficiente de Determinação): mede quanto da variação dos preços reais é explicada pelo modelo (≈0.81 indica excelente ajuste).

MAE (Erro Médio Absoluto): erro médio em relação aos valores reais (~R$ 84 mil).

RMSE (Raiz do Erro Quadrático Médio): mede a dispersão dos erros (~R$ 106 mil).

👉 Em resumo: o modelo aprende padrões dos dados históricos para estimar com boa precisão o valor de novos imóveis — um exemplo claro de aplicação prática de ciência de dados no mercado imobiliário.

📊 Principais Etapas do Projeto

Análise Exploratória (EDA): visualização da distribuição das variáveis e correlações.

Pré-processamento: tratamento de outliers, normalização e codificação de variáveis categóricas.

Treinamento do Modelo: divisão em conjuntos de treino e teste; aplicação da regressão linear.

Avaliação: cálculo de métricas (R², MAE, RMSE).

Visualização dos Resultados: gráficos de dispersão e comparação entre valores reais e previstos.

⚙️ Tecnologias e Bibliotecas Utilizadas

Python 3.10+

Google Colab

Pandas, NumPy – manipulação e análise de dados

Scikit-learn – modelagem preditiva e métricas

Matplotlib, Seaborn – visualização de dados

▶️ Execução do Projeto

Você pode abrir o notebook diretamente no Google Colab clicando no link abaixo:

📂 Estrutura de Arquivos
├── data/
│   └── Base_casas_regressao.csv     ← Base de dados utilizada pelo modelo
├── ML_Mercado_imobiliario.ipynb     ← Notebook principal (Google Colab)
└── requirements.txt                 ← Dependências do projeto

⚠️ Instrução importante

Antes de executar o notebook, faça o upload do arquivo Base_casas_regressao.csv dentro da pasta data/ no ambiente do Colab (ou ajuste o caminho do dataset no código caso use outro local).
Isso garante que o modelo possa carregar e processar corretamente os dados de entrada.

📈 Resultados Obtidos
Métrica	Valor Aproximado	Interpretação
R²	0.816	O modelo explica cerca de 81% da variação dos preços reais
MAE	84.15	Erro médio absoluto em torno de R$ 84 mil
RMSE	105.98	Média dos erros quadráticos, mostrando boa precisão

Esses resultados mostram que a regressão linear conseguiu capturar as relações principais entre os atributos e o preço, sendo adequada para fins de previsão e estudo exploratório.

💡 Insights e Conclusões

O preço de um imóvel tende a crescer com metragem, localização privilegiada e número de quartos.

Variáveis como idade do imóvel e zona urbana apresentaram correlação negativa com o preço.

O modelo pode ser facilmente aprimorado com técnicas mais robustas (como Random Forest ou Gradient Boosting) ou com dados geográficos mais detalhados.

🧠 Conceitos Demonstrados

Análise Exploratória de Dados (EDA)

Engenharia de Atributos

Modelagem Preditiva com Regressão Linear

Avaliação de Modelos

Interpretação de Métricas e Visualizações

👨‍💻 Autor

Thiago Assunção Aires Moreira
🎓 Estudante de Ciência de Dados e Machine Learning – UniCEUB
📧 thiago.aires54@gmail.com

🔗 LinkedIn
