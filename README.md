# Torre de Controle · Logística — mídias da capa

Ativos públicos da capa cinematográfica de um dashboard Power BI de torre de controle logística (visual HTML Content).
O repositório guarda apenas as mídias da capa; o dashboard usa dados fictícios de demonstração.

Capa atual (v3):
- `assets/capa-filme-logistica-*.mp4` — filme de uma operação logística em quatro cenas (centro de distribuição,
  armazém, estrada e entrega) que termina no mapa da Paraíba traçado do Sertão ao litoral; 1920×620, 23 s, H.264, mudo,
  sem laço (o último quadro fica na tela e o dashboard pinta os municípios por cima).
- `assets/poster-inicio-*.jpg`, `assets/palco-vazio-*.jpg`, `assets/palco-mapa-*.jpg` — primeiro quadro, palco sem o
  mapa e último quadro do filme (poster, recorte filtrado e movimento reduzido).
- `assets/papel-de-parede-logistica-*.svg` — ilustração vetorial de traço (torre de controle com feixe de luz,
  galpão, caminhões, caixas e estradas) usada em baixa opacidade na base da capa.
- `assets/manifest.json` — tamanho, SHA-256 e origem de cada arquivo.

Histórico (v2): `assets/capa-loop-logistica-*.mp4` (laço de ~18 s) e `assets/poster-logistica-*.jpg`.

As cenas foram geradas por um modelo de vídeo (Kling 2.5) a partir de roteiro próprio e editadas localmente
(recorte, cor, desfoque de pseudo-textos, dissolves); o mapa final é desenho vetorial da malha municipal do IBGE. A
ilustração foi gerada por IA (Magnific) e estendida e vetorizada no Adobe. Nada aqui é filmagem de um lugar real nem
contém dados, texto, marca ou pessoas identificáveis. Servidos pelo GitHub Pages para que o `<video>` receba
`Accept-Ranges` e respostas `206`.

© Vizu Dados. Uso restrito ao dashboard a que pertencem.
