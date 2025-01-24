# Struttura Base
In questa cartella potete trovare i file e le cartelle di partenza della nostra APP

## Installazione
```bash
git clone https://github.com/AlexGrottola/BootstrapVite.git
```

## Inizializzazione di GIT
```bash
git init 
```

## Inizializzazione di GIT con un nome Personalizzato
```bash
git init -b nuovo_branch
```

## Aggiornamento dell'utente che sta facendo la modifica
```bash
git config user.email "latuaemail"
```
```bash
git config user.name "iltuonome"
```

## Aggiungere i file nello stage di GIT
```bash
git add <nome del file>
```

## Aggiungere il commit 
```bash
git commit -m "Commento che spiega il cambiamento sul file"
```

## Visualizzare il log dei cambiamenti
```bash
git log
```

## Cancella una modifica
```bash
git reset <head>
```

## Cancella una modifica anche dai file
```bash
git reset --hard <head>
```

# Extra

## Rinominare il branch di default di GIT
```bash
git config --global init.defaultBranch main
```