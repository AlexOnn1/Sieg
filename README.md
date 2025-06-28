# Portfólio Gilmar (SIEG)

## Português

### Descrição Geral

Este projeto é um portfólio digital desenvolvido para apresentar os principais trabalhos, estudos e informações profissionais de Gilmar (SIEG), Motion Designer especializado em animação 2D para Broadcast, Publicidade e Design Digital. O site foi construído com foco em responsividade, acessibilidade e organização de conteúdo, visando facilitar a navegação de recrutadores, clientes e parceiros.

---

### Funcionalidades e Recursos

- **Página Inicial (`index.html`)**: Exibe os principais projetos com imagens, hover interativo e links para páginas detalhadas.
- **Página Sobre (`about.html`)**: Apresenta um resumo profissional, foto, trajetória, habilidades e formas de contato.
- **Página de Estudos (`studies.html`)**: Galeria de estudos e experimentos em motion design, com GIFs e imagens.
- **Páginas Individuais de Projetos (`src/html/`)**: Cada projeto possui uma página dedicada com descrição, vídeo demonstrativo (Vimeo), links externos (Behance) e navegação entre projetos.
- **Rodapé Fixo**: Presente em todas as páginas, com direitos autorais.
- **Menu de Navegação Fixo**: Com links para Works, Studies, About e redes sociais.
- **Responsividade**: Layout adaptado para diferentes tamanhos de tela (media queries em CSS).
- **Acessibilidade**: Uso de textos alternativos em imagens, contraste de cores e navegação por teclado.
- **SEO**: Metatags de descrição, palavras-chave e verificação Google.

---

### Tecnologias Utilizadas

- **HTML5**: Estrutura semântica das páginas.
- **CSS3**: Estilização, responsividade e animações de hover.
- **Font Awesome**: Ícones de redes sociais e navegação.
- **Google Fonts**: Tipografia personalizada (Raleway, Montserrat, Rubik).
- **Vimeo**: Integração de vídeos demonstrativos dos projetos.
- **Giphy**: GIFs para estudos e projetos.

---

### Estrutura de Pastas

```
Sieg/
│
├── index.html                # Página inicial com projetos em destaque
├── about.html                # Página sobre o autor
├── studies.html              # Página de estudos e experimentos
├── src/
│   ├── css/
│   │   ├── about.css         # Estilos da página About
│   │   ├── global.css        # Estilos globais e do header/footer
│   │   ├── projetos.css      # Estilos das páginas de projetos
│   │   ├── reset.css         # Reset de estilos para cross-browser
│   │   ├── studies.css       # Estilos da página Studies
│   │   └── style.css         # Estilos da página inicial
│   ├── html/
│   │   ├── broadcast-lol.html    # Página detalhada do projeto Broadcast Lol Esports
│   │   ├── calm-space.html       # Página detalhada do projeto Calm Space
│   │   ├── mafs-stream.html      # Página detalhada do projeto Mafs Stream
│   │   └── standard.html         # Template base para novos projetos
│   ├── images/
│   │   ├── projetos/         # Imagens dos projetos
│   │   ├── logos/            # Logos e favicon
│   │   └── foto/             # Foto de perfil
│   └── ...
└── README.md                 # Documentação do projeto
```

---

### Detalhamento do Código e Implementações

#### 1. HTML

- Uso de tags semânticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) para melhor estruturação e SEO.
- Inclusão de metatags para descrição, palavras-chave e verificação do Google Search Console.
- Imagens com `alt` descritivo para acessibilidade.
- Links externos com `target="_blank"` e `rel="noopener noreferrer"` para segurança.
- Navegação entre projetos implementada com `<a>` e ícones Font Awesome.

#### 2. CSS

- Reset de estilos para garantir consistência entre navegadores.
- Layout flexível com Flexbox para containers de projetos e navegação.
- Media queries para adaptação do layout em dispositivos móveis e telas pequenas.
- Efeitos de hover em cards de projetos, aumentando a interatividade.
- Estilos separados por contexto (global, projetos, estudos, about) para facilitar manutenção.

#### 3. Responsividade

- Layouts adaptados para diferentes larguras de tela (desktop, tablet, mobile).
- Redimensionamento de imagens, vídeos e fontes conforme o dispositivo.
- Menus e rodapés ajustados para não sobrepor conteúdo em telas pequenas.

#### 4. Acessibilidade

- Contraste de cores adequado para leitura.
- Textos alternativos em todas as imagens.
- Navegação por teclado garantida pela estrutura dos elementos.

#### 5. SEO

- Uso de `<title>`, `<meta name="description">` e `<meta name="keywords">` em todas as páginas.
- URLs amigáveis e estrutura de links internos consistente.

#### 6. Integração com Redes Sociais

- Ícones para Twitter, Threads, Bluesky, Behance, LinkedIn e Instagram.
- Links abrem em nova aba para não interromper a navegação do portfólio.

#### 7. Vídeos e GIFs

- Integração de vídeos do Vimeo via `<iframe>`, responsivos e sem conflito de tamanhos.
- GIFs de estudos carregados diretamente do Giphy.

#### 8. Comentários e Organização

- Comentários explicativos no código HTML e CSS para facilitar entendimento.
- Templates prontos para adicionar novos projetos rapidamente.

---

### Como Executar o Projeto

1. **Clone ou baixe este repositório:**
   ```bash
   git clone https://https://github.com/AlexOnn1/Sieg
   ```
2. **Abra o arquivo `index.html` em seu navegador preferido.**
3. **Navegue pelas páginas através do menu fixo no topo.**

---

### Como Adicionar Novos Projetos

