# ⚡ PraJá.studio

> **⚠️ Protótipo fictício, feito para fins de estudo e didáticos.**
> A marca **PraJá.studio**, os pacotes, os preços, os prazos, as condições de pagamento e o número de WhatsApp `(00) 00000-0000` são **inventados**. Este projeto não representa um negócio real nem oferece nenhum serviço.

> **Quer uma página pro seu negócio? É PraJá.**

Landing page (arquivo único em HTML) do estúdio fictício **PraJá.studio**, que entrega páginas em 24 horas para startups que precisam validar ideias rapidamente.

🔗 **Demo:** https://praja-studio.vercel.app

## Objetivo

Praticar e demonstrar a criação de uma landing page moderna usando apenas HTML, CSS e JavaScript puros: identidade visual consistente, animações, interações e responsividade, sem frameworks nem etapa de build.

## Destaques de design

- Identidade escura com gradiente violeta → ciano; tipografia Space Grotesk, Inter e JetBrains Mono
- Mockup de navegador que "constrói a página" em loop (0h → 24h), com leve efeito 3D ao mover o mouse
- Linha do tempo guiada pelo scroll, cards com spotlight, botões magnéticos e contadores animados
- **Briefing ao vivo:** o visitante preenche nome, ideia e prazo, vê a prévia na hora e a mensagem já sai pronta para o WhatsApp
- **Comparação** agência × no-code × PraJá, **horário de corte** e explicação de como cabe tudo em um dia
- **Galeria** de quatro páginas de exemplo (lista de espera, pré-venda, SaaS e evento), todas fictícias
- **Painel de resultados** ilustrativo e seção de garantias (código, hospedagem, custos e entrada)
- Chamadas para ação ao longo da página e barra fixa de WhatsApp no celular
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
- JavaScript puro, para animações, interações e para montar os links do WhatsApp

## Rodando localmente

Não há dependências. Abra o `index.html` no navegador ou sirva a pasta:

```bash
npx serve .
```

## Personalização

| O que mudar | Onde |
|---|---|
| Número do WhatsApp | constante `WHATSAPP_NUMBER` no final do `index.html` (DDI + DDD + número, só dígitos) |
| Telefone exibido | seção final (`.phone`) do `index.html` |
| Nome da marca | `<title>`, logo no header e rodapé |
| Preços e pacotes | seção `#pacotes` |
| Cores | variáveis CSS em `:root` |

## Deploy

O projeto é estático e é publicado na [Vercel](https://vercel.com) a partir deste repositório. Cada push na branch `main` gera um novo deploy automaticamente.

## Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE).
