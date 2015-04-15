# sanji-debpacking
Deb Packing Tool for Sanji Bundles.

## Usage

```
λ ~/sanji-packing -h
usage: sanji-packing [-h] [-c COMMIT] [-o OUTPUT] [-t TEMPDIR] [-r REPO]
                     [-p PREFIX]

Sanji Deb Packing Tool

optional arguments:
  -h, --help            show this help message and exit
  -c COMMIT, --commit COMMIT
                        packing with commit (default: master)
  -o OUTPUT, --output OUTPUT
                        output deb file directory (default: /tmp)
  -t TEMPDIR, --tempdir TEMPDIR
                        temp directory (default: /tmp)
  -r REPO, --repo REPO  Git repository location (default: ${PWD})
  -p PREFIX, --prefix PREFIX
                        Install prefix (default: /opt/moxa/sanji/bundles)
```
