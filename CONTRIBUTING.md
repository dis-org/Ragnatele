#Come collaborare
Se vuoi aiutarci nel realizzare queste dispense, ti preghiamo di seguire, nei limiti del ragionevole, la struttura proposta 
nell'indice, sentendoti libero di aggiungervi eventuali argomenti mancanti. Ti raccomandiamo inoltre di creare un branch: i 
vari rami verranno riuniti il più spesso possibile da harisont.

**Se conosci il latex**
-Utilizza **\code{}** per parti di codice e comandi da terminale menzionati nel testo;
-Utilizza **\vedi{*NOME_SOTTOSEZIONE*}** per creare un riferimenti all'interno del testo.

**Se non conosci il latex**
Allega un file .txt (no altri formati) in cui spieghi in quale sezione vada incollato il paragrafo scritto.
 
**Precisazioni su Git e GitHub**
-Per creare un tuo branch (da farsi una sola volta) utilizzare i seguenti comandi:
	$git branch *nome_branch* //creazione branch
	$git checkout *nome_branch* //il nuovo branch viene impostato come tuo spazio di lavoro
	$git push --set-upstream *nome_branch* //creazione branch online, su GitHub
-Prima di fare modifiche:
	$git pull origin master //se harisont ha comunicato di aver effettuato il merge
	$git pull //in ogni altro caso
-Per condividere il tuo lavoro (ad ogni modifica importante)
	$git status //controlla lo stato delle cose
	$git add . //traccia tutti i file: non preoccuparti di eventuali file intermedi ottenuti in compilazione, il 
.gitignore li ignora
	$git commit -a -m "*Breve messaggio di commit in cui spieghi il tuo lavoro*"
	$git push //carica online il tuo lavoro
