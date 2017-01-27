# eois-tools

## OEIS crawler

```
$ python3.6 crawling.py -h
usage: crawling.py [-h] [--clear-cache] [--restart] [--workers WORKERS]
                   [--log-level {DEBUG,INFO,WARNING,ERROR,CRITICAL}]
                   [--cache-dir CACHE_DIR] [--progress-mark PROGRESS_MARK]
                   [S [S ...]]

OEIS Crawler.

positional arguments:
  S                     Sequence to fetch, given in the form Axxxxxx

optional arguments:
  -h, --help            show this help message and exit
  --clear-cache         Clear cache of sequences, according to --cache-dir
  --restart             Build fringe from cached sequences (defaults to False)
  --workers WORKERS     Degree of parallelism (defaults to 10)
  --log-level {DEBUG,INFO,WARNING,ERROR,CRITICAL}
                        Logger verbosity (defaults to ERROR)
  --cache-dir CACHE_DIR
                        Cache directory (defaults to ./fetched/)
  --progress-mark PROGRESS_MARK
                        Symbol for fetched event (defaults to ●)
```
