# Datormācība

# 1.MĀJASDARBS - basic komandu paskaidrojumi

whoami - parāda lietotāja username  

clear - notīra termināli

who - prints information about currently logged in users

last - parāda wtmp (a file containing a history of all logins and logouts)

pwd - (Print Working Directory) parāda, kur atrodamies

man man - atver pamācību

man "any command" - atver pamācību attiecīgajai komandai

history - apskatīt sarakstu ar iepriekš veiktajām darbībām

ls - uzskaita failus un directories pašreizējā directory. 

ls -l - uzskaita failus un directories pašreizējā directory kā sarakstu un ar padziļinātāku info.

ls -a - uzskaita failus un directories, tajā skaitā ar slēptos failus un directories.

snap - savāc sistēmas config. info un saspiež līdz pax(Portable Archive Exchange) failam  

echo - displays line of text that are passed as argument

sh - executes commands read from a command line string, the standard input, or a specified file

cd "exact name of directory" - aiziet uz attiecīgo directory

cd . - navigate down one directory

cd .. - aiziet atpakaļ uz iepriekšējo directory

cd /  - aiziet uz pašu sākotnējo "root" directory

cd ~ - navigate to home directory

cp "name of a text file" - kopēt failu

cp "name of a text file" /home/"name of the repository"- kopēt failu attiecīgajā repository

rm "name of a file" - notīrīt, nodzēst failu

mkdir "name of a new directory" - izveido directory ar šādu nosaukumu

rmdir "name of an empty directory" -izdzēš directory, kurā nav failu

rm -r "name of the directory" -izdzēš attiecīgo directory

echo "text" > a.txt - creates a file of the echoed text

mv "nosaukums failam"/a.txt "name of the folder"/ - pārvieto failu uz citu directory

firefox & - palaiz firefox 

kill "name of the prog" - aptur lietotāja palaisto programmu

uname -a - print system info

ps aux  -parāda, kādi procesi ir notikuši

history > history_20220913a.txt  

cat history > history_20220913a.txt

whereis ls - noskaidrojam, kur sistēmā atrodas fails, šajā gadījumā ls. dators nepārmeklē visu sistēmu, bet noteiktas mapes.

echo $PATH - var pateikt kāds bija ceļš, lai atrastu failu. parādās saraksts ar caurskatāmajām mapēm.

ls -l - ar detalizāciju saraksts, + linki(?)

ls -lt /bin/ls - (domuzime un trīs x (rwxr -xr - x(read, write, execute - trīs reizes, jo kāds ir owner, owner group, ...)) atbilst failam, kuram ir izpildīšanas tiesības, ls -faila nosaukums, šis fails atrodas bin mapite)

cd /bin -aizved uz sarakstu ar failiem ar izpildīšanas tiesībām, zaļā krāsās

echo $0 - ar kādu bash vai citu shell lietotājs strādā.

bash - pārslēdzas uz bash
sh - pārslēdzas uz sh shell

ls -l ls - var apskatīt šo ls failu, to var lasīt, rediģēt dzēst, apskatīt

cat ls - var lasīt failu (cat izmanto tikai txt failu lasīšanai, ja izmamto izpildāmajiem failiem - nekas nesanāks)
komanda, piemēram, ls -fails, ar instrukcijām, nevis txt fails.

cd -aieziet uz home

git clone https .... - nokopet repository uz sistēmas

absolūta adrese - sākot ar /
relatīva - ar $

nano git-upload -atveram
nano -teksta editors
whereis nano - apskatīt komandas dokumentāciju un instrukcijām.

#!/bin/bash - 

chmod- nomaina tiesības

git pull -pirms taisa git push, ja githuba fails tiek editots.

rm - rf README.rm

history | grep clone
