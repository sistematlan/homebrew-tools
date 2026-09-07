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

## Fórmulas

| Fórmula | Descripción |
|---|---|
| [`mistah`](Formula/mistah.rb) | CLI open-source multiplataforma que recupera espacio en disco: cachés, papelera, backups viejos y más. Sin telemetría, código auditable. |

Las fórmulas en este tap se actualizan automáticamente vía
[GoReleaser](https://goreleaser.com) en cada release de sus respectivos
proyectos — no se editan a mano. Ver `.goreleaser.yaml` en
[sistematlan/mistah](https://github.com/sistematlan/mistah) para el
mecanismo exacto.

## Licencia

Cada fórmula respeta la licencia del proyecto que empaqueta. Este tap
en sí (metadata, no el software empaquetado) es MIT.
