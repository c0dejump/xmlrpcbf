# xmlrpc_bf

bruteforce xmlrpc.php users

# TODO
- [ ] if "wp-json/wp/v2/users" not found try other url like "?author=1"

# Usage:

>
  usage: xmlrpc_bf.py [-h] [-u URL] [-w WORDLIST] [-s TIME_SLEEP] [--user USER] [-a USER_AGENT] [-rs]

  optional arguments:
  -h, --help     show this help message and exit
  -u URL         URL to scan [required]
  -w WORDLIST    Wordlist used for URL Fuzzing [required]
  -s TIME_SLEEP  timesleep if it's must fast
  --user USER    if you know the user
  -a USER_AGENT  Choice user-agent
  -rs            read source
  
>
