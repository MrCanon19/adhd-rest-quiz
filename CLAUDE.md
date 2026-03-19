# CLAUDE.md — adhd-rest-quiz

Quiz diagnostyczny "Jakiego odpoczynku potrzebujesz?" - 14 pytań, statyczna strona HTML, bez backendu.

## Stack

- Vanilla HTML/CSS/JS, single-file (`index.html`)
- GitHub Pages (https://mrcanon19.github.io/adhd-rest-quiz/)
- Osobne repozytorium git (nested repo - `.git` w folderze)

## Jak uruchomić

```bash
open index.html
```

Lub przez GitHub Pages (deploy automatyczny po push do własnego repo).

## Kluczowe informacje

- Cały kod w jednym pliku `index.html` - bez buildu, bez zależności
- Dane zostają w przeglądarce (localStorage), bez rejestracji
- Projekt ma własne repo git - commity i push robić z `projects/adhd-rest-quiz/`, nie z rootu
- W `.gitignore` rootu wpisane `projects/adhd-rest-quiz/.git` (nested repo)

## Jak pushować

```bash
cd /Users/michalmarini/marini-hub/projects/prywatne/adhd-rest-quiz
git add index.html
git commit -m "opis zmian"
git push
```
