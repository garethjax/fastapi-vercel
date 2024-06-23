# Questo è un file di lettura

- più che altro per appunti personali
  

  ## Da ricordare

  - quando si crea un endpoint nella app, bisogna ricrearla anche su vercel.json per matchare la stessa url

  ## Da fare web

  - autenticazione con una password per me e una per massimo e una per le api remote
  - 
  - carica excel
  - salva excel in "risultati" come utente.timestamp.nomefile.xlsx
  - processa righe dell'excel
  - ogni riga dell'excel viene mandata su openrouter con cohere
  - la risposta viene messa in un database sqlite
  - alla fine del processo tutte le righe vengono salvate in excel
  - il file viene messo a disposizione in una pagina "/risultati"

## API 
  - quando viene chiamato il /trasformer viene passato un file con un numero variabile di righe in formato json (tipo excel)
  - viene composto un prompt basato sulla lingua e altri parametri
  - Quando il sistema ha finito viene restituito il risultato in json format

