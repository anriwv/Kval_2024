# Kval_2024
Autor: Anri Sokolov

## Sissejuhatus
 See tarkvaraprojekt on koostatud individuaalse lõputöö raames aastal 2024. Projekti eesmärk on lahendada konkreetne probleem. Projekti käigus viiakse läbi lähteanalüüs, arendustsüklid, testimine ning lõpuks esitletakse valmis lahendust.


 ## Probleemi Sõnastus

Muusikapalade loomine võib olla keeruline, eriti inimestele, kes pole muusikaspetsialistid. Seetõttu on vaja luua lihtne ja kasutajasõbralik rakendus, mis võimaldab igal kasutajal luua oma muusikat ilma keeruliste muusikateooriate tundmata.


## Kasutamine
> git clone https://github.com/anriwv/Kval_2024.git

> python.exe -m pip install --upgrade pip
> 
> pip install -r requirements.txt

> python main.py



Hliifailide saamine:
Kood, et mängida, kõik vajalikud noodid (korduvalt- uga instrumendi jaoks)

![Valmistamine](https://github.com/anriwv/Kval_2024/raw/main/scr/3min.png){:height="400"}


Xml fail. Exportisin ja sain 3 minutilise faili.

![Klaver](https://github.com/anriwv/Kval_2024/raw/main/scr/Klaver.png){:height="400"}


Jagasin osadeks. (iga fail - 2 sek.)

![Valmistamine](https://github.com/anriwv/Kval_2024/raw/main/scr/valmistamine.png){:height="300"}



Nüüd on mitu kausta. Igas kaustas 88 faili.


Prototüübiks oli

![Prototype](https://github.com/anriwv/Kval_2024/raw/main/scr/prototype.png){:height="300"}



Ning lõpptulemus on:

![Final](https://github.com/anriwv/Kval_2024/raw/main/scr/Final.png){:height="300"}


See suudab:
- mängida korraga rohkem kui ühel oktavil
- vahetada oktave
- vahetada instrumente
- salvestada mängitud pala
- (saab mängida ka mitme instrumnendiga. Lõppfailis saavad olla mittu instrumenti)
- näha  kui kaua mängib üks noot (kui ammu seda vajutati)
- terminalis näha millal, mis instrumendiga, millise noodi mängisid

![output](https://github.com/anriwv/Kval_2024/raw/main/scr/output.png){:height="300"}


