# robotapp
Prebuilt app

Lokasi executable/built di rpi 5 bookworm :

1. RadarScan : 
/opt/app/radarScan 

Lokasi service systemd 
/etc/systemd/system/radarscan.service


2. RadarScanLocal
/opt/app/radarScamLocal
Lokasi service :
/etc/systemd/system/radarscanlocal.service

Aktivasi
via user pi
 sudo systemctl daemon-reload
 sudo systemctl enable radarscan.service
 sudo systemctl enable radarscanlocal.service
 sudo systemctl start radarscan.service
 sudo systemctl start radarscanlocal.service

 Cek status :
 sudo systemctl status radarscan.service
 sudo systemctl status radarscanlocal.service
