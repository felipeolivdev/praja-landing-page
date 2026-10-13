# ⚡ One Day Landing Page

Landing page (arquivo único em HTML) do serviço **"Faço a página do seu negócio em um dia"**, voltado a startups que precisam validar ideias rapidamente.

## Sobre o projeto

A página apresenta o problema (validar ideias leva tempo demais), a solução (landing page pronta em 24h), o processo em três passos, pacotes de preço e um FAQ. Todos os botões levam a uma conversa no WhatsApp.

> Marca, preços e telefone são **fictícios**. Substitua-os antes de usar de verdade.

## Destaques de design

- Identidade escura com gradiente violeta → ciano, tipografia Space Grotesk + Inter + JetBrains Mono
- Mockup de navegador que "constrói a página" em loop (0h → 24h) com leve efeito 3D ao mover o mouse
- Linha do tempo guiada pelo scroll, cards com spotlight, botões magnéticos e contadores animados
- **Demo ao vivo:** o visitante digita nome e promessa da startup e vê a prévia na hora; o texto vai pré-preenchido no WhatsApp
- Aurora animada, grão sutil, barra de progresso de leitura e animações de entrada
- Responsivo e respeita `prefers-reduced-motion`

## Estrutura

```
.
├── index.html   # Página completa (HTML + CSS + JS inline)
├── README.md
├── LICENSE
└── .gitignore
```

## Tecnologias

- HTML5 e CSS3 (sem frameworks, sem build)
- JavaScript puro, apenas para montar os links do WhatsApp

## Rodando localmente

Não há dependências. Abra o `index.html` no navegador ou sirva a pasta:

```bash
npx serve .
```

## Personalização

| O que mudar | Onde |
|---|---|
| Número do WhatsApp | constante `WHATSAPP_NUMBER` no final do `index.html` (DDI + DDD + número, só dígitos) |
| Telefone exibido | seção "Final CTA" do `index.html` |
| Nome da marca | `<title>`, logo no header e rodapé |
| Preços e pacotes | seção `#pacotes` |
| Cores | variáveis CSS em `:root` |

## Deploy

O projeto é estático e é publicado na [Vercel](https://vercel.com) a partir deste repositório. Cada push na branch `main` gera um novo deploy automaticamente.

## Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE).
