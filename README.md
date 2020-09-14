
# tdd-project

Projeto da disciplina de Teste de Software.


## Running

A step by step series of examples that tell you how to get a development env running

### Crie um ambiente virtual Python (virtualenv)

```
python3.7 -m venv virtualenv
```

### Ative seu ambiente virtual

```
source virtualenv/bin/activate
```

### Instale Geckodriver
```
brew install geckodriver
```
### Instale Django e Selenium

Com o ambiente virtual  **ativado**, instale o Django 1.11 e o Selenium:
```
(virtualenv)
pip install "django<1.12" "selenium<4"
```

### Iniciar servidor
```
python manage.py runserver
```