# Appunti Stage

**Premessa di qusto repository, è una documentazione di ogni argomento o lavoro intrapreso durante lo stage.
Qui trovereme i vari passaggi, annotazioni inerenti ai vari step superati.**


----
## Indice
- ### WLS
- ### COMANDI LINUX
- ### GIT
----
- ## WSL

**WSL** è l’acronimo della definizione **sottosistema di Windows**  **per Linux**, ovvero la componente che permette di poter utilizzare tutte le funzioni e applicazioni direttamente sul sistema operativo Microsoft. La complessità che caratterizzava questa operazione è superata attraverso un processo virtuale riguardante **Hyper-V** di Microsoft: attraverso questo espediente tutte le peculiarità del sistema Linux saranno gestibili direttamente tramite la creazione di una **finestra CMD**.


## Installazione di WSL
#### Step 1: Recarsi nel sito ubuntu per inizia la procedura => [https://ubuntu.com/wsl](https://ubuntu.com/wsl).


#### Step 2: Seleziona Sistema operavito

Troverete due scelte tra Windows 10 e 11.

#### Step 3: Prerequisiti 

- **build** oltre i 22.000  (Start/Informazioni_sul_pc);

- Abilitare **Piattaforma Macchina Virtuale** (Pannello_di_Controllo/Programmi/
  
  Attiva_o_disattiva_funzionalità_di_Windows).
		
#### Step 4: Aprire **Microsoft Store** e scaricare **Windows Subsystem for Linux Preview** e aprirlo.

#### Step 5: Aprire **Microsoft Store** e scaricare **ubuntu**.

#### Step 6: Aprire **ubuntu**, si apre il suo terminale e farlo configurare.

#### Step 7: Creare un nome utente e password.

#### Step 8: inserire:``` sudo apt full-upgrade ``` per fagli aggiornare tutto e premere **y** per dare consenso.

#### Step 9: Inserire sul terminale : ``` sudo apt install x11-apps ```

#### Step 10: Inserire **xeyes &** per  avviare l'applicazione.

#### Step 11: Inserire **xcalc** per avviare la callcoratrice.

#### Step 12: Osservare come più applicativi posso interagire insieme.

#### Step 13: Chiudere i due applicativi e installare **octave** con **sudo apt install octave**.

#### Step 14: Quindi avviare con **octave --gui &**.

#### Step 15: abbiamo un altro esempio di applicativo su Linux per maggiori info sul app clicca [https://octave.org/](https://octave.org/).

----
## COMANDI LINUX

| comando | descrizione |
|--- |--- |
| sudo apt install 'nome_pacchetto' | installa un nuovo pachetto. |
| sudo apt remove 'nome_pacchetto' | Rimuove il pacchetto selezionato. |
| ls | Stampa tutti i file e cartelle nel nostro terminale. |
| cd 'nome_cartella' | Ti sposta nella cartella selezionata. |
| mkdir 'nome_nuova_cartella'| Crea una nuova cartella. |
| touch 'nome_nuovo_file'| Crea file. |
| nano 'nome_file' | Apre il file selezionato. |
| cp 'nome_file1' 'nome_file2' | Copia il contenuto del file1 nel file2. |
| rm 'nome_file' | Rimuove il file. |
| mv 'file2' 'file3' | Sostituisce (sposta il contenuto) il file2 con file3.  |
| cat 'file' | Stampa il contenuto del File. |
| pwd | Stampa il percorso della *Directory* corrente. |
| ls -lah | Stampa il tutto contenuto (compreso quelli nascosti) della cartella corrente. |
| grep 'stringa' 'nome_file | Stampa le righe del file in cui è presente la 'stringa'. |
| tr 'c' 'x' < 'file' | Sostituisce le 'c' presenti nel file con le 'x'. |
| rmdir 'nome_cartella' | Rimuove la cartella. |
| row 1 | column 2 |

## VIDEO TUTORIAL DEI COMANDI

>[!VIDEO](https://www.youtube.com/watch?v=ROjZy1WbCIA)
>[!VIDEO](https://youtu.be/ROjZy1WbCIA)

----
##  GIT
----




 
