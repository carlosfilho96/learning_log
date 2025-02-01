# Comandos utilizados

## Ambiente virtual
```python -m venv ll_env```

## Ativar ambiente virtual
```.\ll_env\Scripts\activate```

## Instalação do Django no ambiente virtual
```pip install Django```

## Atualização do pip
```python.exe -m pip install --upgrade pip```

## Iniciar um novo projeto
```django-admin startproject learning_log .```

## Criar o banco de dados
```python .\manage.py migrate```

## Executar projeto
```python .\manage.py runserver```

## Criar um aplicativo para o projeto
```python .\manage.py startapp learning_logs```

## Criar novas migrations para o aplicativo adicionado
```python .\manage.py makemigrations learning_apps```