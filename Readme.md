# Script to search into the NSE databases

## Description
#### nse script search is a minimal script to help find a diferentes script into the nse database file

## Help Menu

### Nse-Script-Search (0.1)
#### USAGE:
##### search-script [Options] string
#### PARAMETERS:
#####  -s  create the initial scriptdb for future queries
#####  -h  Display this help menu
#####  -n  The string to search
#####  -c  Create a script.db backup for future diff default name scriptbkp.db the files name are defined in config.lua
#### EXAMPLES:
#####  nsearch -n http
#####  nsearch -c /path/script.db/ /path/for/backup
#####  nsearch.lua -s 

## TODO
* Searching for Category
* Create a backup option
* Searching by Author
* Create a pretty output
* Create a file output
