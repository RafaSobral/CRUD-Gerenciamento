# Gerenciamento de Veículos

Este projeto é um CRUD (Create, Read, Update, Delete) desenvolvido em Django para o gerenciamento de veículos. Ele permite que os usuários adicionem, visualizem, editem e excluam informações sobre veículos em uma interface amigável.

## Funcionalidades

- **Adicionar veículos:** Permite adicionar novos veículos ao sistema com informações como modelo, marca e ano.
- **Visualizar veículos:** Exibe uma lista de veículos cadastrados, com opções para visualização detalhada.
- **Editar veículos:** Permite atualizar informações de veículos existentes.
- **Excluir veículos:** Remove veículos cadastrados do sistema.
- **Pesquisa:** Barra de busca para encontrar veículos rapidamente.

## Tecnologias Utilizadas

- **Django:** Framework principal para desenvolvimento do backend e gerenciamento do banco de dados.
- **Bootstrap:** Para estilização da interface do usuário.
- **HTML/CSS:** Para criação e customização de páginas.
- **PythonAnywhere:** Para hospedagem e execução do projeto.

## Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_REPOSITORIO>
   ```

2. **Crie e ative um ambiente virtual:**

   ```bash
   python -m venv venv
   source venv/bin/activate   # No Windows: venv\Scripts\activate
   ```

3. **Instale as dependências:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Execute as migrações do banco de dados:**

   ```bash
   python manage.py migrate
   ```

5. **Inicie o servidor de desenvolvimento:**

   ```bash
   python manage.py runserver
   ```

6. **Acesse o projeto no navegador:**

   Abra o navegador e acesse [http://localhost:8000](http://localhost:8000).

## Estrutura do Projeto

```plaintext
.
├── manage.py                # Arquivo principal para execução de comandos do Django
├── app/                     # Diretório do aplicativo principal
├── templates/               # Arquivos HTML
├── static/                  # Arquivos CSS e JS
├── db.sqlite3               # Banco de dados SQLite
├── requirements.txt         # Dependências do projeto
└── README.md                # Documentação do projeto
```

