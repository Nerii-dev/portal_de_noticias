# Portal de Notícias Nerii Dev

<img width="1236" height="618" alt="image" src="https://github.com/user-attachments/assets/23322b44-9225-4c18-bac7-00fe23f3f967" />
<br>
<br>
Um portal de notícias moderno e responsivo desenvolvido com foco em experiência do usuário e performance. <br> <br>
Disponível em: <br> <br>
🌐 https://nerii-dev.github.io/portal_de_noticias/
<br> <br>
Portal de Notícias de Tecnologia
<br> <br>
Este é um projeto de front-end que recria a interface de um portal de notícias com foco em tecnologia. A página foi desenvolvida utilizando exclusivamente HTML5 e CSS3, com ênfase em técnicas modernas de layout, organização de código e um sistema de design consistente.

## ✨ Principais Características

    Layout Moderno com CSS Grid: A estrutura principal da página é construída com CSS Grid e grid-template-areas, permitindo um layout complexo e de fácil manutenção.

    Design System com Variáveis CSS: Cores, tipografia e espaçamentos são definidos como variáveis CSS (custom properties) no :root, facilitando a consistência visual e futuras alterações no tema.

    CSS Modular: O código de estilização é organizado em múltiplos arquivos (global, header, seções, utilitários), tornando o projeto mais escalável e fácil de entender.

    HTML Semântico: O HTML5 é utilizado de forma semântica, com tags como <main>, <section>, <article>, <nav> e <figure>, melhorando a acessibilidade e a indexação (SEO).

    Classes Utilitárias: O projeto emprega um conjunto de classes utilitárias para tarefas repetitivas (como gap, grid-flow, text-size), agilizando o desenvolvimento e mantendo a consistência.

## 🛠 Tecnologias Utilizadas

    HTML5

    CSS3:

        CSS Grid Layout

        Flexbox

        Variáveis CSS (Custom Properties)

        Seletores Avançados (ex: ::before, :has())

## 📂 Estrutura de Arquivos

O projeto está organizado da seguinte forma:

    .
    ├── assets/
    │   ├── icons/
    │   └── images/
    ├── style/
    │   ├── global.css      # Estilos globais, reset e variáveis CSS
    │   ├── header.css      # Estilos específicos do cabeçalho
    │   ├── sections.css    # Estilos para as seções de conteúdo
    │   ├── utility.css     # Classes utilitárias reutilizáveis
    │   └── index.css       # Arquivo principal que importa todos os outros
    └── index.html          # Estrutura principal da página

## ⚙️ Como Executar

Este projeto não requer nenhuma dependência ou processo de compilação. Para visualizá-lo:

Clone este repositório:
    
    Bash
    
    git clone https://github.com/nerii-dev/portal_de_noticias.git

Navegue até a pasta do projeto:

    Bash
    
    cd [NOME_DA_PASTA]

Abra o arquivo index.html no seu navegador de preferência.

## 🎨 Configurações globais de fontes e cores:

    :root {
      --brand-color-light: #60a5fa;
      --brand-color-dark: #1D4ED8;
      --bg-color: #0F172A;
      --strole-color: #1E293B;
      --text-color-primary: #F1F5F9;
      --texto-color-secondary: #CBD5E1;
      --font-family: "Archivo", sans-serif;
      --h1: 800 24px/135% var(--font-family);
      --h2: 800 16px/140% var(--font-family);
      --h3: 800 14px/140% var(--font-family);
      --text-span: 600 14px/145% var(--font-family);
      --text: 400 16px/160% var(--font-family);
      --text-sm: 400 14px/160% var(--font-family);
    }

## Conteúdo

Para adicionar ou modificar notícias, edite diretamente o arquivo ```index.html```


Nota: Este é um projeto em desenvolvimento. Novas funcionalidades e melhorias serão implementadas continuamente.
