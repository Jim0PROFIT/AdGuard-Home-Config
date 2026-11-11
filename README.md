# AdGuard Home — listes d'autorisation DNS

![Maintenance](https://img.shields.io/badge/Maintenance-personal-blue)
![AdGuard Home](https://img.shields.io/badge/AdGuard%20Home-allowlist-00a57e)

Dépôt personnel de règles d'autorisation DNS pour AdGuard Home. Les domaines sont ajoutés à partir de besoins constatés dans mon réseau afin de corriger des faux positifs ou de permettre le fonctionnement de services et d'équipements utilisés.

## Fichiers maintenus

Tous les fichiers ci-dessous se trouvent à la racine du dépôt. Les URL directes peuvent être ajoutées dans AdGuard Home → Filtres → Listes d'autorisation DNS.

| Fichier | Usage |
|---|---|
| [01_perso.txt](01_perso.txt) | Services et équipements personnels |
| [02_piracy.txt](02_piracy.txt) | Exceptions liées aux domaines French-TV |
| [03_homelab.txt](03_homelab.txt) | HomeLab, Grafana, Synology et services associés |
| [04_boinc.txt](04_boinc.txt) | BOINC et BOINCstats |
| [05_dns.txt](05_dns.txt) | Quad9 et DNSCrypt |
| [06_google_location.txt](06_google_location.txt) | Google Location Sharing et services de localisation |
| [07_nvidia.txt](07_nvidia.txt) | NVIDIA GeForce |
| [08_games.txt](08_games.txt) | EA, Rockstar, Epic et PlayStation |
| [09_microsoft.txt](09_microsoft.txt) | Windows, mises à jour et services Microsoft |
| [10_o365.txt](10_o365.txt) | Microsoft 365, Exchange, Teams et SharePoint |
| [11_google.txt](11_google.txt) | Google, Family et Android |
| [12_adobe.txt](12_adobe.txt) | Adobe |
| [13_nordvpn.txt](13_nordvpn.txt) | NordVPN |
| [14_x_twitter.txt](14_x_twitter.txt) | X / Twitter |
| [15_yahoo.txt](15_yahoo.txt) | Yahoo |
| [16_netdata.txt](16_netdata.txt) | Netdata |
| [17_domotique.txt](17_domotique.txt) | Services domotiques |
| [18_work.txt](18_work.txt) | Services professionnels |
| [19_samsung.txt](19_samsung.txt) | Services Samsung |
| [21_misc.txt](21_misc.txt) | Services divers |
| [22_winamax.txt](22_winamax.txt) | Winamax |
| [23_Ubiquiti.txt](23_Ubiquiti.txt) | UniFi / Ubiquiti |
| [24_apple.txt](24_apple.txt) | Apple |
| [lastpass.txt](lastpass.txt) | Services LastPass |

## URLs directes

- [01_perso.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/01_perso.txt)
- [02_piracy.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/02_piracy.txt)
- [03_homelab.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/03_homelab.txt)
- [04_boinc.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/04_boinc.txt)
- [05_dns.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/05_dns.txt)
- [06_google_location.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/06_google_location.txt)
- [07_nvidia.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/07_nvidia.txt)
- [08_games.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/08_games.txt)
- [09_microsoft.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/09_microsoft.txt)
- [10_o365.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/10_o365.txt)
- [11_google.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/11_google.txt)
- [12_adobe.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/12_adobe.txt)
- [13_nordvpn.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/13_nordvpn.txt)
- [14_x_twitter.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/14_x_twitter.txt)
- [15_yahoo.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/15_yahoo.txt)
- [16_netdata.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/16_netdata.txt)
- [17_domotique.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/17_domotique.txt)
- [18_work.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/18_work.txt)
- [19_samsung.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/19_samsung.txt)
- [21_misc.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/21_misc.txt)
- [22_winamax.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/22_winamax.txt)
- [23_Ubiquiti.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/23_Ubiquiti.txt)
- [24_apple.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/24_apple.txt)
- [lastpass.txt](https://raw.githubusercontent.com/Jim0PROFIT/AdGuard-Home-Config/main/lastpass.txt)

## Notes de maintenance

- Ces listes sont personnalisées et doivent rester limitées aux exceptions réellement nécessaires.
- Une règle de domaine générique peut autoriser un domaine et ses sous-domaines ; vérifier la portée avant d'ajouter un joker ou un domaine parent.
- Le modificateur $important augmente la priorité d'une règle face aux règles ordinaires de blocage. Il doit être réservé aux cas qui le nécessitent réellement.
- AdGuard Home ne prend pas en charge le modificateur $app dans ses règles de filtrage DNS. Pour cibler un appareil, utiliser plutôt $client avec un client AdGuard Home configuré.
- Les deux instances AdGuard Home doivent utiliser les mêmes listes pour conserver un comportement cohérent.
- adguardhome-allowlist.txt est une ancienne liste agrégée conservée à titre d'archive. Ne pas l'activer en même temps que les listes individuelles sans vérifier les doublons.

Dépôt public pour faciliter la synchronisation et la maintenance de mes deux instances AdGuard Home.
