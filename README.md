# 🎬 FakerFlix - Um Sistema de Filmes

Bem-vindo ao **FakerFlix**! Um sistema de gerenciamento de filmes criado com Django, projetado para fornecer uma experiência completa de visualização e pesquisa de filmes.

## 🚀 Funcionalidades

- **Página Inicial**: Navegue pelas últimas adições e destaques.
- **Lista de Filmes**: Veja todos os filmes disponíveis com filtros e opções de pesquisa.
- **Detalhes do Filme**: Visualize detalhes completos sobre cada filme.
- **Criação de Conta e Login**: Crie uma conta e faça login para acessar funcionalidades personalizadas.
- **Perfil do Usuário**: Edite suas informações de perfil e altere sua senha.
- **Pesquisa Avançada**: Encontre filmes usando termos específicos.

## 📦 Requisitos

- Python 3.10+
- Django 5.1.1
- [Bootstrap 5](https://getbootstrap.com) para estilização

## 🔧 Instalação

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/thaleson/fakerflix.git
   cd fakerflix
   ```

2. **Crie um Ambiente Virtual**

   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`
   ```

3. **Instale as Dependências**

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure o Banco de Dados**

   ```bash
   python manage.py migrate
   ```

5. **Crie um Superusuário**

   ```bash
   python manage.py createsuperuser
   ```

6. **Inicie o Servidor**

   ```bash
   python manage.py runserver
   ```

   Acesse o projeto em `http://127.0.0.1:8000/`

## 📂 Estrutura do Projeto

- `filme/`: Aplicação principal com modelos, visualizações e URLs.
- `templates/`: Templates HTML usados para renderizar as páginas.
- `static/`: Arquivos estáticos como CSS e imagens.
- `requirements.txt`: Lista de dependências do projeto.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🛠️ Contribuições

Contribuições são bem-vindas! Se você tem sugestões ou melhorias, por favor, envie um pull request ou abra uma issue.


