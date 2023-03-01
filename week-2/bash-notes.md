ssh bandit0@bandit.labs.overthewire.org -p # za pristup preko shh na server bandit.labs.overthewire.org po portu 2220
pwd # ispisuje lokaciju na koju se trenutno nalazis
ls # ispisuje listu fajlova i direkotrijuma
cat # ispisuje sadrzaj fajla
cat <- ili cat ./- # ispisuje sadrzaj fajla koji pocinje sa dash
cd # sluzi da promijenimo direktorijum
cat "... space ..." # da citamo fajl koji ima spaace u nazivu, stavimo ime fajla pod " ", . Moze se koristiti i komanada cat \ \ \ \, gde je space izmedju rijeci u fajlu predstavljen \
cat .filename- za ispis hidden fajla
file # da vidimo tip fajla
find -size 1033c -readable ! -executable # iskorisistio sam da nadjem fajl sa ovim osobinma
find / -user bandit7 -group bandit6 # da pronadje fajl koji ne znamo dje se nalazi, sto znaci da trazimo po rutu i ko je ovner nad fajlom
grep "string" nazivfajla # sluzi da mi vrati liniju koda koji sadrzi ovaj string
