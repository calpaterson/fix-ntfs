# fix-nfts

Mass change filenames with characters that cause problems on NTFS.

Initial usecase was to get a syncthing folder working between Linux and
Windows.

```
Usage: fix-ntfs [OPTIONS] FILEPATH

  Rename files that cause problems on ntfs

Options:
  --dry-run
  --help     Show this message and exit.
```

Depends on [click](https://click.palletsprojects.com/en/8.0.x/), so on Debian
do `apt install python3-click`.
