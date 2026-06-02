# Guarani 360 — Landing Page

Landing page do empreendimento **Guarani 360**, em Itaguá, Ubatuba — SP.
DS2 Empreendimentos.

## Estrutura

```
guarani-360-site/
├── index.html        # Página principal (HTML único, CSS e JS inline)
├── assets/           # Imagens, plantas e logos
└── README.md
```

Sem build step. Basta servir `index.html` estaticamente.

## Stack

- HTML5 + CSS3 (puro, sem framework)
- JavaScript vanilla (carrossel da galeria, abas de plantas, scroll reveal)
- Tipografia: Cormorant Garamond + Plus Jakarta Sans (Google Fonts)
- Mapa: iframe Google Maps embed

## Como rodar localmente

```bash
# Qualquer servidor estático funciona
python3 -m http.server 8000
# ou
npx serve .
```

Depois abra `http://localhost:8000`.

## Deploy

Sobe direto em qualquer host estático — GitHub Pages, Vercel, Netlify, Cloudflare Pages, S3.

### GitHub Pages

1. Push para branch `main`
2. Settings → Pages → Branch: `main` / root
3. Pronto

## Seções

1. Hero — Pré-lançamento
2. O Mercado — Ubatuba como ativo
3. O Produto — refúgio + renda
4. Localização — mapa + pontos próximos
5. Ficha Técnica — 4 tipologias com plantas
6. Infraestrutura — lista editorial de amenidades
7. DS2 — timeline de empreendimentos
8. Galeria — carrossel de fotos
9. Pré-lançamento — formulário de cadastro

## Contato

DS2 Empreendimentos
WhatsApp: (12) 99148-8743
Email: adm@ds2empreendimentos.com.br
Rua Carlos Drumond de Andrade, 300 — Ubatuba, SP
