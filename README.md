# ChatPG

**ChatPG** é um aplicativo web de chat desenvolvido com Django. Este projeto permite que usuários autenticados criem salas de chat e conversem em tempo real com outros usuários.

## Funcionalidades

- **Autenticação de Usuários**: Apenas usuários autenticados podem acessar as funcionalidades de chat.
- **Criação de Salas**: Usuários podem criar salas de chat personalizadas.
- **Mensagens em Tempo Real**: Usuários podem enviar e receber mensagens em tempo real dentro das salas.

## Tecnologias Utilizadas

- **Django**: Framework web de alto nível para o backend.
- **Django Channels**: Para habilitar comunicação em tempo real via WebSockets.
- **HTML/CSS/JavaScript**: Para o frontend.

## Como Começar

### Pré-requisitos

- Python 3.7+
- pip (gerenciador de pacotes do Python)
- Virtualenv (recomendado)

### Instalação

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/chatPG.git
   cd chatPG

2. Crie e ative um ambiente virtual:

   ```sh
   python -m venv .venv
   source .venv/bin/activate   # No Windows, use `.venv\Scripts\activate`

3. Instale as dependências:

   ```sh
   pip install -r requirements.txt

4. Aplique as migrações:

   ```sh
   python manage.py migrate

5. Crie um superusuário para acessar o painel de administração:

   ```sh
   python manage.py createsuperuser

6. Execute o servidor de desenvolvimento:

   ```sh
   python manage.py runserver
