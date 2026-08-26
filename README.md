# Site institucional — Accanta Tec

Site estático da Accanta Tec, pronto para publicação na raiz do domínio
[accanta.com.br](https://accanta.com.br).

## Conteúdo

- `index.html` — página inicial (Accanta Compras)
- `demonstracao.html` — demonstração de um ciclo completo de compra
- `termos.html` — Termos de Uso e Política de Privacidade
- `og-accanta.jpg` / `og-demo.jpg` — imagens Open Graph (1200×630) referenciadas
  pelas meta tags de `index.html` e `demonstracao.html`

## Observações

- Sem build e sem dependências locais; a única dependência externa é o
  Google Fonts (CDN).
- Os arquivos devem ficar na raiz do domínio — os links internos e as
  imagens Open Graph usam caminhos absolutos (`/demonstracao.html`,
  `/termos.html`, `https://accanta.com.br/og-*.jpg`).
- As três páginas estão com `noindex, nofollow` até a liberação da marca.
