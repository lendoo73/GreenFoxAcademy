# Átirányítás

* Írj szöveges tartalmat egy fájlba: `echo "ez egy szöveges tartalom" > atiranyitas.txt`
* Irányítsd át a fájl tartalmát egy másikba: `cat atiranyitas.txt > copied.txt`
* Írasd ki egy fájl sorba rakott tartalmát: 
```
echo "2. répa" > copied.txt
echo "4. rigó" >> copied.txt
echo "1. retek" >> copied.txt
cat copied.txt | sort
```
* Írd át egy fájlba egy másik fájl sorrendbe rakott tartalmát: `cat copied.txt | sort > sorted.txt`
* Szedd ki az ugyan olyan sorokat a tasks.txt fájlból: `cat tasks.txt | uniq > tasks.txt`
* Írd ki az összes sorát a tasks.txt fájlnak ami tartalmazza a basic szót: `cat tasks.txt | grep basic`
* Commit-old és Push-old a változtatásaidat:
```
git add .
git commit -m "Átirányítás gyakorlás"
git push
``` 
