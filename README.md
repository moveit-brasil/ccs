# Instruções para Contribuição

Os repositórios agora usam *BRANCHES*. Você está na Branch correta!

### Organização dos Arquivos:

O arquivo principal que é acessado pelos scripts (RCS, p³, p0) é o ["ccs.json"](../blob/gh-pages/ccs.json)

O ccs.json dirá aos scripts para carregar o arquivo de css que está declarado pelo atributo ["ccs"](../blob/gh-pages/ccs.json#L5), na linha 5. Neste caso diremos aos scripts para carregar o arquivo ["room_theme.css"](../blob/gh-pages/room_theme.css).

Dentro deste arquivo, ele tomará conta de carregar os outros 2:
1. ["style.css"](../blob/gh-pages/style.css)
2. "users.css"