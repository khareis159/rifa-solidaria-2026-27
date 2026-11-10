# Rifa Solidária 2026-27 — Portal público

Portal somente leitura do sistema **Ação Entre Amigos**. Qualquer pessoa vê as vendas, confere o livro (cadeia SHA-256 + Merkle verificada no próprio navegador) e envia um pedido de reserva pelo WhatsApp do organizador.

Endereço: https://khareis159.github.io/rifa-solidaria-2026-27/

## O que vai neste repositório (público)
- `index.html` — o portal (enviar uma vez)
- `portal.json` — o livro publicado (gerado pela aba **Publicar** do app administrador; reenviar a cada atualização)

## Como publicar
1. No GitHub: Settings → Pages → Branch `main`, pasta `/ (root)`.
2. Add file → Upload files: `index.html`, `.nojekyll`, `.gitignore` e `README.md` (primeira vez).
3. No app administrador (`rifa.html`, só no seu aparelho): aba Publicar → Gerar portal.json → envie ao repositório (Commit).
4. Aguarde 1–10 minutos (cache do GitHub Pages).

## NUNCA envie
O arquivo de backup do app e o `rifa.html`: contêm nomes, telefones e a semente secreta do sorteio. O repositório é público.

© Carlos Alberto Reis 2026 · Apoio PIX 61999487649
