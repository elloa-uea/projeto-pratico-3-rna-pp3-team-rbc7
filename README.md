# rna-20201
Projeto Prático 3

## Configurando o ambiente
## Acesse a pasta notebooks
### Instale o conda
[Site para instalação](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)

Pode instalar o anaconda ou miniconda.

### Importe o ambiente padrão
Basta executar o seguinte comando no dir src do repositório.

    conda env create -f environment.yml

Para testar a instalação execute os comandos:

    conda activate pp3

### Utilizando o Jupyter-lab
Para habilitar o env como um kernel do Jupyter, basta executar:

    python -m ipykernel install --user --name pp3 --display-name "Python (pp3)"

Abra o jupyter-lab (so precisa escrever jupyter-lab no console), ele vai abrir o seu navegador padrão. 
