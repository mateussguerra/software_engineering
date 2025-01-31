# Gerenciador de Tarefas - API RESTful

Este projeto é uma API RESTful para gerenciamento de tarefas, desenvolvida em **Django** e **Django REST Framework**. A API permite criar, ler, atualizar e excluir tarefas, além de filtrar tarefas por status.

## Funcionalidades

- **Criar uma tarefa**: Adicione uma nova tarefa com título, descrição, status e data de vencimento.
- **Listar todas as tarefas**: Obtenha uma lista de todas as tarefas cadastradas.
- **Buscar uma tarefa por ID**: Acesse os detalhes de uma tarefa específica.
- **Atualizar uma tarefa**: Modifique os dados de uma tarefa existente.
- **Excluir uma tarefa**: Remova uma tarefa do sistema.
- **Filtrar tarefas por status**: Liste tarefas com base no status ("pendente", "realizando", "concluída").

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Framework**: Django e Django REST Framework
- **Banco de Dados**: SQLite (padrão do Django)
- **Ferramentas**: Postman/Insomnia para testes de API

## Como Executar o Projeto

Siga os passos abaixo para configurar e executar o projeto localmente.

### Pré-requisitos

- Python 3.x instalado.
- Pip (gerenciador de pacotes do Python).

### Passos

1. **Clone o repositório**:
   git clone https://github.com/mateussguerra/software_engineering.git
   cd software_engineering

2. **Crie um ambiente virtual (opcional, mas recomendado)**:
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

3. **Instale as dependências**:
pip install -r requirements.txt

5. **Execute as migrações**:
python manage.py migrate

7. **Inicie o servidor de desenvolvimento**:
python manage.py runserver

8. **Acesse a API**:
O servidor estará rodando em http://127.0.0.1:8000/.
Use o Postman ou Insomnia para testar os endpoints.


Feito com ❤️ por Seu Nome
