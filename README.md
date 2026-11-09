# 🎵 Sistema Musical — Interface Front-End

Este repositório contém a interface estática do **Sistema Musical**, desenvolvida em HTML5 e CSS3 moderno. O projeto permite a navegação entre a tela de autenticação, o painel principal, a gestão de artistas, o cadastro de músicas e a visualização da biblioteca completa de faixas.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica das páginas.
* **CSS3:** Estilização com variáveis globais (`:root`), Layout Flexbox e CSS Grid para responsividade.
* **Git:** Normalização de quebras de linha (`.gitattributes`).

---

## 📂 Estrutura do Projeto

* `.gitattributes` — Configura a detecção automática de arquivos de texto e normalização em LF.
* `login.html` — Tela de autenticação com campo de usuário, senha e caixa de dicas de acesso.
* `index.html` — Menu principal interativo com acesso aos módulos do sistema.
* `cadastro_artista.html` — Formulário de cadastro de artistas com suporte a upload de imagem e lista de artistas.
* `cadastro_musica.html` — Formulário de cadastro de faixas (com link do YouTube, letra e imagem de capa) e tabela complementar.
* `listagem_musicas.html` — Biblioteca musical com formulário de filtros e tabela detalhada das músicas.
* `styles.css` — Arquivo de estilos centralizado que atende todas as telas do sistema.

---

## 💻 Funcionalidades da Interface

* **Autenticação:** Formulário estilizado para entrada do usuário.
* **Navegação Centralizada:** Menu em *cards* para acesso rápido às funcionalidades.
* **Gestão de Artistas:** Formulário estruturado em grade de duas colunas e tabela com ações (Editar, Excluir, Músicas).
* **Gestão de Músicas:** Suporte a links do YouTube, área para inserção de letra e atalho de visualização.
* **Biblioteca & Filtros:** Interface para filtragem por busca geral, artista ou gênero musical.
* **Design Responsivo:** Adaptado para telas de celulares e computadores.

---

## 🚀 Como Executar

1. Clone ou baixe este repositório.
2. Abra qualquer um dos arquivos `.html` em um navegador web de sua preferência (recomenda-se iniciar por `login.html` ou `index.html`).
3. Para efetuar testes visuais de login, utilize as credenciais indicadas na tela (`admin` / `123`).