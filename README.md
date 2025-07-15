# 🚀 Portfólio Glauber Cerqueira

> Portfólio pessoal moderno e responsivo desenvolvido com HTML5, CSS3 e JavaScript vanilla, apresentando um design inspirado em interfaces blockchain com animações fluidas e efeitos glassmorphism.

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)

[![Demo](https://img.shields.io/badge/🌐_Demo_Live-37a779?style=for-the-badge)](https://glaubercerq.github.io/portfolio)
[![GitHub](https://img.shields.io/badge/📂_Código-black?style=for-the-badge&logo=github)](https://github.com/glaubercerq/portfolio)

</div>

## 📋 Índice

- [✨ Características](#-características)
- [🛠️ Tecnologias](#️-tecnologias)
- [📂 Estrutura do Projeto](#-estrutura-do-projeto)
- [🚀 Como Usar](#-como-usar)
- [📱 Responsividade](#-responsividade)
- [🎨 Customização](#-customização)
- [📊 Projetos em Destaque](#-projetos-em-destaque)
- [🌐 Deploy](#-deploy)
- [📄 Licença](#-licença)
- [📞 Contato](#-contato)

## ✨ Características

### 🎨 **Design Moderno**
- **Glassmorphism Effects** - Efeitos de vidro translúcido modernos
- **Gradientes Dinâmicos** - Cores vibrantes inspiradas em DeFi/Blockchain
- **Cursor Customizado** - Cursor personalizado com trail animado
- **Partículas Interativas** - Sistema de partículas em canvas no background

### 🎭 **Animações Avançadas**
- **Scroll Reveal** - Elementos aparecem suavemente ao fazer scroll
- **Tilt Effects** - Efeito 3D nos cards ao passar o mouse
- **Magnetic Buttons** - Botões que reagem ao movimento do cursor
- **Floating Elements** - Cards flutuantes com tecnologias
- **Parallax Scrolling** - Efeito parallax sutil em elementos
- **Typing Animation** - Animação de digitação no título principal

### 📱 **Totalmente Responsivo**
- **Mobile First** - Otimizado para dispositivos móveis
- **Breakpoints Inteligentes** - Adapta-se a qualquer tamanho de tela
- **Touch Friendly** - Interações otimizadas para touch
- **Performance** - Carregamento rápido e animações suaves

### 🚀 **Funcionalidades**
- **Navegação Suave** - Smooth scrolling entre seções
- **Barras de Progresso Animadas** - Skills com animação
- **Contador de Estatísticas** - Números animados
- **Formulário de Contato** - Sistema de notificações
- **Menu Hamburger** - Menu responsivo para mobile

## 🛠️ Tecnologias

| Categoria | Tecnologias |
|-----------|-------------|
| **Frontend** | HTML5 Semântico, CSS3 Avançado, JavaScript ES6+ |
| **Design** | Flexbox, CSS Grid, Animations, Transforms |
| **Ícones** | Font Awesome 6.0 |
| **Fontes** | Google Fonts (Inter) |
| **Metodologia** | Mobile First, Progressive Enhancement |

## � Estrutura do Projeto

```
portfolio/
├── 📄 index.html              # Página principal
├── 📁 assets/                 # Recursos do projeto
│   ├── 📁 css/
│   │   └── 📄 main.css        # Estilos principais
│   ├── 📁 js/
│   │   └── 📄 main.js         # Scripts e interatividade
│   └── 📁 images/
│       └── 📄 profile.jpeg    # Imagem de perfil
├── 📁 docs/                   # Documentação
│   ├── 📄 CUSTOMIZATION.md    # Guia de personalização
│   └── 📄 DEPLOY.md           # Guia de deploy
├── 📄 package.json            # Configurações do projeto
├── 📄 .gitignore             # Arquivos ignorados pelo Git
└── 📄 README.md              # Este arquivo
```

## 🚀 Como Usar

### 1. **Clone o Repositório**
```bash
git clone https://github.com/glaubercerq/portfolio.git
cd portfolio
```

### 2. **Abra Localmente**
```bash
# Usando Live Server (VS Code)
# Ou simplesmente abra index.html no navegador
open index.html
```

### 3. **Personalize**
- Edite `index.html` com suas informações
- Substitua `assets/images/profile.jpeg` pela sua foto
- Ajuste cores em `assets/css/main.css` se desejar

### 4. **Deploy**
- Faça upload para GitHub Pages, Netlify, Vercel, etc.
- Veja o [Guia de Deploy](docs/DEPLOY.md) para instruções detalhadas

## 📱 Responsividade

| Dispositivo | Resolução | Características |
|-------------|-----------|-----------------|
| 🖥️ **Desktop** | 1200px+ | Layout completo, todas as animações |
| 💻 **Laptop** | 768px - 1199px | Layout adaptado, animações otimizadas |
| 📱 **Tablet** | 481px - 767px | Menu hamburger, grid reorganizada |
| 📱 **Mobile** | 320px - 480px | Layout vertical, touch optimizado |

## 🎨 Customização

### **Cores Principais**
```css
:root {
    --primary-color: #0F3460;
    --secondary-color: #16537e;
    --accent-color: #E94560;
    --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### **Adicionar Projeto**
```html
<div class="project-card">
    <div class="project-image">
        <div class="project-icon">
            <i class="fas fa-SEU-ICONE"></i>
        </div>
        <!-- ... -->
    </div>
    <div class="project-content">
        <h3 class="project-title">Nome do Projeto</h3>
        <p class="project-description">Descrição...</p>
        <div class="project-tech">
            <span class="tech-tag">Tecnologia</span>
        </div>
    </div>
</div>
```

Veja o [Guia de Customização](docs/CUSTOMIZATION.md) para mais detalhes.

## 📊 Projetos em Destaque

### 🐾 **Quiz Espécies Animais**
Aplicativo de quiz interativo com React, Node.js, Docker e MySQL

### 🛡️ **QA Consultoria & Cursos**
Website corporativo em WordPress com sistema de vendas de cursos

### 🤖 **Event Finder AI**
Sistema inteligente de busca de eventos com Gemini AI e FastAPI

### ✂️ **Golden Barber** *(Em Desenvolvimento)*
App mobile React Native para gerenciamento de barbearias

### 🎮 **Submundo Rio** *(Em Desenvolvimento)*
Jogo web com economia baseada em NFTs e blockchain

### 📈 **Finance AI Trader** *(Em Desenvolvimento)*
Sistema de análise financeira com LLM para sinais de trading

## 🌐 Deploy

### **Opções Recomendadas:**

1. **GitHub Pages** (Gratuito)
   - Conecte o repositório
   - Configure em Settings > Pages
   - URL: `username.github.io/portfolio`

2. **Netlify** (Gratuito)
   - Arraste a pasta para netlify.com/drop
   - Deploy automático a cada commit

3. **Vercel** (Gratuito)
   - Importe do GitHub
   - Deploy automático com domínio customizado

Veja o [Guia de Deploy Completo](docs/DEPLOY.md) para instruções detalhadas.

## 🎯 Performance

- ⚡ **Lighthouse Score**: 95+ em Performance
- 🚀 **Tempo de Carregamento**: < 2s
- 📱 **Mobile Friendly**: 100%
- ♿ **Acessibilidade**: Semântica adequada
- 🔍 **SEO**: Meta tags otimizadas

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. 🍴 Fazer um fork do projeto
2. 🔧 Criar uma branch para sua feature
3. 💾 Commit suas mudanças
4. 📤 Push para a branch
5. 🔀 Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Contato

<div align="center">

**Glauber Cerqueira**  
*Desenvolvedor Web Full Stack*

[![Email](https://img.shields.io/badge/📧_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:glauber.santos.ramos@gmail.com)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/glauber-cerqueira-4b13b32ba/)
[![GitHub](https://img.shields.io/badge/👨‍💻_GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/glaubercerq)
[![WhatsApp](https://img.shields.io/badge/📱_WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+5521976592859)

📍 **Rio de Janeiro, Brasil**

</div>

---

<div align="center">

**Desenvolvido com ❤️ usando HTML, CSS e JavaScript**

*Se este projeto te ajudou, considere dar uma ⭐ no repositório!*

</div>
