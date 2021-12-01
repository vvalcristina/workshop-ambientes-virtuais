# Ambientes Virtuais - pyenv

O pyenv 

### Como funciona o pyenv?

O pyenv intercepta comandos enviados ao python, e direciona para a instalação correta do python. Isso é possível devido a um arquivo .python_version no seu path. Com o pyenv é possivel instalar diversas versões do python e criar ambientes virtuais.

* PIP (Gerenciador de pacotes);
* A versão do Python utilizada (2.x ou 3.x);
* Dependências instaladas com o pip (armazenadas no diretório site-packages);
* Seu código fonte;
* Bibliotecas comuns do Python.
  
Isso faz com que as dependências sejam sempre instaladas em uma virtualenv específica, não mais no sistema operacional. A partir daí, cada projeto executa seu código-fonte utilizando sua virtualenv própria.

### Hands On

```bash
    pyenv local <numero da versão do python >
    pyenv virtualenv <nome_da_virtualenv>
    pyenv activate <nome_da_virtualenv>
    pip install -r requirements.txt
```