# My personal LaTeX settings

## Usage
1. Clona la repository all'interno della cartella `texmf` presente nell'installazione di LaTeX nella tua macchina:
```bash
git clone https://github.com/FrancescoBozzo/local.git
```

2. Esegui il programma `texhash` per aggiornare il database della tua distribuzione LaTeX

3. Per includere nel tuo progetto un file di stile `file.sty` presente in questa repo, ti basterà utilizzare `\usepackage{file}` nel tuo preambolo.

## Packets
- `microtype`: miglioramenti tipografici (si consiglia di importarlo sempre)
- `frontespizio`: per copertina di tesi di laurea
- `titlepage`: per copertine generiche
- `quoting`: per citazioni
- `acronym`: per gestire gli acronimi
- `glossaries`: per gestire il glossario
- `varioref`: per riferimenti incrociati con testo