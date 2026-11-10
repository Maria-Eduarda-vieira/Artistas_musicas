<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=4169E1&width=435&lines=Sistema+Musical+em+PHP+com+Banco+de+Dados" alt="Typing SVG" />

<br>

<p align="center">
  <b>🏫 SENAI A. Jacob Lafer</b> • Curso Técnico em Desenvolvimento de Sistemas<br>
  <b>📚 Disciplina:</b> Programação Backend integrado com Banco de Dados
</p>

</div>

---

### 📌 Sobre a Atividade

Nesta etapa do projeto **Artistas e Músicas (Fase 2)**, transformamos as páginas estáticas em HTML5 desenvolvidas na disciplina de LIMA em um **sistema web dinâmico**. Utilizando **PHP** e **MySQL**, o sistema gerencia cadastro, edição, exclusão e visualização de artistas e músicas, além de contar com autenticação segura via sessão e upload com redimensionamento de imagens.

---

### 👩‍💻 Informações da Atividade

- **Autora:** Maria Eduarda Vieira
- **Turma:** 1ID-DS
- **Data Início:** 28/09/2026
- **Data de Finalização:** 29/09/2026
- **Instituição:** SENAI A. Jacob Lafer

---

### 🛠️ Ferramentas Utilizadas

| Ferramenta | Aplicação no Projeto |
| :--- | :--- |
| **HTML5 & CSS** | Estruturação da interface gráfica e estilização em modo Dark. |
| **PHP .** | Processamento de dados no backend, controle de sessão (`$_SESSION`) e validação de formulários. |
| **MySQLi** | Banco de Dados Relacional` |
| **Biblioteca GD (PHP)** | Redimensionamento automático de imagens (fotos de artistas e capas de álbuns). |
| **MySQL Workbench / phpMyAdmin** |Conexão com o banco de dados `sistema_musical_v2. |
| **Visual Studio Code** | Ambiente de Desenvolvimento Integrado (IDE) utilizado no projeto. |

---



### 📂 Conteúdo do Portfólio

| Módulo / Página | Recursos e Conteúdo |
| :--- | :--- |
| **Autenticação (`login.php`)** | Tela de login protegida com criptografia Bcrypt (`password_verify`) e controle de sessão. |
| **Menu Principal (`index.php`)** | Painel principal que exibe a saudação ao usuário logado ("Olá, admin!") e atalhos para os módulos. |
| **Gerenciar Artistas (`cadastro_artista.php`)** | Formulário de cadastro/edição (CRUD completo) de artistas com upload de foto e validação. |
| **Cadastrar Músicas (`cadastro_musica.php`)** | Vínculo de músicas ao artista (chave estrangeira), cadastro de álbum, letra, capa e link do YouTube. |
| **Biblioteca Musical (`listagem_musicas.php`)** | Consulta interativa com filtros combinados (busca geral, por artista e por gênero) e integração com YouTube. |

---

### 🎯 Objetivos Concluídos

- [x] Capturar e validar requisições enviadas via método **POST** e **GET**.
- [x] Construir uma interface interativa com suporte a upload de arquivos (`enctype="multipart/form-data"`).
- [x] Validar credenciais no backend garantindo segurança contra SQL Injection via **Prepared Statements** e senhas criptografadas com **Bcrypt**.
- [x] Implementar **Sessões no PHP** (`session_start`).
- [x] Estabelecer a conexão via extensão **MySQLi** e realizar o CRUD completo (`SELECT`, `INSERT`, `UPDATE`, `DELETE`) com tratamento de chaves estrangeiras.
- [x] Manipular imagens no servidor utilizando a biblioteca **GD** para redimensionamento automático.

---

### 💡 Como me ajudou:

> Compreendi na prática a evolução de um frontend estático para uma aplicação backend dinâmica e conectada ao Banco de Dados. Aprendi a importância da validação de formulários, do controle de rotas por sessão, do gerenciamento seguro de arquivos enviados pelo usuário e da integridade referencial entre tabelas relacionais no MySQL.

---
