# Portfolio - Dionarley R Vieira

Um portfólio pessoal moderno e responsivo para desenvolvedor e maker brasileiro.

## 🚀 Visão Geral

Este é um site de portfólio pessoal construído com HTML, CSS e JavaScript puro. O design é limpo, moderno e totalmente responsivo.

### Características

- 📱 Totalmente responsivo (mobile, tablet, desktop)
- 🎨 Design moderno com paleta de cores militar (verde, amarelo, cinza)
- ⚡ Animações suaves e transições
- 📧 Formulário de contato com validação
- 🎯 Seções: Início, Sobre, Skills, Projetos, Contato
- 🐳 Dockerizado com nginx

## 📁 Estrutura do Projeto

```
portfolio/
├── index.html          # Página principal
├── styles.css        # Estilos CSS
├── script.js        # JavaScript interativo
├── Dockerfile       # Docker image
├── nginx.conf       # Configuração nginx
├── docker-compose.yml # Orquestração Docker
├── DEVELOPER.md     # Documentação para desenvolvedores
├── AGENTS.md        # Regras para agentes IA
├── README.md        # Este arquivo
└── LICENSE         # CC BY-SA 4.0
```

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e layout (Flexbox, Grid)
- **JavaScript** - Interatividade e animações
- **Font Awesome** - Ícones (via CDN)
- **Docker + nginx** - Containerização

## 🚦 Quick Start

### Docker (Recomendado)

```bash
# Desenvolvimento com hot reload
docker-compose up --build

# Produção
docker-compose up -d --build portfolio-prod
```

Acesse: http://localhost:8080

### Local (Sem Docker)

```bash
# Abra index.html no navegador
# ou
python -m http.server 8080
```

## 🐳 Docker

### Comandos

```bash
# Desenvolvimento
docker-compose up --build

# Produção
docker-compose up -d --build portfolio-prod

# Ver logs
docker-compose logs -f

# Parar
docker-compose down
```

### Ports

| Serviço | Porta |
|---------|-------|
| portfolio | 8080 |
| portfolio-prod | 8080 |

## 🎨 Personalização

### Cores

Edite as variáveis CSS em `styles.css`:

```css
:root {
    --primary-color: #3d4d1e;
    --secondary-color: #6b7a18;
    --accent-color: #e0b418;
    /* ... */
}
```

### Habilidades e Projetos

Edite `index.html` seguindo o padrão dos cards existentes.

## 📄 Licença

Creative Commons Attribution-ShareAlude 4.0 (CC BY-SA 4.0) - see [LICENSE](LICENSE)

## 📞 Contato

- **Email:** dionarley@gmail.com
- **Telefone:** +55 38 98424-7486
- **Localização:** Minas Gerais, Brasil

## 🙏 Agradecimentos

- [Font Awesome](https://fontawesome.com) pelos ícones
- Design inspirado em portfólios modernos de desenvolvedores