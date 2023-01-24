# TD2

## Enoncer
Contexte: TD1 fait avant
1. Lire la documentation spec SPB : sparkplug b
2. Installer NODE-RED en virtualiser (vm rasbery avec node Red pour parcer et mettre en forme)
3. Creer un brocker sur HiveMQ (cloud ou locall peut d'importance)
4. Test    
     NODE-RED ---------- > Broker  
     spBv1.0/  
     metrics [ { name: random, value: nawak} ]
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
