## Simple srt (or sbv) subtitles to plain text formatter.
``` bash
usage: srt2txt [-h] [-l INT] [-b INT] source destination

SRT (and SBV) → formatted text (smart)

positional arguments:
  source                Input SRT (or SBV) file
  destination           Output text file

options:
  -h, --help            show this help message and exit
  -l INT, --line-length INT
                        Max characters per line
  -b INT, --block-lines INT
                        Target lines per block (won't break sentences)
```
