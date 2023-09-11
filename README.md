# Install MLKit

This action installs MLKit in a Linux-based GitHub Actions runner.
The compiler is installed in `$HOME/.local`, which means it will be on
the `$PATH` of a standard setup.

## Inputs

`version`

The full version to install as a string (e.g. `'4.7.3'`), or the
string `'latest'`.

## Example usages

```
      - uses: diku-dk/install-mlkit@v1
        with:
          version: '4.7.3'
```

```
      - uses: diku-dk/install-mlkit@v1
```

```
      - uses: diku-dk/install-mlkit@v1
        with:
          version: 'latest'
```
