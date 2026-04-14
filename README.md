# ldraw-parts

Mirror of the [official LDraw parts library](https://library.ldraw.org/) for CDN access via [jsdelivr](https://www.jsdelivr.com/).

Synced daily from `library.ldraw.org/library/updates/complete.zip` by [GitHub Actions](.github/workflows/sync.yml). The action checks the upstream ETag first and skips if nothing has changed.

## Usage

```
https://cdn.jsdelivr.net/gh/kulits/ldraw-parts@master/ldraw/
```

Pin to a commit SHA for integrity:
```
https://cdn.jsdelivr.net/gh/kulits/ldraw-parts@<sha>/ldraw/
```

## License

All LDraw content is redistributable under [CCAL 2.0](https://www.ldraw.org/article/593) — see `ldraw/CAlicense.txt` and `ldraw/CAreadme.txt`.
