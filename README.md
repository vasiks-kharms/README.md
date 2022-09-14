# Datormācība
Studiju kursa Datormācības (pamatkurss) elektroniskā klade  [^1]
Satura rādītājs
- [1.sadaļa]
- 2.sadaļa
- 3.sadaļa  

##piemēri ar sarakstiem
[piemērs ar linku]  
(https://upload.wikimedia.org/wikipedia/commons/c/c9/Svg_example4.svg)

[piemērs ar sarakstu]  
1. elements  
2. elements  
3. elements  

[piemērs ar sarakstu]  
- *1.elements  
- *2.elements
- *3.elements  

[piemērs ar sarakstu]  
- *1.elements  
-   *2.elements
-     *3.elements

[piemērs ar sarakstu]  
- [x] izpildīts
- [ ] nav izpildīts
- [x] izpildīts  

[piemērs ar emoji]  
🍪 

[^1]: J.Ziemelis. Ievads algoritmu valodā C. Rīga

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

lt - ls  

cat history > history_20220913a.txt  
