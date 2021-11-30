## Gerenciador de pacotes - Conda

O conda se trata de um gerenciador de pacotes, dependências e ambientes, totalmente Open Source, desenvolvido em Python e disponível para Windows, Linux e MacOSX. Com ele é possível criar, manipular e alternar de ambientes de forma extremamente fácil.

Por mais que seja muito utilizado em conjunto com o Anaconda, uma plataforma Python/R para desenvolvimento de aplicações de data science e machine learning, o conda pode ser utilizado para gerenciamento de ambientes para as mais diversas linguagens de programação.

Em outras palavras, independentemente de onde você criar seu ambiente (Window, Linux, MacOSX), no final você vai conseguir replicar esse ambiente com as mesmas características, pois o conda é que ficará responsável por instalar os pacotes necessários para a sua aplicação.

### Hands On

* Vamos utilizar o [Miniconda](https://docs.conda.io/en/latest/miniconda.html), uma versão reduzida do Anaconda. É necessário fazer download da extensão.


```bash
    chmod +x Miniconda2-latest-Linux-x86_64.sh
    ./Miniconda2-latest-Linux-x86_64.sh
    conda --version
```

* Criando o ambiente:


```bash
   conda create --name  <ambiente_conda>
```

* Ativando o ambiente:

```bash
   conda activate <ambiente_conda>
```