1. Crie uma nova página HTML em `src/html/` baseada em `standard.html`.
2. Adicione as informações do projeto, vídeo, descrição e links.
3. Inclua o novo projeto na seção de projetos em `index.html` com imagem, título e link para a nova página.
4. Adicione imagens em `src/images/projetos/` se necessário.

---

### Possíveis Melhorias Futuras

- Adicionar suporte a temas claro/escuro.
- Implementar animações CSS mais avançadas.
- Adicionar formulário de contato funcional.
- Otimizar imagens para carregamento mais rápido.
- Internacionalização automática (i18n) para português e inglês.

---

### Contato

- Email: alexsander.santos.contato@gmail.com
- [LinkedIn](https://linkedin.com/in/alexsander-albino-dev)

---

## English

### General Description

This project is a digital portfolio developed to showcase the main works, studies, and professional information of Gilmar (SIEG), a Motion Designer specialized in 2D animation for Broadcast, Advertising, and Digital Design. The website was built with a focus on responsiveness, accessibility, and content organization, aiming to facilitate navigation for recruiters, clients, and partners.

---

### Features and Resources

- **Home Page (`index.html`)**: Displays main projects with images, interactive hover, and links to detailed pages.
- **About Page (`about.html`)**: Presents a professional summary, photo, background, skills, and contact information.
- **Studies Page (`studies.html`)**: Gallery of motion design studies and experiments, with GIFs and images.
- **Individual Project Pages (`src/html/`)**: Each project has a dedicated page with description, demo video (Vimeo), external links (Behance), and navigation between projects.
- **Fixed Footer**: Present on all pages, with copyright.
- **Fixed Navigation Menu**: With links to Works, Studies, About, and social networks.
- **Responsiveness**: Layout adapts to different screen sizes (CSS media queries).
- **Accessibility**: Use of alt texts in images, color contrast, and keyboard navigation.
- **SEO**: Description meta tags, keywords, and Google verification.

---

### Technologies Used

- **HTML5**: Semantic structure of the pages.
- **CSS3**: Styling, responsiveness, and hover animations.
- **Font Awesome**: Social and navigation icons.
- **Google Fonts**: Custom typography (Raleway, Montserrat, Rubik).
- **Vimeo**: Project demo video integration.
- **Giphy**: GIFs for studies and projects.

---

### Folder Structure

```
Sieg/
│
├── index.html                # Main page with featured projects
├── about.html                # About page
├── studies.html              # Studies and experiments page
├── src/
│   ├── css/
│   │   ├── about.css         # About page styles
│   │   ├── global.css        # Global and header/footer styles
│   │   ├── projetos.css      # Project pages styles
│   │   ├── reset.css         # Cross-browser style reset
│   │   ├── studies.css       # Studies page styles
│   │   └── style.css         # Home page styles
│   ├── html/
│   │   ├── broadcast-lol.html    # Broadcast Lol Esports project page
│   │   ├── calm-space.html       # Calm Space project page
│   │   ├── mafs-stream.html      # Mafs Stream project page
│   │   └── standard.html         # Base template for new projects
│   ├── images/
│   │   ├── projetos/         # Project images
│   │   ├── logos/            # Logos and favicon
│   │   └── foto/             # Profile photo
│   └── ...
└── README.md                 # Project documentation
```

---

### Code and Implementation Details

#### 1. HTML

- Use of semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) for better structure and SEO.
- Inclusion of meta tags for description, keywords, and Google Search Console verification.
- Images with descriptive `alt` text for accessibility.
- External links with `target="_blank"` and `rel="noopener noreferrer"` for security.
- Project navigation implemented with `<a>` and Font Awesome icons.

#### 2. CSS

- Style reset for cross-browser consistency.
- Flexible layout with Flexbox for project containers and navigation.
- Media queries for layout adaptation on mobile and small screens.
- Hover effects on project cards for interactivity.
- Styles separated by context (global, projects, studies, about) for easier maintenance.

#### 3. Responsiveness

- Layouts adapted for different screen widths (desktop, tablet, mobile).
- Resizing of images, videos, and fonts according to device.
- Menus and footers adjusted to avoid overlapping content on small screens.

#### 4. Accessibility

- Adequate color contrast for readability.
- Alt texts on all images.
- Keyboard navigation ensured by element structure.

#### 5. SEO

- Use of `<title>`, `<meta name="description">`, and `<meta name="keywords">` on all pages.
- Friendly URLs and consistent internal link structure.

#### 6. Social Media Integration

- Icons for Twitter, Threads, Bluesky, Behance, LinkedIn, and Instagram.
- Links open in a new tab to avoid interrupting portfolio navigation.

#### 7. Videos and GIFs

- Vimeo videos embedded via `<iframe>`, responsive and without size conflicts.
- Study GIFs loaded directly from Giphy.

#### 8. Comments and Organization

- Explanatory comments in HTML and CSS code for easier understanding.
- Ready-to-use templates for quickly adding new projects.

---

### How to Run the Project

1. **Clone or download this repository:**
   ```bash
   git clone https://github.com/AlexOnn1/Sieg
   ```
2. **Open the `index.html` file in your preferred browser.**
3. **Navigate through the pages using the fixed top menu.**

---

### How to Add New Projects

1. Create a new HTML page in `src/html/` based on `standard.html`.
2. Add project information, video, description, and links.
3. Include the new project in the projects section in `index.html` with image, title, and link to the new page.
4. Add images in `src/images/projetos/` if necessary.

---

### Possible Future Improvements

- Add light/dark theme support.
- Implement more advanced CSS animations.
- Add a functional contact form.
- Optimize images for faster loading.
- Automatic internationalization (i18n) for Portuguese and English.

---

### Contact

- Email: alexsander.santos.contato@gmail.com
- [LinkedIn](https://linkedin.com/in/alexsander-albino-dev)
