# 🔗 Linktree - Página de Links Pessoais

> Clone personalizado do Linktree desenvolvido com HTML e CSS puro, criado como parte do curso da Alura.

## 📋 Sobre o Projeto

Este projeto é uma **página de links pessoais** inspirada no Linktree, que centraliza todos os seus perfis de redes sociais em um único lugar. Com um design moderno e responsivo, facilita o compartilhamento de múltiplos links através de uma única URL.

> 🎓 **Projeto desenvolvido como parte do curso de HTML e CSS da Alura**, aplicando conceitos de layout em grid, transições CSS e design responsivo.

## ✨ Demonstração

A página apresenta:
- 📸 Foto de perfil com efeito hover
- 👤 Nome e username do usuário
- 🔗 Grid de botões para redes sociais
- 🎨 Design com gradiente de azul e animações suaves
- ✨ Efeitos de hover interativos

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica da página
- **CSS3** - Estilização e animações
  - CSS Grid Layout
  - Transitions
  - Transforms
  - Hover Effects
- **Font Awesome 5.8.1** - Ícones das redes sociais

## 🎨 Paleta de Cores

```css
--cor-primaria: #39A7FF;      /* Azul principal (fundo) */
--cor-secundaria: #87C4FF;    /* Azul médio (botões) */
--cor-hover: #B6FFFA;         /* Azul claro (hover) */
--cor-texto: #FFFFFF;         /* Branco (texto) */
```

## 📱 Redes Sociais Incluídas

O projeto inclui links para 6 principais redes sociais:

- 💼 **LinkedIn** - Perfil profissional
- 📷 **Instagram** - Rede social de fotos
- 🐙 **GitHub** - Repositórios de código
- 💬 **WhatsApp** - Contato direto
- 📌 **Pinterest** - Inspirações visuais
- 🐦 **Twitter** - Microblogging

## 📁 Estrutura do Projeto

```
linktree-html-css/
│
├── linktree.html              # Estrutura da página
├── linktree.css               # Estilos e animações
├── cf3f5019ace1ff6d9c6f853428306295.png  # Foto de perfil
└── 40484135_8852379.png       # Imagem de fundo
```

## 💻 Como Usar

### Opção 1: Visualização Direta

1. Clone o repositório:
```bash
git clone https://github.com/victorarielima/Linktree---Html---CSS.git
```

2. Navegue até a pasta:
```bash
cd Linktree---Html---CSS
```

3. Abra o arquivo `linktree.html` no navegador

### Opção 2: Servidor Local

```bash
# Usando Python
python -m http.server 8000

# Usando Node.js
npx serve
```

Acesse `http://localhost:8000` no navegador

## 🎨 Funcionalidades e Efeitos

### Perfil
- ✅ **Foto circular** com borda arredondada
- ✅ **Efeito zoom** ao passar o mouse (scale 1.1)
- ✅ **Nome destacado** com efeito de opacidade
- ✅ **Username** com @ estilizado

### Grid de Links
- ✅ **Layout Grid** 2 colunas x 3 linhas
- ✅ **Botões responsivos** com border-radius
- ✅ **Ícones grandes** (4rem) do Font Awesome
- ✅ **Efeito hover** com mudança de cor
- ✅ **Animação de escala** (scale 1.06) ao hover
- ✅ **Transições suaves** (0.5s)

### Design
- ✅ **Fundo gradiente** com imagem personalizada
- ✅ **Cores harmoniosas** em tons de azul
- ✅ **Espaçamento otimizado** com grid-gap
- ✅ **Centralização perfeita** dos elementos

## 📚 Conceitos CSS Aplicados

### CSS Grid
```css
display: grid;
grid-template-columns: repeat(2, 40%);
grid-template-rows: repeat(3, 6rem);
grid-gap: 60px 20px;
justify-content: center;
```

### Transições e Transforms
```css
transition: 0.5s;
transform: scale(1.06);
```

### Pseudo-classes
```css
:hover {
    background-color: #B6FFFA;
    transform: scale(1.06);
}
```

### Border Radius
```css
border-radius: 50%;  /* Círculo perfeito */
border-radius: 30px; /* Bordas arredondadas */
```

## 🎓 Aprendizados do Curso

Durante o desenvolvimento deste projeto, foram aplicados:

