eggs-utopic
===========


![eggs-utopic](https://github.com/pieroproietti/eggs-utopic/blob/master/eggs-utopic/opt/eggs/eggs.png?raw=true)
 Eggs, un sistema di riproduzione eccellente per pinguini ma che aiuta - non 
poco - anche nella sistemazione delle finestre!

Tutto quello che serve per trasformare il vostro ubuntu/lubuntu/kubuntu 
14.10 in un boot server di se stesso.

Con eggs trasformerete la vostra macchina in un boot server e 
potrete avviare qualsiasi computer in rete locale con le vostre 
impostazioni per la manutenzione, il recupero dati, la clonazione ed
il restore delle vostre immagini di sistema.

Istruzioni
==========
Scaricate ed installate una versione di Ubuntu, Kubuntu o Lubuntu
14.10 sulla macchina che sarà il vostro boot server. 

Una volta completata l'installazione, procedete ad abilitare la 
repository ppa:webupd8team/y-ppa-manager, necessaria per YAD
(Yet Another Dialog) è un fork di zenity con molte migliorie,
procedendo come segue:
- sudo add-apt-repository ppa:webupd8team/y-ppa-manager
- sudo apt-get update
- sudo apt-get install yad

scaricate il pacchetto Debian [eggs-utopic_x.x.x-x_all.deb](http://piojoris15.com/DEBS/eggs-utopic_0.8.0-1_all.deb)
dal sito http://www.piojoris15.com

- sudo dpkg -i eggs-utopic_x.x.x-x_all.deb

correggete le dipendenze:
- sudo apt-get install -f

avviate eggs:
- sudo /opt/eggs/eggs

e procedete secondo le istruzioni.

Una nota sui nomi
=================
La macchina che diventa boot server viene dall'autore chiamata giantturtle
mentre le macchine che vengono avviate in boot remoto vengono individuate 
dal nome littlebird. 

Come fa una tartaruga gigante a riprodursi in tanti piccoli uccellini? 
Beh, la risproduzione non &egrave; ancora perfetta! Scherzi a parte, la 
tartaruga quando inizia il processo di riproduzione è ancora un
pinguino normale, riproduce quindi se stesso, &egrave; solo dopo il 
rilascio dell'uovo che viene aggiornata per la "schiusa" di rete.

In /opt/eggs/wallpaper trovere degli sfondi adeguati per evitare qualsiasi
confusione:

Giant Turtle - Il boot server
![giantturtle](https://github.com/pieroproietti/eggs-utopic/blob/master/opt/eggs/wallpapers/galapagos-giant-turtle.jpg?raw)

Little bird - Il piccolo uccellino che viaggia a scrocco della tartaruga!
![littlebird](https://github.com/pieroproietti/eggs-utopic/blob/master/opt/eggs/wallpapers/galapagos-little-bird.jpg?raw)

Suggerimenti
============
Si consiglia di installare sui littlebird il pacchetto clonezilla che vi 
permetterà di clonare al volo le vostre macchine. In una unica soluzione
avrete la possibilità di salvare i dati utente, effettuare il restore
del disco e rimettere i dati utente al loro posto.

Per installare clonezilla sul littlebird, semplicemente avviate una macchina
in remoto ed aprite una finestra di terminale:

 apt-get update
 
 apt-get install clonezilla gdisk
 
Attenzione: al momento, 22 novembre 2014 per un problema di allineamento nella
repository di ubuntu tra il pacchetto clonezilla e partclone, il pacchetto cosi'
installato NON funziona. Occorre scaricare e compilare partclone-0.2.69-0 che 
implementa l'opzione partclone -z richiesta da clonezilla.
 
A questo punto, potete iniziare a riparare le finestre rotte!

Serve aiuto?
===========
Per ulteriori informazioni consultate il wiki: http://piojoris15.com
