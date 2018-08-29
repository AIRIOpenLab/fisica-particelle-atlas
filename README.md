# Studio del decadimento Z<sup>0</sup>&rightarrow;e<sup>+</sup>e<sup>-</sup> nell'esperimento ATLAS

## Introduzione

In questa analisi, utilizzeremo i [dati pubblici](http://opendata.atlas.cern) dell'esperimento [ATLAS](http://atlas.cern/) al [CERN](http://home.cern/) per studiare la produzione e il decadimento del bosone Z<sup>0</sup>, uno dei vettori dell'[interazione elettrodebole](https://it.wikipedia.org/wiki/Interazione_elettrodebole) nel [Modello standard](https://it.wikipedia.org/wiki/Modello_standard). 

## Requisiti
* Sistema operativo: Linux/Windows/MacOS
* Aver installato [Docker](https://store.docker.com/search?type=edition&offering=community)
* 5 GBytes di disco fisso

## Istruzioni

Dopo aver installato Docker, dovete scaricare l'immagine del software di analisi, aprendo una shell (Linux), oppure una [PowerShell (Windows)](https://docs.microsoft.com/en-us/powershell/) oppure un [Terminale (MacOS)](https://www.slidetomac.com/34646/terminale-unix-lo-strumento-piu-potente-di-mac-os-x-guida-slidetomac) e digitando:

`docker pull airiopenlab/fisica-particelle-atlas`

L'immagine è circa 2 GBytes, contiene preinstallato tutto il software necessario all'analisi e una parte dei dati. Se non avete una connessione internet veloce, prevedete un'ora per lo scaricamento.

Una volta scaricato il tutto, fate partire la [macchina virtuale](https://it.wikipedia.org/wiki/Macchina_virtuale) digitando:

`docker run --rm -p 8888:8888 airiopenlab/fisica-particelle-atlas` 
