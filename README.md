# webFirst-noApp

Extensão para Google Chrome que remove banners botões, pop-ups
e avisos que incentivam o download e uso de aplicativos nativos (mobile ou desktop)
quando o site já pode ser usado normalmente no navegador.

### Problema

Muitos sites exibem mensagens como “Abra no app” ou “Use nosso aplicativo”
mesmo quando a experiência web é completa, prejudicando a navegação.

### Solução

A extensão identifica e oculta esses elementos, mantendo a página limpa
e focada no conteúdo.

### O que faz

- Oculta banners de incentivo ao app nativo
- Atua apenas no DOM da página
- Não bloqueia anúncios tradicionais
- Não interfere em requisições de rede

### O que não faz

- Não coleta dados do usuário
- Não rastreia navegação
- Não altera funcionalidades do site

### Privacidade

Nenhum dado do usuário é coletado ou transmitido, todo o processamento acontece localmente.

### Stack

- Vanilla JavaScript
- Vite
- Chrome Extensions (Manifest V3)

### Aviso legal

Esta extensão não é afiliada a nenhum site ou aplicativo citado.
