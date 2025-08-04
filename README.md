# Challenge Telecom Churn
# 📊 Telecom Churn – Análise de Evasão de Clientes
Este projeto tem como objetivo apoiar decisões estratégicas relacionadas à retenção de clientes em uma empresa de telecomunicações, por meio de uma análise exploratória de dados sobre perfil, histórico de consumo e tipos de contrato.

## 🎯 Propósito da Análise
A partir de um conjunto de dados reais, buscamos responder à seguinte pergunta:

Quais fatores contribuem para o cancelamento voluntário de clientes e como podemos antecipar o churn?

A análise foi conduzida em notebook interativo utilizando bibliotecas como pandas, seaborn e matplotlib, com apoio de técnicas de limpeza, visualização e agregação estatística.

## 📁 Estrutura do Projeto
O projeto está estruturado em torno do notebook TelecomChurn.ipynb, contendo:

Limpeza e preparação dos dados

Criação de colunas derivadas como Contas_Diarias

Análises agrupadas por churn

Visualizações para correlações e perfil do cliente

Os dados utilizados foram tratados localmente e carregados a partir de arquivos .json

## 📈 Exemplos de Gráficos e Insights Obtidos
Grafico de Pizza → mostrou a proporção de clientes que permaneceram e os que saíram.
Gráfico de Barras por tipo de contrato → mostrou que clientes com contrato mensal evadem mais.
Gráfico de histograma entre total gasto e churn → indicou que quem fica paga mais ao longo do tempo.

extra de Correlações → evidenciou que tempo de contrato tem forte relação inversa com churn.

Tabelas Agrupadas por churn → apontaram maior evasão entre idosos e clientes sem dependentes.

Essas visualizações sustentam as recomendações finais, orientando estratégias de retenção.

## ▶️ Como Executar o Notebook
Acesse o Google Colab ou ambiente local.

Faça upload do arquivo TelecomChurn.ipynb.

Instale as bibliotecas necessárias:

python
!pip install pandas matplotlib seaborn
Execute o notebook célula por célula.

Analise os gráficos gerados e consulte os insights ao final.

## 💡 Recomendação Final
Criar campanhas de retenção nos primeiros 12 meses.

Incentivar migração para contratos mais longos.

Personalizar ofertas para perfis com alto custo mensal ou idosos.

Usar alertas preditivos com base em tempo e padrão de gastos.
