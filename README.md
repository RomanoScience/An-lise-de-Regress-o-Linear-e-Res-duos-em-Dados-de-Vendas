📊 Análise de Regressão Linear e Resíduos em Dados de Vendas
📈 Etapas da Análise
Este projeto aplica técnicas de regressão linear e análise de resíduos para investigar a relação entre duas variáveis quantitativas: quantidade vendida (variável independente) e preço unitário (variável dependente), utilizando bibliotecas como pandas, matplotlib, numpy e scikit-learn.

🔍 Objetivo
Avaliar se existe uma relação linear significativa entre o número de unidades vendidas e o preço unitário das vendas, utilizando análise estatística e visualização gráfica.

📁 Etapas Realizadas
1. Carregamento do Dataset
Leitura do arquivo CSV contendo dados fictícios de vendas, com foco nas colunas Quantidade e Preço Unitário.

2. Aplicação da Regressão Linear
Utilização da classe LinearRegression da biblioteca scikit-learn para ajustar uma reta de tendência no formato 
y=ax+b, onde x representa a quantidade e y o preço unitário.

3. Visualização Gráfica
📉 Gráfico de Regressão Linear
Pontos azuis: dados reais (quantidade vs. preço).

Linha vermelha: reta ajustada pelo modelo de regressão.


Link das imagens geradas
https://github.com/RomanoScience/Analise-estatistica-de-dados/blob/main/Regrassao_linear_%26_residual.png


🧐 Interpretação:
O gráfico mostra que os dados estão bastante dispersos em torno da reta, o que indica que o preço unitário não depende fortemente da quantidade vendida.
Apesar disso, há uma leve inclinação positiva na linha de regressão, sugerindo uma tendência crescente fraca entre essas variáveis.

📊 Gráfico de Resíduos do Modelo
Pontos azuis: resíduos (diferença entre valor real e valor previsto).

Linha preta tracejada: linha base no valor zero.

🧠 Interpretação:
Os resíduos estão simetricamente espalhados em torno de zero, sem apresentar padrão de superestimação ou subestimação, o que é desejável em uma regressão.
Contudo, como os dados continuam altamente dispersos, isso reforça que a tendência linear é fraca, e que o modelo de regressão linear pode não ser o mais adequado para prever o preço unitário com base na quantidade.

🧮 Cálculo Estatístico
Desvio padrão dos resíduos: calculado para medir o quão distantes os dados estão da reta ajustada.

Um valor elevado do desvio padrão indica grande variação dos dados em torno da previsão do modelo.

📷 Exemplos de Gráficos Gerados
Regressão Linear	Resíduos do Modelo

👨‍🎓 Sobre o Autor
Sou formado recentemente em Engenharia Elétrica pela UNESP e estou buscando uma oportunidade na área de Dados.
Tenho me dedicado a projetos práticos com foco em análise exploratória, estatística e programação com Python.

📬 Contato
https://www.linkedin.com/in/ronaldoromanojr/ • https://github.com/RomanoScience 
