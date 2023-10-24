## What Is This?

This is a DNS blocklist that can be used for AdGuardHome. (Does not work with Pi-hole)

This list combines for simple filter lists, including the default lists from
AdGuardHome, into one single list, so you don't have to add countless lists to your
AdGuardHome, but just this one.

## How Can I Use It?

Pretty simple, copy this link
( <https://raw.githubusercontent.com/f97/filter-list/master/filters/full.txt> ) and
add it to your AdGuard Home DNS block lists.

## Which Lists Are Combined Here

Which lists I'm using here, you can see in hostlist compiler configuration:

» [click here](hostlist-compiler-config.json) « or have a look at the table below.

| Name                 | URL                                                                                |
| -------------------- | ---------------------------------------------------------------------------------- |
| OISD Big List        | <https://raw.githubusercontent.com/sjhgvr/oisd/main/oisd_big.txt>                  |
| VNM: ABPVN List      | <https://raw.githubusercontent.com/abpvn/abpvn/master/filter/abpvn.txt>            |
| Bigdargon - hostsVN  | <https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts>                 |
| NoCoin Filter List   | <https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt> |
| Coin Blocker Lists   | <https://zerodot1.gitlab.io/CoinBlockerLists/hosts_browser>                        |
| Easylist Cookie List | <https://secure.fanboy.co.nz/fanboy-cookiemonster.txt>                             |
