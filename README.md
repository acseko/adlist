
This is my private list in the [hosts](hosts) file, I also use the following list: https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts

Use this command to reload the configuration
```
/ip/dns/cache flush
:if [/ip/dns/adlist find] do={/ip/dns/adlist reload};
```

