# Lab3_Git
Ćwiczenie 3 - Podstawy poruszania się w Git
#!/bin/bash

git commit
git commit

# Pozioom 2
git branch bugFix
git checkout bugFix

# Poziom 3
git branch bugFix
git checkout bugFix
git commit
git checkout main
git commit
git merge bugFix

# Poziom 4: Git Rebase
git branch bugFix
git checkout bugFix
git commit
git checkout main
git commit
git checkout bugFix
git rebase main

# CZĘŚĆ 2: Poruszanie się po repozytorium

# Poziom 1: Odczepianie HEAD (Detach HEAD)
git checkout C2

# Poziom 2: Względne referencje (Relative Refs ^)
git checkout bugFix^

# Poziom 3: Względne referencje 2 (Relative Refs ~)
git branch -f main C6
git checkout HEAD~1
git branch -f bugFix C0

# Poziom 4: Odwracanie zmian w Gicie (Git Reset / Git Revert)
git reset HEAD~1
git checkout pushed
git revert HEAD

# CZĘŚĆ 3: Przenoszenie pracy (Advanced Git)

# Poziom 1: Cherry Pick
git cherry-pick C3 C4 C7

# Poziom 2: Interaktywny Rebase (Git Interactive Rebase)
git rebase -i HEAD~4
# (W tutorialu otworzy się okno interaktywne, gdzie zmieniasz kolejność lub usuwasz commity)

# CZĘŚĆ 4: Zdalne repozytoria (Remote)

# Poziom 1: Git Clone
git clone

# Poziom 2: Git Fetch
git fetch

# Poziom 3: Git Pull
git fetch
git merge o/main

# Poziom 4: Git Push
git commit
git commit
git push
