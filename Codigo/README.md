# Código do Projeto

Mantenha neste diretório os notebooks, scripts e demais arquivos necessários para reproduzir a análise de dados, o treinamento/avaliação de modelos, o pipeline ou o sistema desenvolvido pela equipe.

Cada equipe deve organizar esta pasta conforme a natureza e o estágio do projeto — um projeto de análise exploratória pode precisar só de alguns notebooks; um projeto que também envolve construir uma aplicação ou API em torno do modelo pode separar notebooks de código reutilizável (ex.: `/notebooks` e `/src`).

## Notebooks

* Numere os notebooks na ordem em que devem ser executados (ex.: `01_coleta_e_exploracao.ipynb`, `02_pre_processamento.ipynb`, `03_modelagem.ipynb`, `04_avaliacao.ipynb`).
* **Não limpe os outputs antes de commitar.** Os notebooks devem ser versionados já executados, com as saídas (gráficos, métricas, tabelas) visíveis, para que seja possível avaliar os resultados sem precisar executar o notebook novamente.
* Reexecute o notebook do início ao fim antes de cada entrega, para garantir que os outputs commitados correspondem à versão atual do código.

## Ambiente e reprodutibilidade

Declare as dependências do projeto (ex.: `requirements.txt`, `environment.yml` ou `pyproject.toml`) para que outra pessoa consiga recriar o ambiente e reproduzir os resultados.

Descreva neste arquivo:

* Estrutura de diretórios e arquivos adotada pela equipe.
* Linguagens, bibliotecas e ferramentas utilizadas.
* Como instalar as dependências e executar notebooks/scripts.
* Como obter ou preparar os dados (ou aponte para `/Dados`).
