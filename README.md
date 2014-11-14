eggs-utopic
===========


![eggs-utopic](https://github.com/pieroproietti/eggs-utopic/blob/master/opt/eggs/eggs.png?raw=true)
Modifica

Un sistema di riproduzione eccellente per pinguini ma che aiuta - non 
poco - nella sistemazione delle finestre!

Tutto quello che serve per trasformare il tuo ubuntu/lubuntu/kubuntu 
14.10 in un boot server di se stesso!

Con eggs trasformerete la vostra macchina in un boot server e 
potrete avviare qualsiasi computer in rete locale con le vostre 
impostazioni per la manutenzione, il recupero dati, la clonazione ed
il restore delle vostre immagini di sistema.

Per il funzionamento di eggs-utopic è necessaria l'installazione del
pacchetto yad, occorre quindi abilitare la repository ppa:webupd8team/y-ppa-manager
procedendo come segue:
- sudo add-apt-repository ppa:webupd8team/y-ppa-manager
- sudo apt-get update
- sudo apt-get install yad

YAD (Yet Another Dialog) è un fork di zenity con molte migliorie.

Una nota sui nomi
=================
La macchina che diventa boot server viene dall'autore chiamata giantturtle
mentre le macchine che vengono avviate in boot remoto vengono individuate 
dal nome littlebird. 

Come fa una tartaruga gigante a riprodursi in tanti
piccoli uccellini? 

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
 apt-get install clonezilla
 
A questo punto, potete iniziare a riparare le finestre rotte!

Serve aiuto?
===========
Per ulteriori informazioni consultate il wiki: http://piojoris15.com
