

# Appunti Stage
![stage](https://user-images.githubusercontent.com/105862368/179209783-c45eac83-f195-401f-a023-6e349dd43796.jpg)

**Premessa di qusto repository, è una documentazione di ogni argomento o lavoro intrapreso durante lo stage.
Qui trovereme i vari passaggi, annotazioni inerenti ai vari step superati.**


----
- ## Indice
1. [WSL](#wsl)
2. [COMANDI LINUX](#comandi-linux)
3. [GIT](#git)
----
- ## WSL

**WSL** è l’acronimo della definizione **sottosistema di Windows**  **per Linux**, ovvero la componente che permette di poter utilizzare tutte le funzioni e applicazioni direttamente sul sistema operativo Microsoft. La complessità che caratterizzava questa operazione è superata attraverso un processo virtuale riguardante **Hyper-V** di Microsoft: attraverso questo espediente tutte le peculiarità del sistema Linux saranno gestibili direttamente tramite la creazione di una **finestra CMD**.


## Installazione di WSL
#### Step 1: Recarsi nel sito [ubuntu](https://ubuntu.com/wsl) per inizia la procedura.


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

#### Step 8: inserire:
``` 
sudo apt full-upgrade
``` 
per fagli aggiornare tutto e premere **y** per dare consenso.

#### Step 9: Inserire sul terminale :
``` 
sudo apt install x11-apps
```

#### Step 10: Inserire
```
xeyes &
```
per  avviare l'applicazione.

#### Step 11: Inserire
```xcalc```
per avviare la callcoratrice.

#### Step 12: Osservare come più applicativi posso interagire insieme.

#### Step 13: Chiudere i due applicativi e installare 
```
octave
```
```
sudo apt install octave
```

#### Step 14: Quindi avviare con
```
octave --gui &
```

#### Step 15: abbiamo un altro esempio di applicativo su Linux per maggiori info sul app clicca [octave](https://octave.org/).

----
- ## Comandi Linux

| comando | descrizione |
|--- |--- |
| **sudo apt install** *'nome_pacchetto'* | installa un nuovo pachetto. |
| **sudo apt remove** *'nome_pacchetto'* | Rimuove il pacchetto selezionato. |
| **ls** | Stampa tutti i file e cartelle nel nostro terminale. |
| **cd** *'nome_cartella'* | Ti sposta nella cartella selezionata. |
| **mkdir** *'nome_nuova_cartella'* | Crea una nuova cartella. |
| **touch** *'nome_nuovo_file'* | Crea file. |
| **nano** *'nome_file'* | Apre il file selezionato. |
| **cp** *'nome_file1' 'nome_file2'* | Copia il contenuto del file1 nel file2. |
| **rm** *'nome_file'* | Rimuove il file. |
| **mv** *'file2' 'file3'* | Sostituisce (sposta il contenuto) il file2 con file3.  |
| **cat** *'file'* | Stampa il contenuto del File. |
| **pwd** | Stampa il percorso della *Directory* corrente. |
| **ls -lah** | Stampa il tutto contenuto (compreso quelli nascosti) della cartella corrente. |
| **grep** *'stringa' 'nome_file'* | Stampa le righe del file in cui è presente la 'stringa'. |
| **tr** *'c' 'x' < 'file'* | Sostituisce le 'c' presenti nel file con le 'x'. |
| **rmdir** *'nome_cartella'* | Rimuove la cartella. |


#### Video tutorial

[![video](https://user-images.githubusercontent.com/105862368/179237259-84909424-6725-4f7e-8421-a70f557c6c99.png)](https://www.youtube.com/watch?v=ROjZy1WbCIA&t=0s)

L'autore inizia dalla definizione e la sua istallazione nel proprio sistema operativo, spiega attentamente i comandi e i loro vantaggi con esempi e procedimenti eseguibili in step molto semplici, facili da seguire.

#### Pagine utili

In queste pagine vengono presentate dei primi esercizi per entrare in confidenza con i comandi linux. Esercizi con lo script nel terminale e vari video che aiutano la comprensione delle operazioni. 
- [link1]( https://www.redhat.com/sysadmin/learn-bash-scripting)
- [link2]( https://linuxconfig.org/bash-scripting-tutorial-for-beginners)
- [link3](https://www.learnshell.org/)

----
- ## GIT
![git](https://user-images.githubusercontent.com/105862368/179232106-29219d2a-583f-4aab-8e87-92e271117563.jpg)



[Git](https://git-scm.com/) è un software per il controllo di versione distribuito utilizzabile da interfaccia a riga di comando, creato da Linus Torvalds nel 2005. Git nacque per essere un semplice strumento per facilitare lo sviluppo del kernel Linux ed è diventato uno degli strumenti di controllo versione più diffusi. 




#### Consigli per l'apprendimento

Seguire i tutorial su udemy [corso_1](https://www.udemy.com/course/git-started-with-github/?LSNPUBID=JVFxdTr9V80&ranEAID=JVFxdTr9V80&ranMID=39197&ranSiteID=JVFxdTr9V80-nJ7w5HFJLzTmw.e36Z8ZiQ&utm_medium=udemyads&utm_source=aff-campaign), [corso_2](https://www.udemy.com/course/the-ultimate-git-5-day-challenge/?LSNPUBID=JVFxdTr9V80&ranEAID=JVFxdTr9V80&ranMID=39197&ranSiteID=JVFxdTr9V80-Zre8AB3HJeh_8kkLWBV6mQ&utm_medium=udemyads&utm_source=aff-campaign).
Sono completi di spiegazione e istallazione nelle varie piattaforme utilizzate, per non parlare che chiarisce i concetti del persorso del file, durante lo sviluppo di un progetto e le varie dinamiche possibili.

![128hsgntnsu9bww0y8sz](https://user-images.githubusercontent.com/105862368/179229011-9243cf66-a985-4624-a01c-e62af57ea002.jpg)

### comandi

| Comando | Descrizione |
   |---|---|
   | **git init** | Crea un nuovo repository git |
   | **git clone** /percorso/del/repository | Crea una copia di un repository locale. |
   | **git clone** nomeutente@host:/percorso/del/repository | Crea una copia si un repository da un server remoto. |
   | **git add** nomedelfile | Aggiunge le modifiche eseguite nel file selezionato. |
   |  git add .  | Aggiunge tutte le modifiche eseguite. |
   | **git commit -m** "Messaggio per la commit" | Esegue un commento per validare le modifiche precedentemente aggiunte. |
   | **git push origin** nomebranch | Invia le modifiche effettuate nel branch remoto  selezionato.|
   | **git remote add origin** 'server' | Aggiunge i cambiamenti al server remoto. |
   | **git checkout** nomebranch |Ci permette di spostarci nel branch selezionato. |
   | **git -b** | Crea un nuovo Branch. |
   | **git branch -d** nomebranch | Cancella il branch selezionato. |
   | **git pull** | Aggiorna il tuo repository locale alla commit più recente. |
   | **git merge** nomebranch | Unisce il mio branch locale a quello remoto. |
   | **git diff** branchlocale branchremoto | Ti permette di visualizzare un anteprima delle differenze tra il branch locale e quello remoto. |
   | **git tag** nometag idcommit | Crea una tag nella commit selezionata. |
   | **git log** | Ti fa visualizzare il registro delle commit eseguite. |
   | **git checkout -- ** nomefile | Carica il file selezionato dal repository romoto. |
   | **git fetch origin** | Recupera l'ultima versione del server. |
   | **git reset --hard** origni/master | Cancella ogni commit e add eseguita nel server locale. |
   | **gitk** | Apre GUI (interfaccia utente), puoi visualizzare ongi aspetto del tuo repository. |
   | **git status** | Stampa lo stato e le differenze con il branch remoto. |
   | **git pull origin** nomebranch | Carica i file dal branch remoto. |
   
   --


----

![githubjpg](https://user-images.githubusercontent.com/105862368/179232185-100aa7b7-890c-45d7-8b6c-81dcd71b64fd.jpg)




 
