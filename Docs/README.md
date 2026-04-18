# Documentação do Projeto

Este diretório contém a documentação completa do portfólio.

## Arquivos

| Arquivo | Descrição |
|--------|-----------|
| [README.md](README.md) | Visão geral e instalação |
| [DEVELOPER.md](DEVELOPER.md) | Guia para desenvolvedores |
| [AGENTS.md](AGENTS.md) | Regras para agentes IA |

## Estrutura do Projeto

```
portfolio/
├── Docs/              # Documentação
├── index.html        # Página principal
├── styles.css        # Estilos CSS
├── script.js         # JavaScript
├── Dockerfile       # Container Docker
├── nginx.conf       # Configuração nginx
└── docker-compose.yml # Orquestração Docker
```

## Quick Start

```bash
# Desenvolvimento
docker-compose up --build

# Produção
docker-compose up -d portfolio-prod

# Testar
curl http://localhost:8080
```

## Tecnologias

- HTML5 semântico
- CSS3 com variáveis
- JavaScript vanilla
- nginx:alpine
- Docker + Compose