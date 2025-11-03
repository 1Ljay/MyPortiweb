# 🚀 Luciano Junior - Portfolio

<div align="center">

[![Astro](https://img.shields.io/badge/Astro-5.0-FF5D01?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

**Portfólio profissional desenvolvido com tecnologias modernas e design espacial futurista**

[Demo ao Vivo](#) · [Reportar Bug](https://github.com/1Ljay/MyPortiweb/issues) · [Solicitar Feature](https://github.com/1Ljay/MyPortiweb/issues)

</div>

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Características](#-características)
- [Stack Tecnológico](#-stack-tecnológico)
- [Começando](#-começando)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Comandos Disponíveis](#-comandos-disponíveis)
- [Internacionalização](#-internacionalização)
- [Build e Deploy](#-build-e-deploy)
- [Licença](#-licença)
- [Contato](#-contato)

---

## 🎯 Sobre o Projeto

Portfolio pessoal de desenvolvedor full-stack construído com **Astro** e **Tailwind CSS**, apresentando um design espacial moderno com animações suaves, suporte multilíngue completo e toggle dark/light mode com persistência de estado.

### ✨ Por que este projeto?

- **Performance First**: Utiliza Astro para entrega de HTML estático ultra-rápido
- **SEO Otimizado**: Meta tags dinâmicas e estrutura semântica perfeita
- **UX Moderna**: Animações fluidas e transições suaves em toda a aplicação
- **Acessibilidade**: WCAG 2.1 AA compliant com suporte a leitores de tela
- **Responsivo**: Design mobile-first que funciona perfeitamente em qualquer dispositivo

---

## 🌟 Características

### 🎨 Design & UI/UX

- **Design Espacial Futurista**: Tema com animações de estrelas em movimento e efeitos holográficos
- **Dark/Light Mode**: Toggle suave entre temas com preferência salva em localStorage
- **Glassmorphism**: Cards com efeito de vidro fosco e blur avançado
- **Animações CSS Puras**: Transições e efeitos sem dependências JavaScript pesadas
- **Sistema Orbital**: 15 tecnologias orbitando ao redor da foto principal como uma roda
- **Light Beams**: Efeitos de feixes de luz passando pelos cards de projetos
- **Gradientes Dinâmicos**: Bordas e elementos com gradientes coloridos animados

### 🌍 Internacionalização

- **3 Idiomas**: Português (BR), Inglês (US), Espanhol (ES)
- **Roteamento i18n**: URLs amigáveis para cada idioma (`/`, `/en`, `/es`)
- **Tradução Completa**: Todo conteúdo totalmente traduzido
- **Persistência**: Idioma selecionado mantido entre navegações

### ⚡ Performance

- **Score Lighthouse**: 100/100 em Performance, SEO e Acessibilidade
- **Otimização de Imagens**: Lazy loading e formatos modernos
- **CSS Otimizado**: Tailwind com purge automático
- **Código Limpo**: Bundle size mínimo com tree-shaking
- **Static Site Generation**: Pré-renderização de todas as páginas

### 📱 Responsividade

- **Mobile First**: Design otimizado para dispositivos móveis
- **Breakpoints Inteligentes**: Layouts adaptáveis para todos os tamanhos
- **Touch Friendly**: Gestos e interações otimizadas para touch
- **PWA Ready**: Preparado para Progressive Web App

---

## 🛠 Stack Tecnológico

### Core

| Tecnologia | Versão | Descrição |
|-----------|--------|-----------|
| [Astro](https://astro.build) | 5.0.0 | Framework web all-in-one para sites ultra-rápidos |
| [Tailwind CSS](https://tailwindcss.com) | 3.4.0 | Framework CSS utilitário para design rápido |
| [TypeScript](https://www.typescriptlang.org) | 5.6.0 | JavaScript com tipagem estática |

### Bibliotecas & Tools

- **astro-icon**: Biblioteca de ícones com suporte a Iconify (200k+ ícones)
- **@iconify-json/logos**: Logos oficiais de tecnologias
- **@iconify-json/mdi**: Material Design Icons
- **@iconify-json/simple-icons**: Ícones de marcas

### Tecnologias em Destaque

- C#, Python, JavaScript, Flutter, Dart
- TypeScript, React, Next.js, Astro
- Tailwind CSS, Git, PostgreSQL
- Docker, AWS, IA

---

## 🚀 Começando

### Pré-requisitos

- **Node.js** 18.x ou superior
- **npm** 9.x ou superior (ou yarn/pnpm)
- **Git** para clonar o repositório

### Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/1Ljay/MyPortiweb.git
   cd MyPortiweb
   ```

2. **Instale as dependências**
   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento**
   ```bash
   npm run dev
   ```

4. **Abra no navegador**
   
   Acesse [http://localhost:4321](http://localhost:4321)

---

## 📁 Estrutura do Projeto

```
src/
├── components/          # Componentes reutilizáveis
│   ├── ContactLink.astro
│   ├── ContactSection.astro
│   ├── Footer.astro
│   ├── Header.astro
│   ├── Hero.astro         # Seção hero com órbita de tecnologias
│   ├── LanguagePicker.astro
│   ├── ProjectCard.astro  # Card individual de projeto
│   ├── ProjectsSection.astro
│   ├── SkillCard.astro    # Card individual de habilidade
│   ├── SkillsSection.astro
│   ├── TechIcon.astro     # Ícone de tecnologia orbital
│   └── ThemeToggle.astro
├── data/                # Dados e constantes
│   └── technologies.ts  # Lista de tecnologias com tipagem
├── i18n/                # Internacionalização
│   ├── languages.ts     # Traduções pt/en/es
│   └── utils.ts         # Utilitários i18n (getLangFromUrl, useTranslations)
├── layouts/             # Layouts base
│   └── Layout.astro     # Layout principal com SEO e meta tags
├── pages/               # Páginas (rotas)
│   ├── index.astro      # Página principal (pt)
│   ├── en/
│   │   └── index.astro  # Versão em inglês
│   └── es/
│       └── index.astro  # Versão em espanhol
└── styles/
    └── global.css       # Estilos globais e animações customizadas
```

---

## 💻 Comandos Disponíveis

| Comando | Ação | Descrição Detalhada |
|---------|------|---------------------|
| `npm install` | Instala dependências | Baixa e instala todas as dependências do projeto |
| `npm run dev` | Servidor de desenvolvimento | Inicia em `localhost:4321` com hot-reload |
| `npm run build` | Build de produção | Cria build otimizado em `./dist/` |
| `npm run preview` | Preview da build | Visualiza a build de produção localmente |
| `npm run astro` | CLI do Astro | Acessa comandos do Astro diretamente |

---

## 🌐 Internacionalização

### Idiomas Suportados

| Idioma | Código | URL | Status |
|--------|--------|-----|--------|
| 🇧🇷 Português (Brasil) | `pt` | `/` | ✅ Completo |
| 🇺🇸 English (US) | `en` | `/en` | ✅ Completo |
| 🇪🇸 Español | `es` | `/es` | ✅ Completo |

---

## 📦 Build e Deploy

### Build de Produção

```bash
npm run build
```

Arquivos otimizados serão gerados em `dist/` com:
- ✅ HTML minificado e pré-renderizado
- ✅ CSS otimizado e purgado (apenas classes usadas)
- ✅ Imagens otimizadas
- ✅ JavaScript tree-shaked (apenas o necessário)

### Deploy

#### Vercel (Recomendado)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/1Ljay/MyPortiweb)

```bash
npm install -g vercel
vercel --prod
```

**Configuração automática** - Vercel detecta Astro automaticamente!

#### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/1Ljay/MyPortiweb)

```bash
npm install -g netlify-cli
netlify deploy --prod
```

**Configuração:**
- Build command: `npm run build`
- Publish directory: `dist`

#### Cloudflare Pages

1. Conecte seu repositório ao Cloudflare Pages
2. Configure:
   - **Build command**: `npm run build`
   - **Output directory**: `dist`
   - **Environment variables**: (se necessário)

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja `LICENSE` para mais informações.

Isso significa que você pode:
- ✅ Usar comercialmente
- ✅ Modificar
- ✅ Distribuir
- ✅ Uso privado

**Condição**: Incluir o aviso de copyright original.

---

## 📞 Contato

**Luciano Junior** - Desenvolvedor Full Stack

[![GitHub](https://img.shields.io/badge/GitHub-1Ljay-181717?style=for-the-badge&logo=github)](https://github.com/1Ljay)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Luciano_Jr-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/luciano-jr-a05613371/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-+55_51_98282--1616-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send?phone=5551982821616)
[![Email](https://img.shields.io/badge/Email-lucianojunior%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lucianojunior@gmail.com)

**Link do Projeto**: [https://github.com/1Ljay/MyPortiweb](https://github.com/1Ljay/MyPortiweb)

---

<div align="center">

## ⭐ Mostre seu Apoio

Se este projeto te ajudou ou inspirou, considere dar uma **estrela** ⭐!

**Desenvolvido por [Luciano Junior](https://github.com/1Ljay)**

</div>

