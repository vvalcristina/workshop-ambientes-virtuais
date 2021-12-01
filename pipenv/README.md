## Gerenciador de pacotes - Pipenv 

O pipenv cria e gerencia ambientes virtuais além de instalar e desinstalar bibliotecas, para isso ele utliza um arquivo Pipfile e Pipfile.lock que é utilizado para produzir instalações deterministicas. Além de conseguir separar dependencias em grupo por ex: dev (dependencias apenas em ambiente de dev)

### Hands On

```bash
   pip install pipenv
   pipenv install pandas
   pipenv install pytest --dev
```