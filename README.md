# Projeto de Previsão de Preços de Carros Usados

## Visão Geral

Este projeto visa a criação de um modelo preditivo para preços de carros usados. Este projeto foi concebido em resposta à dificuldade enfrentada por uma empresa de revenda de carros usados na precificação competitiva de seu catálogo. Utilizando um conjunto de dados fornecido pelo marketplace, pretendemos analisar o mercado nacional de carros usados e criar um modelo que ajude nosso cliente a precificar seus carros de acordo com o mercado.

## Conjuntos de Dados

Dois conjuntos de dados foram fornecidos:

1. `cars_training`: Composto por 29584 linhas e 28 colunas de informação (features), incluindo a variável alvo 'preco'.

2. `cars_test`: Composto por 9862 linhas e 28 colunas. Este conjunto de dados não inclui a variável alvo 'preco'. 

Nosso objetivo é prever os preços dos carros no conjunto de dados `cars_test`.

## Entregáveis

Os pontos 1, 2 e 3 abaixo estão em um jupyter notebook neste repositório com o nome 'LH_CD_EDUARDOALVARENGA.ipynb'.

O ponto entregável 4 está neste repositório com o nome 'predicted.csv'

1. Análise das principais estatísticas da base de dados, incluindo gráficos descritivos e interpretações.

2. Análise exploratória de dados (EDA) incluindo a formulação e resposta a 3 hipóteses de negócio, e respostas às seguintes perguntas de negócio:

    - Qual o melhor estado cadastrado na base de dados para se vender um carro de marca popular e por quê?
    
    - Qual o melhor estado para se comprar uma picape com transmissão automática e por quê?
    
    - Qual o melhor estado para se comprar carros que ainda estejam dentro da garantia de fábrica e por quê?
  
    - Hipótese 1: Carros com transmissão automática são mais caros do que carros com uma transmissão manual.
  
    - Hipótese 2: Carros de único dono são mais caros do que carros que tiveram mais de um dono.
  
    - Hipótese 3: Carros ainda dentro da garantia de fábrica são mais caros do que carros fora da garantia.

3. Descrição do processo de criação do modelo de previsão de preços, incluindo as variáveis escolhidas, transformações de variáveis, o tipo de problema de aprendizado de máquina (regressão ou classificação), o modelo escolhido e as razões para essas escolhas. 

4. O resultado final do modelo em uma planilha chamada 'predicted.csv', contendo duas colunas: 'id' e 'preco'.

## Como Instalar e Executar o Projeto

É necessário possuir Python e Jupyter Notebook para rodar o projeto, ou então utilizar de ferramentas como o Google Colab

1. Clone o repositório do GitHub para sua máquina local. 

```bash
git clone https://github.com/eduardosalvarenga/LH_CD_EDUARDOALVARENGA/tree/main
```
2. Navegue até o diretório do projeto
```
cd LH_CD_EDUARDOALVARENGA
```
3. Instale as dependências necessárias usando:
```
pip install -r requirements.txt
```
4. Abra o Jupyter Notebook para visualizar e executar o projeto.

