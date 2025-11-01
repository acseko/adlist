
Use this command to reload the configuration
```
/ip/dns/cache flush
:if [/ip/dns/adlist find] do={/ip/dns/adlist reload};
```

