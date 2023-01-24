# TD2

## Enoncer
1. Lire la documentation spec SPB
2. Installer NODE-RED
3. Creer un brocker sur HiveMQ
4. Test  
     NODE-RED ---------- > Broker
     spBv1.0/  
     metrics [  
      { name: random, value: nawak},  
     ]
5. Envoyer les donnée au format :
    ESIEA/grp6  
    {"hum" : x , "temp" : y}  
    spBv1.0/grp6/DDATA/raspberry/esp8266  
    metrics [  
      { name: humidity, value: x},  
      { name: temperature, value Y}  
    ]
6. Creation de graphe

![shema](./ScreenShot/shema.jpeg)
