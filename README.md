# curlcache.sh
Local cache curl request.

## Usage
```
 curlcache.sh [--cache-timeout minutes] CURLOPTIONS
```

```
 curlcache.sh -h|--help
```


## Options
*  --cache-time minutes 

    Number of minutes for valid cache. 

    Default is 3600.

*  -h | --help 

    Show this help.


## Description
Stores the result of the curl request and if it is repeated in less than minutes it is localment served.




