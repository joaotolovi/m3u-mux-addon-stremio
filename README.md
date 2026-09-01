# M3U Mux

<p align="center">
  <img src="https://m3umux.joaotolovi.com/assets/m3u-mux-logo-512.png" alt="M3U Mux" width="160">
</p>

<p align="center">
  <strong>Busca precisa para a sua playlist no Stremio.</strong><br>
  M3U e Xtream em um addon rápido, configurável e feito para encontrar o título certo.
</p>

<p align="center">
  <a href="https://m3umux.joaotolovi.com/">Abrir M3U Mux</a> ·
  <a href="https://buymeacoffee.com/joaotolovi">Apoiar o projeto</a>
</p>

## O que torna o M3U Mux diferente

Uma playlist grande não deveria entregar resultados parecidos como se fossem certos. O M3U Mux cruza os metadados do Stremio e do TMDB com o seu catálogo para buscar o match exato: filme certo, série certa e, quando aplicável, temporada e episódio certos.

Ele foi construído para evitar confusões entre títulos semelhantes, remakes, filmes e séries com o mesmo nome, ou episódios errados. A busca permanece rápida mesmo depois que a playlist é indexada.

## Benchmark independente de catálogo

Em um teste real com uma playlist de **643 mil entradas** e 51 títulos validados manualmente:

| Métrica | M3U Mux | GhostVOD |
| --- | ---: | ---: |
| Acertos exatos | **51 / 51** | 34 / 51 |
| Busca quente (mediana) | **25 ms** | 1,53 s |
| Busca fria (mediana) | **124 ms** | 3,99 s |

Isso equivale a cerca de **61× mais rápido em busca quente** e **32× mais rápido em busca fria** no cenário medido. Busca quente é uma consulta repetida, usando cache; busca fria mede a primeira consulta, sem esse benefício.

Os resultados dependem da playlist, do provedor e da rede, mas o foco do projeto é constante: precisão antes de volume e resposta rápida sem sacrificar o match correto.

## Recursos

- Fontes M3U, M3U8 e Xtream
- Configuração pelo navegador, sem expor a playlist no link de instalação
- Até 10 fontes por addon
- Busca por IMDb com metadados do TMDB
- Match de filme, série, temporada e episódio
- Títulos em vários idiomas e títulos alternativos
- Preferências de idioma de áudio, qualidade e grupos de playlist
- Índice persistente para buscas rápidas após a primeira sincronização
- Atualização automática do catálogo
- Link individual para configurar novamente um addon já criado
- Compatível com Stremio, Nuvio e WuPlay

## Comece agora

1. Acesse [m3umux.joaotolovi.com](https://m3umux.joaotolovi.com/).
2. Adicione a sua fonte M3U ou Xtream.
3. Aguarde a indexação e instale o link gerado no seu app compatível.

O M3U Mux não hospeda conteúdo nem fornece playlists. Você conecta apenas as suas próprias fontes.

## Apoie o projeto

Se o M3U Mux te ajuda, considere apoiar seu desenvolvimento em [Buy Me a Coffee](https://buymeacoffee.com/joaotolovi).

