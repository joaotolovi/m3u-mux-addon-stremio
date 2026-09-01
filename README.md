<p align="center">
  <img src="https://m3umux.joaotolovi.com/assets/m3u-mux-logo-512.png" alt="M3U Mux" width="160">
</p>

<p align="center">
  <a href="https://go.dev/"><img src="https://img.shields.io/badge/Go-1.26%2B-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"></a>
  <a href="https://www.sqlite.org/"><img src="https://img.shields.io/badge/SQLite-FTS5-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"></a>
  <a href="https://www.stremio.com/"><img src="https://img.shields.io/badge/Stremio-addon-7B5BF2?style=for-the-badge" alt="Stremio"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-yellow?style=for-the-badge" alt="MIT License"></a>
  <a href="https://buymeacoffee.com/joaotolovi"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-support%20the%20project-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee"></a>
</p>

<p align="center">
  <strong>Precise playlist search for Stremio.</strong><br>
  M3U and Xtream in one fast, configurable addon built to find the right title.
</p>

<p align="center">
  <a href="https://m3umux.joaotolovi.com/">Open M3U Mux</a> ·
  <a href="https://buymeacoffee.com/joaotolovi">Support the project</a>
</p>

## What makes M3U Mux different

A large playlist should not return vaguely similar results as if they were correct. M3U Mux combines Stremio and TMDB metadata with your catalog to search for the exact match: the right movie, the right show and, when applicable, the right season and episode.

It is designed to avoid confusion between similar titles, remakes, movies and shows with the same name, or the wrong episode. Once a playlist is indexed, search remains fast.

## Real-catalog benchmark

In a real test using a playlist with **643,000 entries** and 51 manually validated titles:

| Metric | M3U Mux | GhostVOD |
| --- | ---: | ---: |
| Exact matches | **51 / 51** | 34 / 51 |
| Warm search (median) | **25 ms** | 1.53 s |
| Cold search (median) | **124 ms** | 3.99 s |

That is roughly **61× faster for warm searches** and **32× faster for cold searches** in the measured scenario. A warm search is a repeated lookup that can use cache; a cold search measures the first lookup without that benefit.

Results depend on the playlist, provider and network, but the project has a consistent focus: precision before volume, and fast responses without compromising the correct match.

## Features

- M3U, M3U8 and Xtream sources
- Browser-based setup without exposing the playlist in the installation URL
- Up to 10 sources per addon
- IMDb lookup backed by TMDB metadata
- Movie, series, season and episode matching
- Multi-language and alternative-title matching
- Audio language, quality and playlist-group preferences
- Persistent index for fast searches after the initial sync
- Automatic catalog refresh
- An individual link to reconfigure an existing addon
- Compatible with Stremio, Nuvio and WuPlay

## Get started

1. Visit [m3umux.joaotolovi.com](https://m3umux.joaotolovi.com/).
2. Add your M3U or Xtream source.
3. Wait for indexing, then install the generated link in your compatible app.

M3U Mux does not host content or provide playlists. You connect only your own sources.

## Support the project

If M3U Mux helps you, consider supporting its development on [Buy Me a Coffee](https://buymeacoffee.com/joaotolovi).
