# 🕶️ Óticas Vida - Versão Web Pura

Site institucional da Óticas Vida desenvolvido com **HTML5**, **CSS3** e **JavaScript** puro (sem frameworks).

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e animações
- **JavaScript Vanilla** - Interatividade
- **Responsive Design** - Layout adaptável

## 📋 Funcionalidades

- ✅ Design responsivo (mobile, tablet, desktop)
- ✅ Menu hambúrguer para mobile
- ✅ Scroll suave entre seções
- ✅ Animações de entrada ao rolar página
- ✅ Header fixo com shadow ao rolar
- ✅ Sem dependências externas
- ✅ 100% nativo

## 🎨 Estrutura de Arquivos

```
otica-vida-web/
├── index.html      # Estrutura HTML
├── styles.css      # Todos os estilos
├── script.js       # Toda a lógica JavaScript
└── README.md       # Este arquivo
```

## 🛠️ Como Usar

### Opção 1: Abrir Diretamente

Simplesmente abra o arquivo `index.html` em qualquer navegador moderno.

### Opção 2: Servidor Local (Recomendado)

```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Com PHP
php -S localhost:8000
```

Depois acesse: `http://localhost:8000`

### Opção 3: Live Server (VS Code)

1. Instale a extensão "Live Server"
2. Clique com botão direito em `index.html`
3. Selecione "Open with Live Server"

## 📱 Responsividade

O site é totalmente responsivo e se adapta a:

- 📱 **Mobile:** < 768px
- 📱 **Tablet:** 768px - 1024px
- 💻 **Desktop:** > 1024px

## 🎯 Seções do Site

1. **Header** - Menu de navegação fixo
2. **Hero** - Banner principal com gradiente
3. **Produtos** - Catálogo com 4 produtos
4. **Sobre** - Informações da empresa
5. **Contato** - Dados de contato e redes sociais
6. **Footer** - Copyright

## ⚡ Performance

- Sem dependências externas
- CSS e JS inline (pode ser separado)
- Imagens otimizadas (placeholders)
- Carregamento instantâneo
- ~15KB total (sem imagens)

## 🎨 Personalização

### Cores

Edite as variáveis CSS no arquivo `styles.css`:

```css
:root {
    --primary-color: #1a1a1a;
    --secondary-color: #3b82f6;
    --accent-color: #10b981;
    --text-color: #374151;
}
```

### Conteúdo

Todo o conteúdo está no arquivo `index.html` e pode ser editado diretamente.

### Estilos

Todos os estilos estão organizados em `styles.css` com comentários.

### JavaScript

Toda a lógica está em `script.js` de forma simples e comentada.

## 🖼️ Adicionando Imagens

1. Crie uma pasta `images/`
2. Adicione suas imagens
3. Substitua os placeholders:

```html
<!-- Antes -->
<div class="placeholder">Óculos de grau</div>

<!-- Depois -->
<img src="images/oculos-grau.jpg" alt="Óculos de grau">
```

## 🌐 Deploy

### GitHub Pages

1. Suba os arquivos para um repositório
2. Vá em Settings > Pages
3. Selecione a branch `main`
4. Seu site estará em: `username.github.io/repo-name`

### Netlify

1. Arraste a pasta no site do Netlify
2. Pronto! Site no ar

### Vercel

```bash
npx vercel
```

## ✨ Recursos Implementados

### JavaScript

- Menu toggle responsivo
- Scroll suave
- Animações ao rolar
- Shadow dinâmico no header
- Click-to-call em mobile
- Intersection Observer

### CSS

- Variáveis CSS
- Flexbox e Grid
- Media queries
- Transições suaves
- Gradientes
- Animações keyframes
- Custom scrollbar

## 🔧 Melhorias Futuras

- [ ] Adicionar formulário de contato funcional
- [ ] Integrar com EmailJS ou FormSpree
- [ ] Adicionar galeria de imagens
- [ ] Implementar dark mode
- [ ] Adicionar carousel de produtos
- [ ] Integrar Google Maps
- [ ] Adicionar WhatsApp floating button

## 📄 Compatibilidade

Testado e funcionando em:

- ✅ Chrome/Edge (últimas versões)
- ✅ Firefox (últimas versões)
- ✅ Safari (últimas versões)
- ✅ Opera (últimas versões)
- ✅ Navegadores mobile

## 📝 Licença

© 2022 Óticas Vida - Todos os direitos reservados.

## 👨‍💻 Desenvolvimento

Desenvolvido com ❤️ usando apenas HTML, CSS e JavaScript puro.

---

**Dica:** Este é um site estático puro, não requer compilação ou build! 🚀
