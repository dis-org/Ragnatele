# Come collaborare
Se vuoi aiutarci nel realizzare queste dispense, ti preghiamo di seguire, nei limiti del ragionevole, la struttura proposta 
nell'indice, sentendoti libero di aggiungervi eventuali argomenti mancanti.

## Da dove cominciare
Nel file [TODO.md] trovi la lista degli argomenti da rivedere, da aggiungere e quelli sui quali stanno lavorando gli altri.

### Se non usi GitHub o non conosci il LaTeX
Invia un file .txt (no altri formati) a uzkamascio@gmail.com contenente il testo e le indicazioni sulla sezione in cui collocarlo.

### Comandi di LaTeX personalizzati
* ` \italic{} ` equivale a ` \textit{} `;
* ` \code{} ` per parti di codice e comandi da terminale menzionati nel testo, equivale a ` \texttt{} `.;
* ` \vedi{Nome_sottosezione} ` (si rispettino eventuali maiuscole iniziali) per creare riferimenti interni equivale a ` \nameref{} `.
* ` \sec{} `, ` \sub{} ` e ` \subsub{} ` per creare sezioni e sottosezioni con label.
* Ugualmente, se hai bisogno di creare una piccola sezione non indicizzata *all'interno di una sotto-sottosezione*, utilizza il tag `\para{titolo_paragrafo}`.
* `\image[nomefile.ext][scale=0.x]{Descrizione}`inserisce un'immagine.
* `\boximage[nomefile.ext][scale=0.x]{Descrizione}` inserisce un'immagine riquadrata.

(NB: le immagini devono essere salvate nella cartella `images/`);

### Se stai facendo un fork con l'intenzione di aprire una pull-request
Prima di cominciare comunicaci chi sei e su che parte vuoi lavorare aprendo una pull-request del [TODO.md].

### Se vuoi fare parte della Disorganizzazione
Ci trovi al DMI UniPG.

### Se fai parte della Disorganizzazione
* Per creare un tuo branch (da farsi una sola volta) utilizzare i seguenti comandi:
	1. ` $git branch nome_branch ` creazione branch 
	2. ` $git checkout nome_branch ` imposta il nuovo branch come tuo spazio di lavoro 
	3. ` $git push --set-upstream origin *nome_branch* ` crea il branch su GitHub
* Prima di fare modifiche:
	1. modifica il [TODO.md] direttamente da GitHub (assicurati di essere sul master branch)
	1. ` $git pull origin master ` per allinearti con il master branch
* Quando hai finito di fare quello che stavi facendo:
	1. ` $git status ` controlla lo stato delle cose
	2. ` $git add . ` se devi aggiungere immagini
	1. ` $git commit -a -m "Breve messaggio di commit in cui spieghi il tuo lavoro" `
	2. ` $git push ` carica online il tuo lavoro
	1. modifica il [TODO.md] direttamente da GitHub (assicurati di essere sul master branch)
	4. Apri la pull-request su GitHub

[TODO.md]: https://github.com/Disorganizzazione/Ragnatele/blob/master/TODO.md
