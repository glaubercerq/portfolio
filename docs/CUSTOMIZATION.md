# Guia de Customização

Este documento explica como personalizar o portfólio para suas necessidades.

## 📋 Personalização Básica

### 1. Informações Pessoais

Edite o arquivo `index.html` e atualize:

```html
<!-- Nome no título da página -->
<title>SEU NOME - Desenvolvedor Web</title>

<!-- Nome na seção hero -->
<span class="title-name">SEU NOME</span>

<!-- Sua foto -->
<img src="assets/images/profile.jpeg" alt="SEU NOME">
```

### 2. Contatos

```html
<!-- Email -->
<span>seu.email@exemplo.com</span>

<!-- Telefone -->
<span>+55 (XX) XXXXX-XXXX</span>

<!-- Localização -->
<span>Sua Cidade, País</span>

<!-- Links sociais -->
<a href="SEU_GITHUB" target="_blank">GitHub</a>
<a href="SEU_LINKEDIN" target="_blank">LinkedIn</a>
```

### 3. Skills

Ajuste as porcentagens em `index.html`:

```html
<div class="skill-progress" data-width="95"></div>
<span class="skill-percent">95%</span>
```

### 4. Projetos

Para cada projeto, atualize:

```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-ICONE"></i> <!-- Escolha um ícone -->
    </div>
    <!-- ... -->
    <h3 class="project-title">Nome do Projeto</h3>
    <p class="project-description">Descrição...</p>
    <div class="project-tech">
        <span class="tech-tag">Tecnologia</span>
    </div>
</div>
```

## 🎨 Customização Avançada

### Cores

Edite as variáveis CSS em `assets/css/main.css`:

```css
:root {
    --primary-color: #SUA_COR;
    --secondary-color: #SUA_COR;
    --accent-color: #SUA_COR;
    --gradient-primary: linear-gradient(135deg, #COR1, #COR2);
}
```

### Animações

Ajuste as animações modificando os keyframes:

```css
@keyframes float {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-20px); }
}
```

### Adicionar Nova Seção

1. Adicione o HTML na estrutura
2. Crie os estilos CSS correspondentes
3. Atualize a navegação
4. Adicione as animações de scroll reveal

## 📱 Responsividade

O site é totalmente responsivo com breakpoints:

- Desktop: 1200px+
- Laptop: 768px - 1199px
- Tablet: 481px - 767px
- Mobile: 320px - 480px

## 🚀 Performance

- Use imagens otimizadas (WebP quando possível)
- Mantenha os arquivos CSS e JS minificados
- Use CDNs para libraries externas
- Teste a performance com Lighthouse
