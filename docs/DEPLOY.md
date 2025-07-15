# Guia de Deploy

Este documento explica como fazer o deploy do seu portfólio em diferentes plataformas.

## 🚀 Opções de Deploy

### 1. GitHub Pages (Gratuito)

1. **Prepare o repositório:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/SEU_USUARIO/portfolio
   git push -u origin main
   ```

2. **Configure o GitHub Pages:**
   - Vá para Settings > Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Clique em Save

3. **Acesse:** `https://SEU_USUARIO.github.io/portfolio`

### 2. Netlify (Gratuito)

1. **Deploy rápido:**
   - Arraste a pasta do projeto para [netlify.com/drop](https://netlify.com/drop)
   - Ou conecte seu repositório GitHub

2. **Configurações avançadas:**
   - Build command: (vazio)
   - Publish directory: (vazio ou .)
   - Environment variables: (se necessário)

3. **Domínio personalizado:**
   - Site settings > Domain management
   - Add custom domain

### 3. Vercel (Gratuito)

1. **Conecte o repositório:**
   - Importe o projeto do GitHub
   - Framework Preset: Other
   - Build command: (vazio)
   - Output directory: (vazio)

2. **Deploy automático:**
   - Cada push no GitHub faz deploy automático

### 4. Surge.sh (Gratuito)

1. **Instale o Surge:**
   ```bash
   npm install -g surge
   ```

2. **Faça o deploy:**
   ```bash
   surge
   ```

3. **Domínio personalizado:**
   ```bash
   surge --domain meudominio.surge.sh
   ```

## 🛠️ Preparação para Deploy

### Checklist pré-deploy:

- [ ] Teste o site localmente
- [ ] Otimize imagens
- [ ] Verifique todos os links
- [ ] Teste responsividade
- [ ] Valide HTML/CSS
- [ ] Configure analytics (opcional)
- [ ] Adicione favicon
- [ ] Configure meta tags SEO

### SEO Básico:

Adicione ao `<head>`:

```html
<!-- SEO Meta Tags -->
<meta name="description" content="Portfólio de Glauber Cerqueira - Desenvolvedor Web Full Stack especializado em React, Node.js e Python">
<meta name="keywords" content="desenvolvedor web, full stack, react, nodejs, python, portfolio">
<meta name="author" content="Glauber Cerqueira">

<!-- Open Graph -->
<meta property="og:title" content="Glauber Cerqueira - Desenvolvedor Web">
<meta property="og:description" content="Portfólio profissional com projetos em React, Node.js e Python">
<meta property="og:image" content="assets/images/og-image.jpg">
<meta property="og:url" content="https://seudominio.com">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Glauber Cerqueira - Desenvolvedor Web">
<meta name="twitter:description" content="Portfólio profissional com projetos em React, Node.js e Python">
<meta name="twitter:image" content="assets/images/og-image.jpg">
```

## 📊 Analytics

### Google Analytics:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🔒 HTTPS

Todas as plataformas mencionadas fornecem HTTPS automático. Para domínios personalizados, configure SSL nas configurações da plataforma.
