# TubeHaus templates for Unraid Community Applications

Unraid Docker templates for [TubeHaus](https://github.com/biolend83/tubehaus), a self-hosted YouTube client.

| Template | What it is |
|---|---|
| [`templates/tubehaus.xml`](templates/tubehaus.xml) | **TubeHaus**: the server (library, captions, offline saves). No web page of its own. |
| [`templates/tubehaus-web.xml`](templates/tubehaus-web.xml) | **TubeHaus-Web**: the web app and its Caddy router. Set `TUBEHAUS_SERVER` to the server's `IP:3010`. |

Install **both**: TubeHaus first, then TubeHaus-Web, and open `http://[your server]:8796`.

The same pair without templates: [`deploy/docker-compose.home.yml`](https://github.com/biolend83/tubehaus/blob/main/deploy/docker-compose.home.yml) with the Docker Compose Manager plugin.

Support: https://github.com/biolend83/tubehaus/issues
