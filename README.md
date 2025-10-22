# InvestHelper 📈
Um programa em Python para auxiliar investidores a encontrar ações compatíveis com seu perfil de investimento.

## 🎯 Sobre o Projeto
Muitos investidores, especialmente os iniciantes, enfrentam o desafio de escolher ações na bolsa que se alinhem com seu perfil de risco e objetivos financeiros. A insegurança ao tomar decisões pode levar a escolhas que resultam em perdas.

O InvestHelper foi criado para abordar esse problema, oferecendo sugestões de ações baseadas em um perfil de investimento definido pelo próprio usuário.

## ✨ Como Funciona
Definição do Perfil: O usuário define seu perfil de investidor informando suas preferências para três características principais:

Risco: O quão disposto está a correr riscos (0.0 a 1.0, sendo 1.0 o mais alto).

Retorno Esperado: Qual o nível de retorno desejado (0.0 a 1.0, sendo 1.0 o mais alto).

Liquidez: A importância da facilidade de comprar/vender a ação (0.0 a 1.0, sendo 1.0 a mais alta).

Seleção de Ações: O usuário informa os códigos (tickers) das ações que tem interesse em analisar (separados por vírgula). Essas ações também possuem classificações para Risco, Retorno e Liquidez (armazenadas no arquivo acoes.txt).

Cálculo de Compatibilidade: O programa calcula o quão "próximas" as características de cada ação selecionada estão do perfil definido pelo usuário.

Resultado: É exibida uma lista das ações de interesse, ordenadas pela compatibilidade com o perfil do usuário (em porcentagem). Um gráfico 3D também é gerado para visualizar a relação entre o perfil do usuário e as ações selecionadas nessas três dimensões (Risco, Retorno, Liquidez).

## 🛠️ Tecnologias Utilizadas
Linguagem: Python 3

Bibliotecas Principais:

NumPy (numpy): Para cálculos numéricos.

Matplotlib (matplotlib): Para a geração do gráfico 3D.
