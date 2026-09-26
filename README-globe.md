# Globe Express — Agência de Viagens Premium

Landing page conceitual para a **Globe Express**, uma marca fictícia de agência de viagens premium. Projeto desenvolvido como case de portfólio (design/direção de arte), simulando um site real de uma empresa de turismo de alto padrão.

## Sobre o projeto

Site com estética dark e acento dourado, inspirada em marcas de turismo de luxo. Cobre toda a jornada de um site de marca de serviços:

- **Hero** full-screen com foto dramática de montanha, localização em destaque e CTAs
- **Cards de destinos** sobrepostos na base do hero — Los Lances, Göreme, Saint Antonien, Nagano
- **Viagens em destaque** — grid assimétrico com dois pacotes: Patagônia Selvagem e Islândia Aurora
- **Barra de estatísticas** — 148+ destinos, 24K viajantes, 17 anos, avaliação 4.9
- **Newsletter CTA** — formulário com interação inline
- **Footer** — navegação, serviços e contato

## Tecnologias

Site estático, sem build nem dependências:

- HTML5 semântico
- CSS puro (custom properties, grid, flexbox)
- Fontes [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) + [DM Sans](https://fonts.google.com/specimen/DM+Sans), via Google Fonts
- Imagens de [Unsplash](https://unsplash.com), sob a [Unsplash License](https://unsplash.com/license), embutidas como base64

## Estrutura

```
.
├── index.html   # site completo (HTML + CSS + imagens embutidas)
└── README.md
```

## Rodando localmente

```bash
git clone https://github.com/kaiqueRoc/globe-express.git
cd globe-express
open index.html
```

## Publicando no GitHub Pages

1. Faça upload do `index.html` para um repositório público no GitHub
2. Vá em **Settings → Pages**
3. Em **Source**, selecione a branch `main` e a pasta `/ (root)`
4. Salve — em alguns minutos o site fica no ar em `kaiqueroc.github.io/globe-express`

## Créditos

- Design e desenvolvimento: **Kaique**
- Projeto conceitual/fictício, criado para fins de portfólio — a marca Globe Express não existe
- Fotografias: Unsplash (licença livre para uso)
