# Componentes de terceiros

O Baixador traz dentro dele, **sem modificações**, estes programas livres. Cada um segue a sua própria licença:

| Componente | Para quê | Licença | Código-fonte |
|---|---|---|---|
| **yt-dlp** | Baixar do YouTube e de mais de mil sites | [Unlicense](https://github.com/yt-dlp/yt-dlp/blob/master/LICENSE) (domínio público) | [github.com/yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp) |
| **spotDL** | Baixar músicas, álbuns e playlists do Spotify | [MIT](https://github.com/spotDL/spotify-downloader/blob/master/LICENSE) | [github.com/spotDL/spotify-downloader](https://github.com/spotDL/spotify-downloader) |
| **Deno** | Usado pelo yt-dlp para ler o YouTube | [MIT](https://github.com/denoland/deno/blob/main/LICENSE.md) | [github.com/denoland/deno](https://github.com/denoland/deno) |
| **FFmpeg** (ffmpeg e ffprobe) | Juntar vídeo e áudio, converter para MP3 e MP4, pôr a capa | [GPL v3](https://www.gnu.org/licenses/gpl-3.0.html) | [ffmpeg.org](https://ffmpeg.org/download.html) · builds usados: [Mac](https://ffmpeg.martin-riedl.de) e [Windows](https://www.gyan.dev/ffmpeg/builds/) |

Na versão para Windows, a janela usa ainda o [pywebview](https://github.com/r0x0r/pywebview) (BSD), o [Python](https://www.python.org) (PSF) e o Microsoft Edge WebView2, que já vem no Windows.

O FFmpeg é distribuído como um programa separado, sem alterações. O código-fonte exato de cada versão está nos links acima; se precisar dele e não encontrar, peça numa *issue* que enviamos.

O desenho do gato, o ícone e a interface são do autor, Daniel Ribeiro.
