In ogni cartella � presente un file README.txt contenente le istruzioni per eseguire la rispettiva parte di progetto.

La logica con cui sono configuarte le parti � la seguente: 
il lato server lavora in locale con il lato client 
(il server su localhost:80 e il client su localhost:4200).

Le parti mobile e desktop quando sono in esecuzione "fanno" le loro richeste su un'istanza del lato server raggiungibile 
all'indirizzo IP: 80.211.139.226 
(Server virtuale Aruba da noi acquistato), questa scelta � stata fatta al fine di semplificare 
il test dell'app usandola anche la pi� dispositivi Android
e desktop app
contemporaneamente. 



Riassumento le parti cos� come configurate effettuano le richieste http verso i rispettivi indirizzi:

client -> localhost
	
mobile (Android) -> 80.211.139.226
desktop (Windows) -> 80.211.139.226


