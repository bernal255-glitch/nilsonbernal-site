# nilsonbernal.com

Site estático (HTML puro, sem build) publicado no Netlify, projeto `kaleidoscopic-rugelach-04da29`.

| URL | Arquivo | Idioma |
|---|---|---|
| `/` | `index.html` | Português |
| `/en/` | `en/index.html` | English |
| `/es/` | `es/index.html` | Español |
| `/guia.html` · `/guide.html` · `/guia-es.html` | guias do proprietário | PT · EN · ES |

## Publicar
Gere a pasta de deploy a partir do git, o que exclui automaticamente os arquivos internos
(`README.md`, `.gitattributes`, marcados como `export-ignore`):

```sh
rm -rf /tmp/deploy && mkdir /tmp/deploy && git archive HEAD | tar -x -C /tmp/deploy
```

Depois publique a pasta `/tmp/deploy` no Netlify. Se publicar arrastando a pasta no painel,
não inclua o `README.md` nem a pasta `.git`.

## Formulários (Netlify Forms)
`hotel-owner`, `investor`, `general-manager` (contato) e `scan-leads` (resultado do Scan).
