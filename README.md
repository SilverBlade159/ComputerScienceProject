# Χρήση του repository

## Εγκατάσταση Git

---

## Προσθήκη κώδικα

Μπορείτε να προσθέσετε ότι αρχεία θέλετε locally στον υπολογιστή σας ή να κάνετε αλλαγές στον κωδικά. Στην συνέχεια ανοίγετε το terminal και αντιγράφετε τις παρακάτω εντολές γραμμή προς γραμμή.

### Την πρώτη φορά που θα κάνετε προσθήκη κώδικα

```
cd ../ComputerScienceProject // συμπληρώστε το κατάλληλο path
git remote add origin git@github.com:SilverBlade159/ComputerScienceProject.git
git add .
git commit -m "Αναφέρετε τις αλλαγές στον κώδικα"
git push -u origin main
```

### Μετέπειτα χρησιμοποιείστε αυτές τις εντολές όταν θέλετε να προσθέσετε κώδικα

```
cd ../ComputerScienceProject // συμπληρώστε το κατάλληλο path
git add .
git commit -m "Αναφέρετε τις αλλαγές στον κώδικα"
git push
```
