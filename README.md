
This is my private list in the [hosts](hosts) file, I also use the following list: https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts

Use this command to reload the configuration:
```
/ip/dns/cache flush
:if [/ip/dns/adlist find] do={/ip/dns/adlist reload};
```

Note:
It's not mandatory to use reload to update the lists, Adlist checks for new updates once every four hours.
https://help.mikrotik.com/docs/spaces/ROS/pages/37748767/DNS#DNS-adlistAdlist
