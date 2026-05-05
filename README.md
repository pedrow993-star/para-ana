# Para Ana ♥

Página de uma só folha com animação de um **Coração Infinito em 3D** (Three.js), partículas flutuantes, brilho dinâmico e interações ao toque. Um design premium e elegante inspirado na "declaração infinita".

## ✨ Características

- **Coração 3D em Partículas**: Milhares de pontos formando um volume 3D pulsante.
- **Paleta Rose Gold**: Cores em tons de rosa, creme, dourado e branco.
- **Interatividade**: Toque ou clique para criar explosões de luz e pulsar o coração.
- **Tipografia Elegante**: Uso de fontes serifadas (Cormorant Garamond) para um toque clássico.
- **Performance**: Otimizado para dispositivos móveis com aceleração de hardware (WebGL).

## 📂 Arquivos

- `index.html` — O código completo (HTML + CSS + JS/Three.js).
- `robots.txt` — Permite indexação pelos motores de busca.
- `sitemap.xml` — Mapa do site para SEO.
- `.nojekyll` — Desativa o Jekyll no GitHub Pages.
- `README.md` — Este arquivo.

## 🚀 Como hospedar no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `para-ana`).
2. Suba os arquivos desta pasta para a branch `main`.
3. Vá em **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch**.
5. Selecione branch `main` e pasta `/ (root)`. Salve.
6. A URL será: `https://SEU-USUARIO.github.io/para-ana/`

### 💡 Antes de publicar
Edite `robots.txt` e `sitemap.xml` substituindo a URL base pela URL final do seu site.

## 🎨 Personalização

Tudo está concentrado no `index.html`:

- **Nome "Ana"**: Procure por `para<span class="dot"></span>Ana` e altere.
- **Mensagem**: Altere o conteúdo dentro de `<p class="message">`.
- **Cores**: A paleta está na variável `const palette` no script.
- **Densidade**: Altere `HEART_COUNT` para mais ou menos partículas no coração.

---

Feito com ♥ e Three.js.