- 📌 **HTML Semântico**: Uso adequado de tags `<header>`, `<section>`, `<a>`
- 📌 **CSS Grid Layout**: Criação de layouts em grade responsivos
- 📌 **Transições CSS**: Animações suaves e profissionais
- 📌 **Transform**: Efeitos de escala e rotação
- 📌 **Pseudo-classes**: Estados hover e active
- 📌 **Background**: Imagens de fundo e sobreposições
- 📌 **Centralização**: Técnicas modernas de alinhamento
- 📌 **Ícones**: Integração do Font Awesome

## 🔧 Personalização

Para personalizar a página para seu uso:

### 1. Alterar Informações Pessoais
```html
<!-- No arquivo linktree.html -->
<p id="name">Seu Nome</p>
<span>@seuusername</span>
```

### 2. Atualizar Links das Redes Sociais
```html
<!-- Substitua "1" pelos seus links reais -->
<a href="https://github.com/seuusuario" target="_blank" class="grid-item">
```

### 3. Trocar Foto de Perfil
- Substitua o arquivo `cf3f5019ace1ff6d9c6f853428306295.png`
- Ou atualize o caminho no HTML:
```html
<img src="sua-foto.png" alt="sua foto" id="perfil-image">
```

### 4. Personalizar Cores
```css
/* No arquivo linktree.css */
body {
    background-color: #SuaCor;
}

.grid-item {
    background-color: #SuaCor;
}
```

### 5. Adicionar Mais Redes Sociais
```html
<a href="seu-link" target="_blank" class="grid-item">
    <div>
        <i class="fab fa-nome-icone"></i>
    </div>
    <span>Nome da Rede</span>
</a>
```

## 🌟 Recursos Adicionais

### Ícones do Font Awesome

Acesse [Font Awesome](https://fontawesome.com/v5/search) para encontrar mais ícones:
- `fab fa-youtube` - YouTube
- `fab fa-tiktok` - TikTok
- `fab fa-discord` - Discord
- `fab fa-spotify` - Spotify
- `fab fa-twitch` - Twitch

### Dicas de Design
- 💡 Mantenha uma paleta de cores coesa (2-3 cores)
- 💡 Use imagens de alta qualidade
- 💡 Limite o número de links (6-8 idealmente)
- 💡 Ordene os links por importância
- 💡 Teste em diferentes dispositivos

## 📱 Responsividade

O projeto utiliza:
- ✅ Unidades relativas (rem, %)
- ✅ Grid responsivo
- ✅ Meta viewport configurada
- ✅ Imagens com cover

### Sugestões de Melhorias Futuras

- [ ] Media queries para mobile
- [ ] Tema escuro/claro
- [ ] Animações mais elaboradas
- [ ] Contador de cliques
- [ ] Links condiciona is (ativar/desativar)
- [ ] Analytics integrado

## 🎯 Casos de Uso

Este tipo de página é ideal para:

- 📱 **Bio do Instagram** - Link único na bio
- 💼 **Cartão de visita digital** - Compartilhe em eventos
- 🎨 **Portfolio** - Centralize seus trabalhos
- 📧 **Assinatura de email** - Link para todos os perfis
- 🎥 **Criadores de conteúdo** - Hub de todas as plataformas
- 🏢 **Networking** - Compartilhe em encontros profissionais

## 👨‍💻 Autor

**Victor Ariel**

- Instagram: [@imvictorariel](https://www.instagram.com/imvictorariel/)
- GitHub: [@victorarielima](https://github.com/victorarielima)

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais como parte de um curso da Alura.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 🔗 Referências

- [Linktree Original](https://linktr.ee/) - Inspiração do projeto
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Guia completo de Grid
- [Font Awesome Icons](https://fontawesome.com/) - Biblioteca de ícones
- [MDN Web Docs](https://developer.mozilla.org/) - Documentação web

## 💡 Dicas de SEO e Compartilhamento

Para melhorar o compartilhamento da sua página:

```html
<!-- Adicione no <head> -->
<meta name="description" content="Todos os meus links em um só lugar">
<meta property="og:title" content="Seu Nome - Links">
<meta property="og:description" content="Confira todos os meus perfis">
<meta property="og:image" content="sua-foto.png">
<meta name="twitter:card" content="summary">
```

---

<div align="center">

**📌 Acesse meus links e fique conectado!**

Desenvolvido com 💙 durante o curso da Alura

</div>
