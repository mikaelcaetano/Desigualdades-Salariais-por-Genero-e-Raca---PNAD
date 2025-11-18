📄 README — Análise Interseccional de Desigualdades Salariais no Brasil
Desigualdades Salariais no Brasil: Uma Análise Interseccional de Gênero, Raça e Escolaridade

Autor: Mikael Silva Caetano
Data: 2025
Linguagem: Python
Base de Dados: PNAD Contínua – IBGE (2º trimestre/2025)

📌 Descrição do Projeto

Este repositório apresenta uma análise exploratória e comparativa sobre desigualdades salariais no Brasil, considerando gênero, raça/cor e escolaridade, com abordagem interseccional.
O objetivo é investigar se a educação reduz diferenças históricas ou se as desigualdades persistem mesmo entre indivíduos com níveis educacionais semelhantes.

O projeto foi desenvolvido como parte de um processo de seleção de pesquisa aplicado ao contexto de políticas públicas, desigualdades sociais e mercado de trabalho.

🎯 Pergunta de Pesquisa

Em que medida a escolaridade modera os efeitos das desigualdades de gênero e raça sobre os rendimentos do trabalho no Brasil?

🧩 Hipóteses Testadas
Código	Hipótese resumida
H1	Homens têm rendimentos superiores às mulheres, mesmo com escolaridade igual
H2	Pessoas brancas ganham mais do que pessoas pretas e pardas
H3	Mulheres negras compõem o grupo mais vulnerável e com menor retorno à educação
H4	O prêmio da educação é maior entre homens e brancos
🛠 Ferramentas Utilizadas
Linguagem

Python 3.10+

Bibliotecas principais - Python
pandas
numpy
matplotlib
seaborn
pnadcIBGE (ou pnadc / pnadium equivalente)
scikit-learn (opcional)
statsmodels (opcional)

🔍 Metodologia Resumida

Coleta dos microdados via pacote pnadcIBGE ou loading local (não incluído aqui).

Filtragem de amostra:

idade entre 18 e 64 anos

apenas ocupados

renda válida > 0

Recodificação de variáveis categóricas

Cálculo de estatísticas descritivas

Visualizações analíticas

(Opcional) Modelagem econométrica com log-salário e interações

📊 Principais Visualizações (a serem incluídas)

Renda média por sexo, raça e escolaridade

Heatmap interseccional

Boxplot por distribuição de renda

Índice de Gini por grupo

Os gráficos finais devem ser salvos em /outputs/graficos/.

⚠️ Nota sobre dados do IBGE

Este repositório não inclui microdados da PNAD Contínua por questões legais.
Para executar o projeto, consulte:
🔗 https://www.ibge.gov.br/estatisticas/sociais/trabalho/9171-pnad-continua.html

📌 Reprodutibilidade

Antes de rodar o notebook, instale as dependências:

pip install -r requirements.txt


Ou individualmente:

pip install pandas numpy matplotlib seaborn

📜 Licença

Este projeto é educacional e acadêmico, sem fins comerciais.
Conteúdos derivados da PNAD seguem licença e normas do IBGE.
