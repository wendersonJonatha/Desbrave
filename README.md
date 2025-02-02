# Desbrave


Bem-vindo ao repositório oficial da plataforma **Desbrave**! 🚀

## 📝 Descrição do Projeto
O **Desbrave** é uma plataforma digital interativa que combina:
- **Cursos gratuitos** focados em cultura local, cidadania digital e tecnologia.
- **Fóruns de discussão** para jovens compartilharem ideias e aprenderem uns com os outros.

Nosso objetivo é conectar jovens de 13 a 25 anos à cultura e à educação digital, reduzindo a exclusão digital em Recife e fortalecendo o patrimônio cultural da cidade.

---

## 🎯 Apresentando o Problema
Recife é uma cidade rica em cultura e história, mas muitos jovens estão desconectados desse patrimônio. Além disso, com o aumento dos desafios digitais, como a desinformação e a falta de orientação sobre cidadania online, há uma lacuna que precisa ser preenchida.

Os jovens precisam de um espaço que seja:
- **Interativo**: Para engajá-los de forma dinâmica e participativa.
- **Acessível**: Disponível em qualquer dispositivo e para todos os públicos.
- **Educativo**: Que ofereça conhecimento prático sobre cultura local, cidadania digital e tecnologia.

É isso que o **Desbrave** oferece: uma plataforma completa para conectar jovens à cultura, à educação e ao futuro.

---

## 🛠️ Tecnologias Utilizadas
- **Front-end**: HTML, CSS, JavaScript.
- **Back-end**: Java com Spring Boot.
- **Banco de Dados**: MySQL.
- **Infraestrutura**: Docker.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
- Docker instalado.
- Git instalado.

### Passos para Execução
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/Desbrave.git
   cd Desbrave

2- Inicie os contêineres com Docker Compose:

bash
Copy
docker-compose up --build

3-Acesse a aplicação:

Front-end: http://localhost:8080

Back-end (API): http://localhost:8081

📂 Estrutura do Projeto
Copy
Desbrave/
├── src/                        # Código-fonte da aplicação
│   ├── frontend/               # Front-end (HTML, CSS, JavaScript)
│   │   ├── assets/             # Imagens, ícones, fonts
│   │   ├── css/                # Arquivos CSS
│   │   ├── js/                 # Arquivos JavaScript
│   │   ├── index.html          # Página inicial
│   │   ├── login.html          # Página de login
│   │   ├── register.html       # Página de cadastro
│   │   ├── forum.html          # Tela de fóruns
│   │   ├── courses.html        # Tela de cursos
│   │   └── dashboard.html      # Dashboard do usuário
│   │
│   └── backend/                # Back-end (Java Spring Boot)
│       ├── src/
│       │   ├── main/
│       │   │   ├── java/com/desbrave/
│       │   │   │   ├── controller/  # Controladores REST
│       │   │   │   ├── service/     # Lógica de negócio
│       │   │   │   ├── repository/  # Repositórios do banco de dados
│       │   │   │   └── model/       # Entidades do banco de dados
│       │   │   └── resources/
│       │   │       ├── application.properties  # Configurações do Spring Boot
│       │   │       └── static/      # Arquivos estáticos (opcional)
│       │   └── test/                # Testes unitários
│       └── Dockerfile              # Configuração do Docker
│
├── database/                  # Scripts do banco de dados
│   ├── schema.sql             # Script de criação do banco de dados
│   └── data.sql               # Dados iniciais (opcional)
│
├── docker-compose.yml         # Configuração do Docker Compose
├── README.md                  # Documentação do projeto
└── .gitignore                 # Arquivos ignorados pelo Git

🧩 Funcionalidades:

1.Cadastro e Login: Autenticação segura para usuários.
2.Fóruns: Espaço seguro para discussões e interações.
3.Cursos: Cursos gratuitos com vídeos, textos e quizzes.
4.Dashboard do Usuário: Área personalizada com progresso e métricas.

🤝 Como Contribuir
1. Faça um fork do repositório.

2.Crie uma branch para sua feature:
bash
Copy
git checkout -b minha-feature

3- Commit suas alterações:
bash
Copy
git commit -m "Adicionei uma nova funcionalidade"

4- Envie para o repositório remoto:
bash
Copy
git push origin minha-feature

5. Abra um Pull Request.


📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

🙌 Agradecimentos
Agradecemos a todos que contribuíram para o desenvolvimento do Desbrave!
