# Χρήση του repository

## Εγκατάσταση Git

1. Κατεβάστε την [τελευταία έκδοση git](https://git-scm.com/downloads) (64-bit Git for Windows Setup)
2. Ανοίξτε τον installer ύστερα που τον κατεβάσετε και συνεχίστε να πατάτε next με τα default options και τελικά install.
3. Όταν τελειώσει, ανοίξτε το terminal και γράψτε την παρακάτω εντολή:

```
git --version
```

Αν δεν εμφανιστεί κάποιο error, τότε έχετε εγκαταστήσει το git επιτυχώς.

Χρήσιμα links:

- https://www.simplilearn.com/tutorials/git-tutorial/git-installation-on-windows

---

## Αντιγραφή repository στον υπολογιστή σας

Μεταφερθείτε στον κατάλληλο φάκελο στον οποίο θέλετε να αντιγράψετε το repository στο terminal με την εντολή cd και στην συνέχεια χρησιμοποιείστε την παρακάτω εντολή:

```
git clone https://github.com/SilverBlade159/ComputerScienceProject.git
```

Στην συνέχεια μπορείτε να ανοίξετε τον φάκελο στο IDE επιλογής σας (π.χ. VS Code)

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
