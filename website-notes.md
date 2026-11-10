# Socolola website: working notes

- v1 (9 Nov 2026): landing page, bilingual PT-PT / EN toggle.
- v2–v3: "Equipa" section; Benjamin shown as Benjamin M'bakassy.
- v6–v7: Alba removed from team; team section centred.
- v9: hero carousel = 4 licensed sector stock photos (building construction, road paving with extended sky, open-pit mine, offshore oil platform), 6 s each. Bridge/viaduct photo removed. No photo credits needed.
- 10 Nov 2026: standalone GitHub Pages package built (socolola-website.zip: index.html with full head, assets/, favicon.png, CNAME = socolola.ao, .nojekyll) and sent to Benjamin.
- Brand: wordmark ink #062224, "HOLDING, LDA" teal #075e68. Fonts: Sora (headings), Source Serif 4 (body), IBM Plex Mono (labels).
- Legal name: Socolola Holding – Gestão de Empreendimentos, Lda. Domain: socolola.ao.

## Team on site
| Name | PT | EN |
|---|---|---|
| Dr. António Mbakassy Jr. | Presidente da Comissão Executiva (PCE) | Chief Executive Officer |
| Benjamin M'bakassy | Diretor de Relações Corporativas | Corporate Relations Director |
| Luís Maio | Diretor de Estratégia Corporativa | Corporate Strategy Director |

## Domain, email and hosting
- socolola.ao + 3 email accounts registered via Angoweb (email on cPanel). Benjamin asked Angoweb to move domain + email from the provider's account (geral@grapewareon.com) back to his own Angoweb account. Provider's hosting quote (200,000 AOA/yr) declined.
- Chosen host: GitHub Pages (free; repo must be public on a free plan).
- DNS for GitHub Pages (set in Angoweb / cPanel Zone Editor):
  - A @ → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
  - AAAA @ (optional) → 2606:50c0:8000::153, 2606:50c0:8001::153, 2606:50c0:8002::153, 2606:50c0:8003::153
  - CNAME www → <github-username>.github.io
  - Remove old A record for @ / www pointing to the cPanel server. Keep MX, mail, webmail, autodiscover, SPF/DKIM TXT records.
  - After the switch, webmail via socolola.ao/webmail stops working; use webmail.socolola.ao or Angoweb's webmail address.
  - Optional: verify domain in GitHub account settings (TXT record) to prevent takeover; then tick "Enforce HTTPS".

## Open items before going live
- Contact email on page is still the placeholder geral@socolola.ao; confirm which of the 3 real addresses to show. LinkedIn link is a search URL; get the real page URL. Street address/phone optional.
- Mining and oil & gas photos vs. the four sectors listed on the page (infrastructure, civil construction, real estate, financial structuring): confirm whether to add those sectors or drop the photos.
- Staff photos are low-res (~480 px); ask for originals.
- Content rules: keep Socolola separate from GAM, SOOIL, GOPM and the other family companies; no claimed projects, figures or team size until confirmed.
