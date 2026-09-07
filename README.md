# homebrew-tools

Tap oficial de [sistematlan](https://sistematlan.com) para Homebrew.

## Uso

```sh
brew tap sistematlan/tools
brew install mistah
```

o directo, sin tap explícito:

```sh
brew install sistematlan/tools/mistah
```

> **Nota:** este tap solo funciona en macOS. Homebrew Casks (el
> mecanismo que usamos para distribuir binarios precompilados) no
> existe en Linuxbrew — usuarios de Linux deben instalar `mistah` vía
> `curl | sh` o `go install`, ver
> [README de mistah](https://github.com/sistematlan/mistah#instalación).

## Casks

| Cask | Descripción |
|---|---|
| [`mistah`](Casks/mistah.rb) | CLI open-source multiplataforma que recupera espacio en disco: cachés, papelera, backups viejos y más. Sin telemetría, código auditable. |

Los casks en este tap se actualizan automáticamente vía
[GoReleaser](https://goreleaser.com) en cada release de sus respectivos
proyectos — no se editan a mano. Ver `.goreleaser.yaml` en
[sistematlan/mistah](https://github.com/sistematlan/mistah) para el
mecanismo exacto.

## Licencia

Cada cask respeta la licencia del proyecto que empaqueta. Este tap
en sí (metadata, no el software empaquetado) es MIT.
