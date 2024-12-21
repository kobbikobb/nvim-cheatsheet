# Neovim Cheatsheet

## General

### Save and close
- wq
- shift + zz

### Suspend and go to terminal
- ctrl + z
- fg in terminal = come back

### Open Links
- gx = open browser
- gf = open file, ctrl + o to jump back

## Substituding 

### Substitude globally
- :%s/OLD/NEW/g
- add c to confirm each

### Substitude when text is selected
- :'<,'>s/OLD/NEW/g

## Jumping

### % = Jump between (), {} or []

### Mark and jump
- ma = mark
- 'a = jump
- mA = mark globally
- 'A = jump globally

### Jump to line
- Line number + G

## Selecting

### gv = re-select previous selection

### vi = select text inside
- vi( | vib = select (TEXT WITHIN)
- vi{ | viB = select {TEXT WITHIN}
- vi[ = select [TEXT WITHIN]
- vi" = select "TEXT WITHIN"
- Also works with cib (replace), dib (delete), etc

### va = select text around
- va( | vab = select (TEXT)
- va{ | vaB = select {TEXT}
- va[ = select [TEXT]
- va" = select "TEXT"
- Also works with cab (replace), dab (delete), etc

## Editing

### Combine lines
- J = join
- gJ = join excluding break

