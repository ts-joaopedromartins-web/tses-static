# TS Imóveis — versão estática para aprovação

Versão **temporária** do site (só HTML, CSS, JS e fotos), gerada em 16/10/2026 a partir do sistema completo
(repositório `tses-site-projeto`), para o cliente aprovar num ambiente de teste.

- **Páginas:** a home e as 7 casas reais (TSC-00001 a TSC-00007). Os demais links do site (lista de imóveis,
  condomínios, bairros, privacidade, termos) mostram o aviso "disponível na versão final".
- **"Quero construir"** leva para https://lp.tses.com.br/.
- **Fora do Google:** `robots.txt` bloqueia tudo e as páginas têm `noindex`.

## Como publicar
Copiar o conteúdo deste repositório para a **raiz** de um domínio ou subdomínio (na Hostinger: dentro da
`public_html` do subdomínio). Não funciona dentro de uma subpasta (`dominio.com.br/teste/`), porque os
caminhos começam na raiz (`/build/...`, `/imoveis/...`).

Para testar no computador: `php -S localhost:8080` dentro desta pasta e abrir http://localhost:8080.

## Não editar aqui
Este repositório é só uma "foto" do site. Mudanças de conteúdo ou visual vão no sistema (`tses-site-projeto`)
e a versão estática é gerada de novo.
