## Projeto API Adote um Pet

Desenvolvido no curso multi-stack da treinaweb

### Instalando o projeto

#### Clonar o repositório

```
git clone https://github.com/elisalvsan/adote-um-pet-python.git
```

#### Criar e ativar ambiente virtual

```
python3 -m venv .venv
source .venv/bin/activate
```

#### Instalar as depencências

```
pip install -r requirements.txt
```

#### Criar a estrutura no banco de dados

```
python manage.py migrate
```

#### Iniciar o servidor de desenvolvimento

```
python manage.py runserver
```