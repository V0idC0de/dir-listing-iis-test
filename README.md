# Reproducing the Issue

```shell
nuclei -u https://raw.githubusercontent.com/V0idC0de/dir-listing-iis-test/main/index.html -id dir-listing
```

> This doesn't yield any result currently.

```shell
$ nuclei -u https://raw.githubusercontent.com/V0idC0de/dir-listing-iis-test/main/index.html -id dir-listing

                     __     _
   ____  __  _______/ /__  (_)
  / __ \/ / / / ___/ / _ \/ /
 / / / / /_/ / /__/ /  __/ /
/_/ /_/\__,_/\___/_/\___/_/   2.7.0

                projectdiscovery.io

[WRN] Use with caution. You are responsible for your actions.
[WRN] Developers assume no liability and are not responsible for any misuse or damage.
[INF] Using Nuclei Engine 2.7.0 (latest)
[INF] Using Nuclei Templates 9.0.1 (latest)
[INF] Templates added in last update: 23
[INF] Templates loaded for scan: 1
[INF] No results found. Better luck next time!
```
