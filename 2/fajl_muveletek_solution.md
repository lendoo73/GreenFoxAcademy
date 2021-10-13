# Fájl műveletek

* Lépj be az újonnan létrehozott repository-ba: `cd *y`
* Listázd ki a részletes információkat a benne található fájlokról és könyvtárakról: `ls -la`
* Másold le a index.html fájlt about.html néven: `cat index.html > about.html`
* Hozz létre egy temp_images nevű könyvtárat: `mkdir temp_images`
* Másold bele a 1.jpg és 2.jpg fájlokat a temp_images könyvtárba az images-ből: 
```
cat images/1.jpg > temp_images/1.jpg
cat images/2.jpg > temp_images/2.jpg
```
* Mozgasd a 6.jpg fájlt az images könyvtárba a css-ből: `mv css/6.jpg images`
* Töröld ki a 7.jpg fájlt a css-ből: `rm css/7.jpg`
* Commit-old és Push-old a változtatásaidat:
```cli
git status
git add .
git push -u origin HEAD
```
