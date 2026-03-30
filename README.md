# Learning Log

Aplicativo web desenvolvido com Django para que estudantes anotem seus resumos e tópicos importantes sobre seus estudos. Uma plataforma pessoal para registrar e organizar o aprendizado.

## Funcionalidades

- **Tópicos**: Criar e visualizar tópicos de estudo
- **Entradas**: Adicionar anotações detalhadas em cada tópico
- **Edição**: Editar suas anotações e tópicos
- **Autenticação**: Sistema de login e registro de usuários
- **Restrição de Privacidade**: Cada usuário só visualiza seus próprios tópicos. Tópicos não são visíveis para usuários não logados

## Requisitos

- Python 3.x
- Django
- SQLite (padrão)

## Instalação e Uso

1. Ative o ambiente virtual:
```bash
ll_env\Scripts\activate
```

2. Inicie o servidor:
```bash
python manage.py runserver
```

3. Acesse em `http://localhost:8000`

4. Crie uma conta e comece a anotar seus tópicos

## Estrutura do Projeto

- `learning_logs/`: App principal com modelos, views e templates
- `users/`: App de autenticação (login/registro)
- `templates/`: Templates HTML do projeto
- `db.sqlite3`: Banco de dados SQLite