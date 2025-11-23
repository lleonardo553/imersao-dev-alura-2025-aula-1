# 📚 Book Search

## Buscador de Livros com a Google Books API

Projeto desenvolvido durante a **Imersão Dev com Alura e Google**, focado na integração e consumo de dados de APIs externas para criar uma aplicação prática de busca de informações.

O **Book Search** é uma ferramenta simples e intuitiva que permite aos usuários pesquisar títulos de livros e obter detalhes básicos (como nome e autor) diretamente da base de dados do Google.

---

## ✨ Tecnologias Utilizadas

* **HTML5:** Estrutura básica da aplicação.
* **CSS3:** Estilização e layout.
* **JavaScript (Vanilla JS):** Lógica principal, manipulação do DOM e requisições assíncronas.
* **Google Books API:** Fonte de dados para a busca e recuperação de informações dos livros.

---

## 🚀 Como Funciona

1.  O usuário digita o nome de um livro no campo de busca.
2.  A aplicação utiliza JavaScript para fazer uma requisição (`GET`) assíncrona para a API do Google Livros.
3.  A API retorna um objeto JSON com os resultados correspondentes.
4.  O JavaScript processa e extrai informações relevantes (título, autor, etc.).
5.  Os resultados são exibidos dinamicamente na tela para o usuário.

---

## 🔗 Acessar o Projeto

Você pode ver a aplicação funcionando diretamente no Google Sites.

* **Demonstração Online (Google Sites):**
    [https://sites.google.com/view/imersaodevalura2025aula1/aula-1](https://sites.google.com/view/imersaodevalura2025aula1/aula-1)

> **⚠️ Observação:** O projeto está hospedado no Google Sites porque o GitHub Pages estava apresentando restrições de segurança (CORS/requisições) para o consumo direto da API externa do Google Livros. O código fonte completo e funcional se encontra neste repositório.

---

## 🛠️ Como Executar Localmente

Para rodar o projeto em seu ambiente local:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/lleonardo553/imersao-dev-alura-2025-aula-1.git](https://github.com/lleonardo553/imersao-dev-alura-2025-aula-1.git)
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd imersao-dev-alura-2025-aula-1
    ```
3.  Abra o arquivo `index.html` no seu navegador.
    *(Recomendação: Utilize uma extensão de servidor local, como o Live Server do VS Code, para evitar problemas de CORS ao tentar consumir a API, pois em alguns navegadores, abrir o arquivo diretamente pode causar bloqueios.)*

---

## 🙋 Contribuidor

**Lleonardo 553** - [@lleonardo553](https://github.com/lleonardo553)

---

## 🙏 Agradecimentos

Este projeto foi possível graças ao conteúdo e estrutura oferecidos pela **Imersão Dev** realizada pela **Alura** em parceria com o **Google**.
