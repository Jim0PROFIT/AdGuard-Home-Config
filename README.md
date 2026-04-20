# Liste de filtres autorisés — AdGuard Home
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Status](https://img.shields.io/badge/Maintenance-personal-blue)
![AdGuard Home](https://img.shields.io/badge/AdGuard%20Home-allowlist-00a57e)

Dépôt contenant ma liste personnelle de domaines autorisés pour AdGuard Home.  
Objectif : corriger les faux positifs, débloquer certains services et garder une configuration propre.

## Contenu

| Fichier | Description | Domaines |
|---|---|---|
| [01_perso.txt](filters/01_perso.txt) | Services personnels (Freebox, Canal+, TikTok, LinkedIn, Alexa…) | 56 |
| [02_piracy.txt](filters/02_piracy.txt) | Sites bloqués (piraterie) | 2 |
| [03_homelab.txt](filters/03_homelab.txt) | HomeLab (SMLIGHT, Grafana, Netdata, Synology…) | 12 |
| [04_boinc.txt](filters/04_boinc.txt) | BOINC / BoincStats | 5 |
| [05_dns.txt](filters/05_dns.txt) | DNS (Quad9, DNSCrypt) | 4 |
| [06_google_location.txt](filters/06_google_location.txt) | Whitelist Google Location Sharing | 15 |
| [07_nvidia.txt](filters/07_nvidia.txt) | Nvidia GeForce | 1 |
| [08_ea_games.txt](filters/08_ea_games.txt) | EA Games + Rockstar + Epic Game Store | 9 |
| [09_microsoft.txt](filters/09_microsoft.txt) | Microsoft (général, Windows Updates, Insider, Ubiquiti, Firefox, Canon, Dropbox) | 52 |
| [10_o365.txt](filters/10_o365.txt) | Microsoft O365 / Azure AD / Teams / SharePoint | 93 |
| [11_google.txt](filters/11_google.txt) | Google (Discover, Notifications, Family) | 4 |
| [12_adobe.txt](filters/12_adobe.txt) | Adobe | 5 |
| [13_nordvpn.txt](filters/13_nordvpn.txt) | NordVPN | 10 |
| [14_x_twitter.txt](filters/14_x_twitter.txt) | X / Twitter | 2 |
| [15_yahoo.txt](filters/15_yahoo.txt) | Yahoo | 3 |
| [16_netdata.txt](filters/16_netdata.txt) | Netdata Cloud | 6 |
| [17_domotique.txt](filters/17_domotique.txt) | Domotique (Netatmo, Hoymiles, Météo-France, RTE, Ariston…) | 9 |
| [18_work.txt](filters/18_work_scc.txt) | Travail — SCC / Randstad / Concur | 9 |
| [19_xxxx](filters/19_xxxx) | xxxx — xxxx / xxxx | x |
| [20_epic.txt](filters/20_epic.txt) | Epic Games (data router, perf store) | 2 |
| [21_misc.txt](filters/21_misc.txt) | Divers (Microsoft Azure, Weward, Intel, Hoymiles, Candy Crush…) | 13 |
| [22_winamax.txt](filters/22_winamax.txt) | Winamax | 5 |

- **changelog.md** — Notes rapides sur les modifications.
- **sources.md** — Références des listes externes.

## Utilisation

Dans AdGuard Home → *Settings* → *DNS Allowlist*, ajouter chaque fichier souhaité :

```
https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/filters/01_perso.txt
https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/filters/03_homelab.txt
...
```

> Pour importer l'ancienne liste complète (non splitée) :
> `https://github.com/Jim0PROFIT/AdGuard-Home-Config/blob/main/adguardhome-allowlist.txt`

## Notes

- Usage strictement personnel.
- Mises à jour selon les besoins.
- Dépôt public uniquement pour faciliter la synchronisation.

---

# Allowed Filters List — AdGuard Home
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Status](https://img.shields.io/badge/Maintenance-personal-blue)
![AdGuard Home](https://img.shields.io/badge/AdGuard%20Home-allowlist-00a57e)

This repository contains my personal allowlist for AdGuard Home.  
Goal: fix false positives, unblock legitimate services, and keep a clean DNS configuration.

## Contents

| File | Description | Domains |
|---|---|---|
| [01_perso.txt](filters/01_perso.txt) | Personal services (Freebox, Canal+, TikTok, LinkedIn, Alexa…) | 56 |
| [02_piracy.txt](filters/02_piracy.txt) | Blocked sites (piracy) | 2 |
| [03_homelab.txt](filters/03_homelab.txt) | HomeLab (SMLIGHT, Grafana, Netdata, Synology…) | 12 |
| [04_boinc.txt](filters/04_boinc.txt) | BOINC / BoincStats | 5 |
| [05_dns.txt](filters/05_dns.txt) | DNS (Quad9, DNSCrypt) | 4 |
| [06_google_location.txt](filters/06_google_location.txt) | Google Location Sharing whitelist | 15 |
| [07_nvidia.txt](filters/07_nvidia.txt) | Nvidia GeForce | 1 |
| [08_ea_games.txt](filters/08_ea_games.txt) | EA Games + Rockstar + Epic Game Store | 9 |
| [09_microsoft.txt](filters/09_microsoft.txt) | Microsoft (general, Windows Updates, Insider, Ubiquiti, Firefox, Canon, Dropbox) | 52 |
| [10_o365.txt](filters/10_o365.txt) | Microsoft O365 / Azure AD / Teams / SharePoint | 93 |
| [11_google.txt](filters/11_google.txt) | Google (Discover, Notifications, Family) | 4 |
| [12_adobe.txt](filters/12_adobe.txt) | Adobe | 5 |
| [13_nordvpn.txt](filters/13_nordvpn.txt) | NordVPN | 10 |
| [14_x_twitter.txt](filters/14_x_twitter.txt) | X / Twitter | 2 |
| [15_yahoo.txt](filters/15_yahoo.txt) | Yahoo | 3 |
| [16_netdata.txt](filters/16_netdata.txt) | Netdata Cloud | 6 |
| [17_domotic.txt](filters/17_domotic.txt) | Home automation (Netatmo, Hoymiles, Météo-France, RTE, Ariston…) | 9 |
| [18_work_scc.txt](filters/18_work_scc.txt) | Work — SCC / Randstad / Concur | 9 |
| [19_xxxx](filters/19_xxxx) | xxxx — xxxx / xxxx | x |
| [20_epic.txt](filters/20_epic.txt) | Epic Games (data router, perf store) | 2 |
| [21_misc.txt](filters/21_misc.txt) | Misc (Microsoft Azure, Weward, Intel, Hoymiles, Candy Crush…) | 13 |
| [22_winamax.txt](filters/22_winamax.txt) | Winamax | 5 |

- **changelog.md** — Quick notes on changes.
- **sources.md** — External list references.

## Usage

In AdGuard Home → *Settings* → *DNS Allowlist*, add each desired file:

```
https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/filters/01_perso.txt
https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/filters/03_homelab.txt
...
```

> To import the original full list (pre-split):
> `https://github.com/Jim0PROFIT/AdGuard-Home-Config/blob/main/adguardhome-allowlist.txt`

## Notes

- Maintained for personal use only.
- Updated when needed.
- Public repo only for easy syncing.
