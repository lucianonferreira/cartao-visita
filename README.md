# Cartão de visita – Luciano Nunes Ferreira

Página de cartão de visita profissional de Luciano Nunes Ferreira, Engenheiro Agrônomo (Uberaba-MG). É um site estático em um único arquivo (`index.html`), com CSS embutido e sem dependências externas, otimizado para celular.

O site é servido pelo [Caddy](https://caddyserver.com/) (imagem oficial, versão 2) via Docker.

## Como rodar com Docker

Pré-requisito: Docker com Docker Compose instalado.

```bash
docker compose up -d
```

Depois, acesse: http://localhost:8090

Para parar:

```bash
docker compose down
```

## Arquivos

- `index.html` – a página do cartão de visita
- `docker-compose.yml` – sobe o Caddy servindo esta pasta (somente leitura) na porta 8090
