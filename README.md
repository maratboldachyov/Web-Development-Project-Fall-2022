!!!!!!!!! NICHEGO NE HUYARIT' V MASTER VETKU !!!!!!!!!
!!!!!!!!! MASTER ETO PROD VETKA !!!!!!!!!



Algorithm:

    git clone {Https...}

    <Yesli byli izmeneniya v master, to delayem>

    git pull origin master


    <Daleye>:

    git checkout -b Marat     # Vashe imya

    git add .

    git status   # proverka na pravil'nost' zalitiya files

    git commit -m "Marat: Fixed/Added"     # Nazvaniye Svoyey Vetki: Chto Vy Sdelali (Eto nuzhno, chtoby ne yebat'sya, a tupo otkatit'sya po nuzhnomu commitu)

    git push -u origin Marat


    Yesli zalivayete ne v perviy raz:
    
    git checkout Marat
    git add .
    git commit -m "Marat: Added authentification"
    git push origin Marat
    
Kasatel'no master vetki. Pered zashitoy delayem merge v master i proveryayem vse li ok. V processe, yesli ponadobitsya sdelat' merge, pishite mne.




