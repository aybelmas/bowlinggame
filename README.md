# Calculateur de Score au Bowling

Ce programme Java permet de calculer le score d'une séquence de lancers au bowling. 

Il suit les règles standard du bowling, en prenant en compte les strikes, les spares et les misses.

## Comment l'utiliser

```bash
# Clonez le dépôt :
git clone https://github.com/aybelmas/bowlinggame.git

# Compilez le fichier Java :
javac BowlingGame.java

# Exécutez les cas de test fournis :
java BowlingGame

Cas de Test :

    Cas de Test 1 : Que des Strikes
        Lancers : "XXXXXXXXXXXX"
        Score Attendu : 300

    Cas de Test 2 : Que des Misses
        Lancers : "9-9-9-9-9-9-9-9-9-9-"
        Score Attendu : 90

    Cas de Test 3 : Que des Spares
        Lancers : "5/5/5/5/5/5/5/5/5/5/5"
        Score Attendu : 150
