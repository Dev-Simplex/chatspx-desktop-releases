# chatspx-desktop-releases

Instaladores publicados do app de Windows do Chat SPX. Este repositório não tem código-fonte:
o código fica no repositório privado `chatspx-desktop`.

**Os instaladores não aparecem na lista de arquivos:** ficam anexados a cada release. Para baixar,
abra **Releases** (coluna da direita), escolha a versão e baixe o `.exe` em **Assets**.

Cada release é gerada pelo `npm run release` do `chatspx-desktop` (instalador montado no servidor,
sem GitHub Actions) e traz o instalador (`.exe`), o `latest.yml` e o `min-version.json`, lidos pelo
atualizador automático do app.
