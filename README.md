<<<<<<< HEAD
# shopping2
Teste django

# Shopping Django Project

Este projeto é um projeto Django configurado para usar PostgreSQL como banco de dados.

## Como rodar o projeto

1. Crie um banco de dados PostgreSQL chamado `shoppingdb` e um usuário `postgres` com senha `postgres` (ou ajuste as credenciais em `shopping/settings.py`).
2. Ative o ambiente virtual:
   ```bash
   source venv/bin/activate
   ```
3. Instale as dependências (se necessário):
   ```bash
   pip install -r requirements.txt
   ```
4. Rode as migrações:
   ```bash
   python manage.py migrate
   ```
5. Inicie o servidor:
   ```bash
   python manage.py runserver
   ```

## Dependências principais
- Django
- psycopg2-binary

