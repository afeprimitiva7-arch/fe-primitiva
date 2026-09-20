# Fé Primitiva

Site de estudos bíblicos — https://afeprimitiva.com

## Tecnologia

- Astro
- Cloudflare
- Conteúdo em Markdown
- Estrutura preparada para CMS Git-based

## Como adicionar um estudo

Crie um arquivo `.md` em `src/content/estudos/` com:

```yaml
---
title: "Título"
description: "Descrição curta"
categoria: "deus"
subtema: "Nome do subtema"
data: 2026-09-15
destaque: false
referencias:
  - "Referência 1"
  - "Referência 2"
---
```

Depois escreva o conteúdo em Markdown.

## Próxima etapa

Conectar um CMS Git-based ao repositório para que os estudos possam ser criados e editados por uma interface gráfica, sem alterar código.

O link do Google Forms do Discipulado ainda precisa ser fornecido para ser colocado no botão da página.
