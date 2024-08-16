# Sistema de Tickets com Django

Este projeto é um sistema de gerenciamento de tickets desenvolvido com Django. Ele permite que os usuários criem, visualizem, editem e excluam tickets, proporcionando uma forma simples de acompanhar e gerenciar problemas ou solicitações em um sistema.

## Funcionalidades

- **Listar Tickets:** Visualize todos os tickets cadastrados no sistema.
- **Criar Tickets:** Permite a criação de novos tickets com título, descrição e status.
- **Editar Tickets:** Edite as informações de um ticket existente.
- **Excluir Tickets:** Exclua um ticket do sistema.

## Requisitos

- Python 3.x
- Django 3.x ou superior
- SQLite (ou outro banco de dados configurado)

## Configuração do Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/sistema-de-tickets.git
   cd sistema-de-tickets


## Crie um ambiente virtual 

python3 -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

## Instale as dependências

pip install -r requirements.txt

## Realize as migrações do banco de dados

python manage.py migrate

## Crie um superusuário (opcional, para acesso ao admin)

python manage.py createsuperuser

## Acesse o sistema

Abra o navegador e vá para http://127.0.0.1:8000/ para ver o sistema de tickets em ação.
