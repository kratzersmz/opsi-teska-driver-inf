# opsi-teska-driver-inf

pnputil.exe /export-driver * C:\test

die Treiber liegen dann unter C:\test


diese Treiber dann in *\drivers\kopieren oder hier einen unterordner stellen mit namen vom gerät, z.b. a555 und hier die Ordner reinkopieren. In den Product Properties von teska-driver-inf dann in diesem Fall a555 einstellen. Somit lädt er nur Treiber aus diesem Verzeichnis

Neue Funktionen:
* Zertifikate könnten im Dir certs abgelegt werden und werden vor Installation des Treibers installiert
* neue Opsi Property für remove driver. Dies ist sinnvoll, wenn man z.B. einen Treiber vom System löschen möchte. Aktueller Einsatzzweck ist hier mblock mit seinem Bluetooth 5 Problem. Macht sowas ähnliches wie das zadig tool, wenn man die serial bluetooth im Driver dir hinterlegt....

