# Ambientes Virtuais - Virtualenv

Um ambiente virtual empacota todas as dependências que um projeto precisa e armazena em um diretório, fazendo com que nenhum pacote seja instalado diretamente no sistema operacional. Sendo assim, cada projeto pode possuir seu próprio ambiente e, consequentemente, suas bibliotecas em versões específicas.

### Como funciona uma virtualenv?

O funcionamento de uma virtualenv é bem simples. Basicamente, uma cópia dos diretórios necessários para que um programa Python seja executado é criada, incluindo:

* PIP (Gerenciador de pacotes);
* A versão do Python utilizada (2.x ou 3.x);
* Dependências instaladas com o pip (armazenadas no diretório site-packages);
* Seu código fonte;
* Bibliotecas comuns do Python.
  
Isso faz com que as dependências sejam sempre instaladas em uma virtualenv específica, não mais no sistema operacional. A partir daí, cada projeto executa seu código-fonte utilizando sua virtualenv própria.

### Hands On

```bash
    pip install virtualenv
    virtualenv <nome_da_virtualenv>
    source  <nome_da_virtualenv>/bin/activate
```