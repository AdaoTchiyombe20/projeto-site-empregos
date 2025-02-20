# Projeto Site de Empregos

## Descrição
Este é um projeto de uma plataforma de empregos desenvolvida com **PHP, MySQL, HTML, CSS e JavaScript**. O objetivo é conectar candidatos a oportunidades de emprego de forma eficiente.

## Tecnologias Utilizadas
- **PHP** (Back-end)
- **MySQL** (Banco de dados)
- **HTML, CSS e JavaScript** (Front-end)
- **Composer** (Gerenciador de dependências PHP)

## Estrutura do Projeto
```
projeto-site-empregos/
│── public/ (Arquivos acessíveis ao usuário)
│── src/ (Código do servidor)
│── assets/ (Recursos estáticos)
│── db/ (Banco de dados)
│── .gitignore
│── README.md
│── composer.json
```

## Como Configurar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-site-empregos.git
   ```
2. Instale as dependências:
   ```bash
   composer install
   ```
3. Configure o banco de dados em `src/config/database.php`.
4. Inicie o servidor local:
   ```bash
   php -S localhost:8000 -t public
   ```

## Funcionalidades Principais
- Cadastro e login de usuários
- Empresas podem postar vagas
- Candidatos podem se candidatar às vagas
- Pesquisa e filtros de vagas

## Contribuição
Sinta-se à vontade para contribuir! Faça um **fork**, crie uma **branch**, implemente sua melhoria e envie um **pull request**.

## Licença
Este projeto está sob a licença MIT.

