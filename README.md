# Combined-Wordlists
A combined wordlists for files and directory discovery

current count (TBE): 829,522

This a combined wordlist of:
* [nullenc0de](https://gist.githubusercontent.com/nullenc0de/96fb9e934fc16415fbda2f83f08b28e7/raw/146f367110973250785ced348455dc5173842ee4/content_discovery_nullenc0de.txt)
* [Jason Haddix](https://gist.githubusercontent.com/jhaddix/b80ea67d85c13206125806f0828f4d10/raw/c81a34fe84731430741e0463eb6076129c20c4c0/content_discovery_all.txt)
* [Seclists Web Content](https://github.com/danielmiessler/SecLists/tree/master/Discovery/Web-Content)
* [web-fuzz-wordlist](https://github.com/kaimi-io/web-fuzz-wordlists)

Sorted and compile into one for [dirsearch](https://github.com/maurosoria/dirsearch)

`python3 ~/dirsearch/dirsearch.py -u domain.tld -t 200 -e * -w newlist.txt --plain-text-report output.txt`

of course, It will take time :D

Credits all goes to this creators of this wordlists :)
