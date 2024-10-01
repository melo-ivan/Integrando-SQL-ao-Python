# Sistema de Gerenciamento de Biblioteca com SQLite

Este projeto é um sistema simples de gerenciamento de biblioteca, desenvolvido em Python utilizando SQLite para armazenar informações sobre autores, livros e empréstimos.

## Estrutura do Projeto

- **Autores**: Armazena informações sobre os autores dos livros.
- **Livros**: Registra os livros disponíveis na biblioteca e seus respectivos autores.
- **Empréstimos**: Mantém um histórico de empréstimos de livros, incluindo informações de datas e usuários.

## Pré-requisitos

- Python 3.x
- SQLite3 (incluso com Python 3.x)

## Como Usar

### 1. Clone o repositório

```bash
git clone https://github.com/usuario/biblioteca-sqlite.git
cd biblioteca-sqlite

2. Instale as dependências
Não há bibliotecas externas além do SQLite e das nativas do Python. No entanto, você pode usar um ambiente virtual:
python -m venv venv
source venv/bin/activate  # Linux/MacOS
venv\Scripts\activate  # Windows

3. Execute o código
cd src
python main.py

