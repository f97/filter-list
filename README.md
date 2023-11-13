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

| Name                             | URL                                                                                                                         |
| -------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| f97.xyz                          | <https://raw.githubusercontent.com/f97/filter-list/master/f97.txt>                                                          |
| OISD Big List                    | <https://raw.githubusercontent.com/sjhgvr/oisd/main/oisd_big.txt>                                                           |
| VNM: ABPVN List                  | <https://raw.githubusercontent.com/abpvn/abpvn/master/filter/abpvn.txt>                                                     |
| Bigdargon - hostsVN              | <https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts>                                                          |
| FMSF 2                           | <https://raw.githubusercontent.com/nmtrung/FMSF-2.0/master/fmsf_2.0.txt>                                                    |
| NoCoin Filter List               | <https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt>                                          |
| Coin Blocker Lists               | <https://zerodot1.gitlab.io/CoinBlockerLists/hosts_browser>                                                                 |
| Adguard Cookie List              | <https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/AnnoyancesFilter/Cookies/sections/cookies_general.txt> |
| Adguard Mobile                   | <https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/MobileFilter/sections/adservers.txt>                   |
| Adguard Base                     | <https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/BaseFilter/sections/adservers.txt>                     |
| NextDNS CNAME Cloaking Blocklist | <https://raw.githubusercontent.com/nextdns/cname-cloaking-blocklist/master/domains>                                         |
| NextDNS Privacy - Alexa          | <https://raw.githubusercontent.com/nextdns/native-tracking-domains/main/domains/alexa>                                      |
| NextDNS Privacy - Apple          | <https://raw.githubusercontent.com/nextdns/native-tracking-domains/main/domains/apple>                                      |
| NextDNS Privacy - Huawei         | <https://raw.githubusercontent.com/nextdns/native-tracking-domains/main/domains/huawei>                                     |
| NextDNS Privacy - Roku           | <https://raw.githubusercontent.com/nextdns/native-tracking-domains/main/domains/roku>                                       |
| NextDNS Privacy - Samsung        | <https://raw.githubusercontent.com/nextdns/native-tracking-domains/main/domains/samsung>                                    |
| NextDNS Privacy - Sonos          | <https://raw.githubusercontent.com/nextdns/native-tracking-domains/main/domains/sonos>                                      |
| NextDNS Privacy - Windows        | <https://raw.githubusercontent.com/nextdns/native-tracking-domains/main/domains/windows>                                    |
| NextDNS Privacy - Xiaomi         | <https://raw.githubusercontent.com/nextdns/native-tracking-domains/main/domains/xiaomi>                                     |
| 1Hosts (mini)                    | <https://o0.pages.dev/mini/adblock.txt>                                                                                     |
| GoodbyeAds AdBlock Filter        | <https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Formats/GoodbyeAds-AdBlock-Filter.txt>                        |
| EasyList                         | <https://easylist.to/easylist/easylist.txt>                                                                                 |
| Smart-TV Blocklist               | <https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV-AGH.txt>                                         |
| Anti-AD                          | <https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-adguard.txt>                             |
| HaGeZi's Personal DNS            | <https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/personal.txt>                                         |
| Pi Hole TikTok                   | <https://raw.githubusercontent.com/ftpmorph/ftprivacy/master/blocklists/tiktok-full-block-ftpihole.txt>                     |
| Pi Hole Smart TV                 | <https://raw.githubusercontent.com/ftpmorph/ftprivacy/master/blocklists/smart-tv-ads-tracking.txt>                          |
| Pi Hole Smart Phone              | <https://raw.githubusercontent.com/ftpmorph/ftprivacy/master/blocklists/smartphone-ads-tracking.txt>                        |
