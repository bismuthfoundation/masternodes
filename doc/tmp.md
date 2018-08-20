# Temp Instructions

DO NOT USE YET, For team purposes only.

## Bismuth node

I suppose you already have a regular Bismuth node installed.  
We'll suppose it lies in you home dir, then Bismuth  
`~/Bismuth`

## Getting the Archive

move to your home dir  
`cd
wget url_of_the_tar.gz
tar -zxvf hypernode.tar.gz
cd hypernode
`

## Python stuff

Python 3.6+ required  
Install prerequisites:  
`pip3 install -r requirements`

## Config

`cd main`

If your bismuth install is not in the default directory, give the path:  
`nano config.txt`
add a line:
`POW_LEDGER_DB=/path/to/the/ledger.db`

You can forget the config.txt if the install is standard.

## First check

run
`python3 hn_check.py`

This will
- create a new poswallet.json
- display some info
- check the ledger.db is readable


