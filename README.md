# League of Legends patch notes parser

Parse League of Legends patch notes from leagueoflegends.com into JSON.

Currently supporting patches 8.13 to 8.22.

## Quickstart

Python 3.6 is required.

```sh
# download patch notes (here for patch 8.22)
./leaguepatchnotes download -o patch-notes-8.22.html 8.22
# parse patch notes into JSON
./leaguepatchnotes parse -o patch-notes-8.22.json patch-notes-8.22.html
```

