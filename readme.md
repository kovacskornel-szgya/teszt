#Hello Mizu
…or create a new repository on the command line
echo "# teszt" >> README.md #fájl létrehozása, az első sorba "# teszt" kerül
git init #a git mappa inicializálása
git add README.md #staging changes, azaz a változtatások mentése
git commit -m "first commit" #változtatások jóváhagyása, és megjelölés beküldésre
git branch -M main #a fejlesztési ág átnevezése main-re
git remote add origin https://github.com/kovacskornel-szgya/teszt.git #távoli repo hozzáadása origin néven
git push -u origin main # a fejlesztési ág feltöltése első alkalommal
…or push an existing repository from the command line
git remote add origin https://github.com/kovacskornel-szgya/teszt.git
git branch -M main
git push -u origin main #feltölti az origin nevű távoli repo-ba a commitokat
git pull origin main #origin main lehívása

További terminál parancsok:
git pull origin main #  a friss repo letöltése
git remote -v #aktuális távoli repo lekérdezése
git status #change, stage, commit állapotának lekérdezése
git config --global --list #globális beállítások listázása
cd <directory name>#ChangeDirectory
cd .. #egy mappával feljebb lép
mkdir <directory name> #make directory
rmdir <directory name> #remove directory
ls #list - könyvtár listázása
git commit -am "messeage" #összes változtatás és commit egy lépésben
 