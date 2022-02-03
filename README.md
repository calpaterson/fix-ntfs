# fix-nfts

Mass change filenames with characters that cause problems on NTFS.

```
Usage: fix-ntfs [OPTIONS] FILEPATH

  Rename files that cause problems on ntfs

Options:
  --dry-run           Does nothing but prints what would be done.
  --replacement TEXT  Characters not allowed on NTFS are replaced with this
                      string (default: '_').
  --help              Show this message and exit.
```

Initial usecase was to get a syncthing folder working between Linux and
Windows.

Also useful to find problem filenames when run with `--dry-run`.

Depends on [click](https://click.palletsprojects.com/en/8.0.x/), so on Debian
do `apt install python3-click`.
