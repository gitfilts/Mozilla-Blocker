# Mozilla-Blocker
#### The Great Blocklists to prevent all Mozilla spying and data collecting efforts on their users.

# Useful only with Systemwide Ad-blockers, DNS Sinkholes and host blocking.

## Filters which allows firefox forks to install and update add-ons from mozilla extension store -
Adguard Home and Zen Privacy Guard -

Windows/Linux host and Android Adaway - 

## No Mozilla Version - Everything is blanket blocked from Mozilla, including Add-ons -
Adguard Home and Zen privacy Guard - 

Windows/Linux host and Android Adaway - 
## Recommended Methods to Block Mozilla
1. DNS Network-wide Adblocker- Adguard Home (best-method)(foss)(dns) - https://github.com/AdguardTeam/AdGuardHome
2. Systemwide Adblocker for Widnows/Linux- Zen Privay Guard (unstable)(foss)(adblock)- https://github.com/anfragment/zen
3. SwitchHosts for Windows (unstable)(foss)(hosts) - https://github.com/oldj/SwitchHosts
4. hosty for Linux (foss)(hosts) - https://github.com/astrovm/hosty
5. personelDNSfilter for Android (no-root)(foss)(hosts)(dns) - https://github.com/IngoZenz/personaldnsfilter
6. Netguard firewall for Android (no-root)(foss)(hosts) - https://github.com/M66B/NetGuard
7. Adaway for Android (root)(foss)(hosts) - https://github.com/AdAway/AdAway
8. Adguard for Android as Dns protection (no-root)(non-foss)(paid-app)(dns) - https://adguard.com/en/adguard-android/overview.html

The adblock filter format works perfectly on Adguard Home.
Zen privacy guard is still early on development so it is unstable when enforcing the filters.
Host rules will work with anything just as a host file for any platform and with blockers that supports host format.
I don't know if the adblock_dns formate of rules will work correctly on pi-hole as I only used Adguard Home and they works fine there. 

## Mozilla also uses Google trackers on their sites which they don't allow adblockers to detect and report to the user
UBlock Origin and uMatrix/nuMatrix can't detect and block google tracking scripts from google-analytics.com and googletagmanager.com on the mozilla site - "Mozilla-Addons", in firefox and modern firefox forks due to policy forced onto extension makers by Mozilla, probably with the excuse of security. Adguard for windows and android also doesn't detect https google tracking request and scripts on mozilla websites like Mozilla Add-ons while using any broswers, even in chrome.

So I don't really recommend relying on Adguard systemwide adblocker for firefox or any of the standard firefox fork users, otherwise Adguard is good for other browser users. In app DNS filterer is still good and will block every trackers without mozilla policy interventions.

Among all the firfox forks, only unique forks like Palemoon and Basilisk doesn't have this sort of forced privacy violating policy enforced on them by Mozilla. But these browsers suffers from performance and stabitlity issues frequently. So blocking Mozilla on system/dns lelvel and using modern firefox forks like librewolf, floorp, zen etc would be more suited to have a regular comfortable usage experience.

uBlock Origin Legacy(ublock fork) and nuMatrix(uMtrix fork) can block google tracking scripts from google-analytics.com and googletagmanager.com on mozilla websites on Palemoon and Basilisk. Blocking these google trackers with a dns adblocker like adguard home and pi-hole should be enough to prevent tracking, but those can't prevent those scripts from running on mozilla websites in firefox or all standard firefox forked browser. For more security and privacy aware people, this can be an issue where regular users would be just fine blocking mozilla systemwide with dns/host blocking.
