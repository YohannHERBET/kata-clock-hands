### Une branche par implémentation du kata réalisée

---

## Objectif

Créez une fonction qui transforme une chaîne représentant une heure sous la forme "HH:MM" en une chaîne qui représente les aiguilles de l'horloge à cette heure-là sous la forme "HA:MA", où "HA" est l'angle (en degrés) de l'aiguille des heures par rapport à la position "12:00", et "MA" est l'angle de l'aiguille des minutes.

### Règles:

1. L'angle entre chaque minute est de 6 degrés (car 360 degrés / 60 minutes = 6 degrés).
2. L'angle entre chaque heure est de 30 degrés (car 360 degrés / 12 heures = 30 degrés).
3. L'aiguille des heures se déplace aussi lorsque les minutes avancent. Par exemple, à "06:30", l'aiguille des heures sera à mi-chemin entre 6 et 7.

### Exemples:

```
getClockAngles("00:00") => "0:0"
getClockAngles("03:00") => "90:0"
getClockAngles("06:30") => "195:180"
getClockAngles("12:45") => "22.5:270"
```

### Remarques:

* Veillez à gérer les cas où l'entrée est invalide (par exemple "25:70").
* Assurez-vous que votre fonction retourne des angles toujours compris entre 0 et 360 degrés.
* Si besoin, arrondissez l'angle des heures à deux décimales.

---

Bonne chance !
