# basic_wifi_project
Eine Basisdatei, mit der ihr eure ESP-Projekte starten könnt. Es wird eine Verbindung zum Wlan aufgebaut, ein Webserver und ein DNS-Server eingerichtet und gestartet.

Ändert folgende Zeilen, um sofort loslegen zu können:

```c++
const char* ssid = "wlan_ssid";
const char* password = "wlan_password";

// following for the name of: http://name_esp.local/ 
const char* dns_name = "name_esp";

```
