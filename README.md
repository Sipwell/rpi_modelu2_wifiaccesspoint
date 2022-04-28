# WiFi Accesspoint & Hotspot

## Beschrijving
Project om van de Raspberry Pi een WiFi Access Point & Hotspot te maken

## Hardware
- Raspberry Pi 4B
- WiFi USB module

## Software
- WiFi Access Point met Network Manager (https://raspberry2.pindanet.be/inhoud.php)

## Issues
- Problemen met WiFi ontvangen & broadcasten -> Wlans veranderd (https://www.reddit.com/r/archlinux/comments/l2kv1o/set_networkmanager_to_use_wlan1_over_wlan0/)
- WiFi wou niet verbinden -> NMCLI aangepast (https://www.makeuseof.com/connect-to-wifi-with-nmcli/)
- Problemen met verkeerde Wlans -> Wlans gedelete (nmcli connection delete id <connection name>)
  
## Project geslaagd & Thuis toegepast
- Signaal zeer sterk, doch zeer trage verbinding bij verbinding via de hotspot
