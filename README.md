# homebrew-tzlang

Tap de Homebrew para
[TzLang](https://github.com/TzLanguaje/TzLanguaje), un lenguaje de
programación educativo con sintaxis
en español.

## Instalación

```bash
brew install tzlanguaje/tzlang/tzlang
```

Compila desde el código, así que sirve
para macOS (Intel y Apple Silicon) y
para Linux.

## Comprobar

```bash
tz --version
```

## Actualizar a una versión nueva

En `Formula/tzlang.rb`, cambiar la
`url` a la etiqueta nueva y poner su
`sha256`:

```bash
curl -fsSL https://github.com/TzLanguaje/TzLanguaje/archive/refs/tags/vX.Y.Z.tar.gz | shasum -a 256
```

## Licencia

MIT, igual que TzLang.
