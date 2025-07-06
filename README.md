# Dia Internacional do Cooperativismo 🤝

Uma página web educacional dedicada ao **Dia Internacional das Cooperativas**, celebrando os princípios, valores e história do movimento cooperativista mundial.

## 📋 Sobre o Projeto

Este projeto é uma aplicação web responsiva que apresenta informações completas sobre o cooperativismo, desenvolvida para fins educacionais. A página celebra o Dia Internacional das Cooperativas, que é comemorado no primeiro sábado de julho desde 1995.

## ✨ Características

### 🎨 Design e Interface
- **Design Moderno**: Interface clean com gradientes e animações suaves
- **Totalmente Responsivo**: Adaptação perfeita para desktop, tablet e mobile
- **Navegação SPA**: Single Page Application com transições fluidas
- **Acessibilidade**: Suporte a navegação por teclado e padrões de acessibilidade

### 📱 Funcionalidades
- **Menu de Navegação Responsivo**: Menu hambúrguer para dispositivos móveis
- **Botão "Voltar ao Topo"**: Navegação facilitada em páginas longas
- **Formulário de Contato**: Validação completa de dados do usuário
- **Animações Interativas**: Efeitos visuais e transições suaves
- **Timeline Histórica**: Linha do tempo interativa da história do cooperativismo

## 📚 Conteúdo Educacional

### 🏠 O que é o Dia
- História e proclamação do Dia Internacional das Cooperativas
- Importância da data para o movimento cooperativista mundial
- Celebrações e tradições

### ⚖️ Princípios e Valores
- **7 Princípios Cooperativistas**:
  1. Adesão Voluntária e Livre
  2. Gestão Democrática
  3. Participação Econômica dos Membros
  4. Autonomia e Independência
  5. Educação, Formação e Informação
  6. Intercooperação
  7. Interesse pela Comunidade

- **Valores Fundamentais**: Ajuda mútua, responsabilidade, democracia, igualdade, equidade e solidariedade

### 🏭 Ramos do Cooperativismo
13 ramos do cooperativismo brasileiro (OCB):
- 🏠 Habitacional
- 💰 Crédito
- 🌾 Agropecuário
- 🏭 Trabalho
- 🏥 Saúde
- 🚛 Transporte
- 🎓 Educacional
- 🏪 Consumo
- 🎯 Especial
- ⚽ Esporte
- 🎨 Cultural
- 🏘️ Infraestrutura
- 🏖️ Turismo e Lazer

### 📖 História
- **1844**: Fundação da Rochdale Society (Inglaterra)
- **1895**: Criação da Aliança Cooperativa Internacional (ACI)
- **1902**: Primeira cooperativa no Brasil
- **1969**: Criação da OCB
- **1992**: Proclamação do Dia Internacional pela ONU
- **2012**: Ano Internacional das Cooperativas

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização avançada com:
  - Flexbox e CSS Grid
  - Gradientes e animações
  - Media queries para responsividade
  - Variáveis CSS personalizadas
- **JavaScript (Vanilla)**: Funcionalidades interativas:
  - Navegação SPA
  - Validação de formulários
  - Animações e efeitos visuais
  - Lazy loading de imagens
  - Suporte a gestos touch

### Recursos Externos
- **Google Fonts**: Tipografia otimizada
- **Unsplash**: Imagens de alta qualidade
- **Intersection Observer API**: Animações on-scroll
- **Service Worker**: Suporte PWA básico

## 🚀 Como Executar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional, mas recomendado)

### Instalação
1. **Clone ou baixe** o arquivo `index.html`
2. **Abra diretamente** no navegador ou
3. **Use um servidor local**:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (http-server)
   npx http-server
   
   # Live Server (VS Code)
   Extensão Live Server
   ```

### Acesso
- **Diretamente**: Abra `index.html` no navegador
- **Servidor local**: Acesse `http://localhost:8000`

## 📱 Responsividade

### Breakpoints
- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px
- **Mobile pequeno**: < 480px

### Adaptações Mobile
- Menu hambúrguer
- Timeline simplificada
- Cards em coluna única
- Formulário otimizado
- Imagens responsivas

## 🎯 Funcionalidades Técnicas

### Performance
- **Lazy Loading**: Carregamento otimizado de imagens
- **Debounce**: Otimização de eventos de scroll
- **CSS Otimizado**: Transições e animações eficientes
- **Imagens Comprimidas**: Carregamento rápido

### Acessibilidade
- **Semântica HTML**: Tags apropriadas e ARIA labels
- **Navegação por Teclado**: Suporte completo
- **Contraste**: Cores acessíveis
- **Focus Visible**: Indicadores claros de foco

### SEO
- **Meta Tags**: Descrição, keywords e Open Graph
- **Estrutura Semântica**: Headers hierárquicos
- **URLs Amigáveis**: Navegação por âncoras
- **Schema Markup**: Dados estruturados (potencial)

## 🎨 Paleta de Cores

```css
/* Cores Principais */
--primary: #667eea        /* Azul principal */
--secondary: #764ba2      /* Roxo secundário */
--accent: #2c5aa0         /* Azul escuro */
--background: #f8f9fa     /* Cinza claro */
--white: #ffffff          /* Branco */
--text: #333333           /* Texto escuro */
```

## 📧 Formulário de Contato

### Validações Implementadas
- **Nome**: Mínimo 2 caracteres
- **E-mail**: Formato válido (regex)
- **Telefone**: Mínimo 10 dígitos (opcional)
- **Assunto**: Mínimo 3 caracteres
- **Mensagem**: Mínimo 10 caracteres

### Recursos
- Validação em tempo real
- Mensagens de erro personalizadas
- Feedback visual para o usuário
- Simulação de envio

## 🌟 Recursos Especiais

### Animações
- **Fade In**: Entrada suave dos elementos
- **Slide Up**: Animação de rolagem
- **Hover Effects**: Interações visuais
- **Type Writer**: Efeito de digitação no título

### Interatividade
- **Timeline Animada**: História do cooperativismo
- **Cards Interativos**: Ramos do cooperativismo
- **Menu Responsivo**: Navegação mobile
- **Scroll Suave**: Transições fluidas

## 🔧 Melhorias Futuras

### Funcionalidades
- [ ] Sistema de busca interno
- [ ] Modo escuro/claro
- [ ] Compartilhamento social
- [ ] Comentários e avaliações
- [ ] Newsletter

### Técnicas
- [ ] Service Worker completo
- [ ] Cache offline
- [ ] Progressive Web App
- [ ] Internacionalização (i18n)
- [ ] CMS headless

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais sobre o cooperativismo. O conteúdo é baseado em informações públicas sobre o movimento cooperativista mundial.

## 🤝 Contribuições

Contribuições são bem-vindas! Se você deseja melhorar este projeto:

1. **Fork** o repositório
2. **Crie** uma branch para sua feature
3. **Commit** suas mudanças
4. **Push** para a branch
5. **Abra** um Pull Request

## 📞 Contato

Para dúvidas, sugestões ou colaborações, utilize o formulário de contato disponível na própria página.

---

**Cooperativismo**: *Construindo um mundo melhor através da solidariedade e ajuda mútua* 🌟
