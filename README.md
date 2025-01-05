# PROJETO CAPACITA BRASIL

## ATIVIDADE DE NIVELAMENTO - MÓDULO BÁSICO

**Prof. Eliakim**

# PROPOSTA DE ATIVIDADE - Criação de uma Landing Page

Escolha um tema para sua página:

- Biblioteca virtual
- Aprender Libras
- Viagens e Turismo (SELECIONADO)
- Aventura

---

### Instruções de Estrutura HTML Completa para o Projeto Web

#### 1. Cabeçalho (`<header>`)

- **Logotipo**: Adicionar uma imagem de logotipo que represente o tema do site. O logotipo deve estar à esquerda do cabeçalho.
- **Barra de Navegação**:
  - Usar uma lista não ordenada (`<ul>`) para estruturar os links principais do site, como "Início", "Conteúdo", "Vídeos" e "Contato".
  - Cada link deve estar dentro de um item de lista (`<li>`) com links internos para as seções da página.

#### 2. Seção Principal (`<main>`)

- Esta seção é o corpo central do site e deve conter sub-seções para os principais conteúdos. As sub-seções devem estar dentro do `<main>` para manter a estrutura semântica.
- **Seção de Introdução**:
  - Adicionar uma breve introdução ao tema do site, explicando o propósito e oferecendo uma visão geral.
  - Incluir um título (`<h1>`) e um parágrafo (`<p>`) com informações iniciais.
- **Seção de Conteúdo ou Artigos (`<section id="conteudo">`)**:
  - Estruturar uma área para artigos ou conteúdos principais.
  - Cada artigo deve ser criado com uma tag `<article>`.
    - Dentro de cada `<article>`:
      - Título do artigo (`<h2>`), imagem ilustrativa (`<img>` com atributo alt descritivo) e parágrafo com resumo (`<p>`).
      - Adicionar botões de interação para "Leia mais" ou "Comente", levando a uma página ou seção adicional.
- **Seção de Vídeos (`<section id="videos">`)**:
  - Embed de vídeos utilizando a tag `<video>` ou `<iframe>` para vídeos externos.
  - Incluir legendas ou descrições em cada vídeo para acessibilidade.
  - Requisitos obrigatórios:
    - Cada vídeo deve ter uma breve descrição em texto (`<p>`) para contexto e uma transcrição, caso necessário.

#### 3. Formulário de Contato (`<section id="contato">`)

- **Estruturado Formulário**: O formulário deve ser configurado para envio de informações com campos obrigatórios.
  - **Campos obrigatórios**:
    - Nome (`<input type="text">`): Campo de texto obrigatório com um placeholder para orientar o usuário.
    - Email (`<input type="email">`): Campo de email obrigatório com validação de email.
    - Assunto (`<select>`): Seleção obrigatória com opções predefinidas.
    - Mensagem (`<textarea>`): Campo de texto extenso para a mensagem do usuário, marcado como obrigatório.
    - Botão de envio (`<button type="submit">`): Usar `type="submit"` para o botão e estilizar conforme o tema do site.
  - **Validação**: Todos os campos devem usar o atributo `required` para garantir que nenhum campo obrigatório seja deixado em branco antes do envio.

#### 4. Rodapé (`<footer>`)

- **Links de Navegação**:
  - Incluir links adicionais para seções do site, como "Política de Privacidade", "Termos de Uso" e "Ajuda".
- **Links para Redes Sociais**:
  - Inserir ícones com links para redes sociais como Facebook, Twitter e Instagram.
- **Informações de Contato**:
  - Adicionar informações de contato, como e-mail e telefone, ou um link para a seção de contato.

#### 5. Regras Adicionais

- **Estrutura Semântica**: Todos os elementos devem estar organizados em tags semânticas (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`) para acessibilidade e boas práticas.
- **Campos Obrigatórios**: Usar o atributo `required` nos campos de formulário que são essenciais para envio.
- **Links Internos e Navegação**:
  - Configurar a navegação para que todos os links no cabeçalho direcionem para seções da página usando `id` nas seções e `href="#id-secao"` nos links.
- **Validação de Formulário**: Além do `required`, garantir validação para tipos de campo (email, number, etc.), proporcionando um envio sem erros.
- **Uso de Imagens e Vídeos**:
  - Adicionar atributos `alt` descritivos em imagens para acessibilidade e `title` nos vídeos quando aplicável.

#### 6. Utilizando Conceitos de CSS, Estilize sua Página

#### 7. Adicione seu Projeto em um Repositório Remoto do GitHub



  
