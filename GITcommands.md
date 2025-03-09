# Promemoria Comandi Git per MovieApp

## Primo setup (già fatto)
```
git init
git add .
git commit -m "Setup iniziale"
git branch -M main
git remote add origin https://github.com/emmanueletavolara/MovieApp.git
git push -u origin main
```

## Workflow quotidiano

### Creare un nuovo branch per sperimentare
```
git checkout -b feature/nome-funzionalita
```

### Verificare lo stato e il branch attuale
```
git status
```

### Salvare le modifiche
```
git add .
git commit -m "Descrizione delle modifiche"
```

### Tornare al branch principale
```
git checkout main
```

### Unire le modifiche al main (se soddisfatto)
```
git merge feature/nome-funzionalita
```

### Caricare le modifiche su GitHub
```
git push origin main
```

## Comandi utili

### Visualizzare tutti i branch
```
git branch
```

### Scartare modifiche non salvate
```
git checkout -- .
```

### Vedere la cronologia
```
git log --oneline
```

### Aggiornare il repository locale con le modifiche remote
```
git pull origin main
```

### Eliminare un branch (dopo averlo unito)
```
git branch -d feature/nome-funzionalita
```
