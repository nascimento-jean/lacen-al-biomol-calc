# Publicação no GitHub Pages

Este pacote está pronto para ser enviado à raiz de um repositório GitHub Pages.

Arquivos importantes:
- `index.html` deve ficar na raiz do repositório ou na raiz da pasta configurada como fonte do Pages.
- `manifest.webmanifest` habilita instalação como PWA.
- `service-worker.js` habilita cache/offline.
- `icons/` contém os ícones do aplicativo.
- `.nojekyll` evita processamento Jekyll desnecessário no GitHub Pages.

Sugestão de repositório:
`lacen-al-biomol-calc`

URL esperada:
`https://nascimento-jean.github.io/lacen-al-biomol-calc/`

Configuração:
Settings > Pages > Build and deployment > Source: Deploy from a branch > Branch: main > Folder: /(root) > Save.
