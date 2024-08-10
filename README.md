Fiz um projeto  cujo objetivo era criar um projeto autoral guiado por IAs generativas.
Decidi escolher o Copilot  para efetuar esse projeto usei  um dataset fornecido pela DIO em um outro projeto de machine learning.
para efetuar esse projeto usei a ferramenta Orange 3


Meu prompt:

Preciso da sua ajuda para me guiar em um projeto de machine learning no orange 3 vou te enviar o guia passo a passo: Nível de conhecimento: Qual o seu nível de conhecimento em machine learning e programação? Nível intermediario : conheço um pouco de estrutura de dados em Python e conheço a biblioteca Scikit-learn
Dados disponíveis: Que tipo de dados você possui ou pretende coletar : possuo o seguinte dataset :https://docs.google.com/spreadsheets/d/14gsS8h0-wgtoSKdmexTgN4XvyV1q1Vh3HZ4xetRXNCs/edit
Objetivo específico da previsão: Qual o nível de precisão desejado? Você busca prever a demanda de um único produto, de uma categoria inteira ou de todo o estoque? vou importar o dataset que você


Configure as variáveis de entrada e saída de acordo com os dados.
Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.
3. Analisar
Após o treinamento, examine as métricas de performance do modelo.
Verifique as principais características que influenciam as previsões.
Faça ajustes no modelo, se necessário, e re-treine até obter um desempenho satisfatório.
4. Prever
Use o modelo treinado para fazer previsões de estoque.
Exporte os resultados e analise as previsões geradas.
Documente suas conclusões e qualquer insight obtido a partir das previsões.
Recursos computacionais: Que tipo de infraestrutura você tem disponível (computador pessoal usarei um o orange 3 app pois preciso terminar rápido esse projeto






Resposta do Copilot:
 
Configuração no Orange 3

1. Importar o Dataset:
Abra o Orange 3.

Use o widget File para carregar o dataset do GitHub. Você pode baixar o arquivo CSV e carregá-lo diretamente.
2. Configurar Variáveis de Entrada e Saída:
        Use o widget Select Columns para definir suas variáveis de entrada (features) e a variável de saída (target). No seu caso, a variável de saída será a demanda de estoque.
Pré-processamento dos Dados:
Utilize widgets como Preprocess para normalizar ou padronizar os dados, se necessário.

3. Treinamento do Modelo
Escolher o Modelo:
Use o widget Model para selecionar o algoritmo de machine learning. Como você está familiarizado com Scikit-learn, pode escolher modelos como Random Forest, Linear Regression, ou k-Nearest Neighbors.

Treinar o Modelo:
Conecte o widget Model ao widget Test & Score para avaliar a performance do modelo.
Inicie o treinamento. Isso pode levar algum tempo, dependendo do tamanho do dataset.


4. Análise
Examine as Métricas de Performance:
Use o widget Test & Score para visualizar métricas como acurácia, precisão, recall, e F1-score.
Verifique as Características Importantes:
Utilize o widget Rank para identificar as características mais influentes nas previsões.
Ajustes e Re-treinamento:
Se necessário, ajuste os hiperparâmetros do modelo usando o widget Hyperparameter Tuning e re-treine o modelo até obter um desempenho satisfatório.


5. Previsão
Fazer Previsões:
Use o widget Predictions para aplicar o modelo treinado e fazer previsões sobre novos dados de estoque.
Exportar Resultados:
Exporte os resultados usando o widget Save e analise as previsões geradas.
Documentação:
Documente suas conclusões e insights obtidos a partir das previsões.
