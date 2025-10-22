![Template de Blog Next.js da Netlify projetado por Bejamas](github-banner.svg)

# 📝 Template de Blog com Next.js

[![Botão de Deploy na Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify-templates/nextjs-blog-theme)

## 🚀 Sobre o Projeto

Este é um template de blog personalizável e moderno, desenvolvido com tecnologias de ponta para criar uma experiência de blogging excepcional. O projeto foi originalmente criado pela Bejamas e disponibilizado como template pela Netlify.

![Prévia do tema do blog](nextjs-blog-theme-preview.png)

## ✨ Tecnologias Utilizadas

O projeto utiliza um conjunto poderoso de tecnologias modernas:

- **⚛️ [Next.js](https://github.com/vercel/next.js)** v12 - Framework React com renderização do lado do servidor
- **🎨 [Tailwind CSS](https://tailwindcss.com/)** v3.0 - Framework CSS utilitário para design rápido e responsivo
- **📄 [MDX](https://mdxjs.com/)** v1 - Permite usar componentes React dentro de arquivos Markdown
- **🌓 Tema Claro/Escuro** - Design moderno com suporte a temas claro e escuro
- **📱 Design Responsivo** - Experiência perfeita em dispositivos móveis e desktop

## 🗂️ Estrutura do Projeto

```
├── components/       # Componentes React reutilizáveis
├── pages/           # Páginas da aplicação e rotas
│   ├── posts/       # Páginas dinâmicas para posts do blog
├── posts/           # Arquivos MDX dos posts do blog
├── public/          # Arquivos estáticos (imagens, etc.)
├── styles/          # Estilos globais e configurações CSS
├── utils/           # Funções utilitárias
```

### 📋 Principais Arquivos e Diretórios

- `components/` - Contém todos os componentes React reutilizáveis
- `pages/` - Implementa o sistema de roteamento do Next.js
- `styles/globals.css` - Estilos globais da aplicação
- `utils/global-data.js` - Configurações globais do blog
- `tailwind.config.js` - Configuração do Tailwind CSS

## 🛠️ Como Começar

### Instalação Local

1. Clone o repositório:
```bash
git clone [URL_DO_SEU_REPOSITÓRIO]
cd [NOME_DO_REPOSITÓRIO]
```

2. Instale as dependências:
```bash
npm install
# ou
yarn install
```

3. Execute o projeto localmente:
```bash
npm run dev
# ou
yarn dev
```

4. Acesse o projeto em seu navegador:
```
http://localhost:3000
```

## ⚙️ Configuração do Blog

A configuração é baseada em variáveis de ambiente para facilitar a integração com qualquer plataforma Jamstack, como a Netlify.

| Variável | Descrição | Opções |
| --- | --- | --- |
| `BLOG_NAME` | Nome do seu blog, exibido abaixo do avatar | |
| `BLOG_TITLE` | Título principal (`h1`) na página inicial | |
| `BLOG_FOOTER_TEXT` | Texto no rodapé | |
| `BLOG_THEME` | Tema para o Tailwind | default |
| `BLOG_FONT_HEADINGS` | Família de fontes para todos os cabeçalhos HTML | sans-serif (padrão), serif, monospace |
| `BLOG_FONT_PARAGRAPHS` | Família de fontes para todos os outros elementos HTML | sans-serif (padrão), serif, monospace |

## 📝 Adicionando Novos Posts

Todos os posts são armazenados no diretório `/posts`. Para criar um novo post, crie um novo arquivo com a extensão [`.mdx`](https://mdxjs.com/).

Como os posts são escritos no formato `MDX`, você pode passar props e componentes. Isso significa que você pode usar [componentes React](https://reactjs.org/docs/components-and-props.html) dentro dos seus posts para torná-los mais interativos.

## 🧪 Testes

O projeto inclui configuração para testes com Cypress. Execute os testes com:

```bash
npm run test
# ou
yarn test
```

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.

---

⭐ Desenvolvido com ❤️ como parte do desafio da trilha React da DIO ⭐
