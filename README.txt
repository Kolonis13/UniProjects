Εργασία 1

Δημιουργήστε ένα παιχνίδι ερωτήσεων-απαντήσεων όπου το πρόγραμμα θα προτείνει τυχαίες ερωτήσεις στον παίκτη. Οι συνολικές ερωτήσεις (τράπεζα ερωτήσεων) του προγράμματος είναι 10.

Θα γίνουν 5 ερωτήσεις στον παίκτη οι οποίες θα επιλέγονται τυχαία από τις 10. Κάθε φορά θα εμφανίζεται η ερώτηση και ο χρήστης με το πληκτρολόγιο θα απαντά. Ο παίκτης θα λαμβάνει άμεσα το αποτέλεσμα της απάντησής του με τα λεκτικά «ΣΩΣΤΟ» ή «ΛΑΘΟΣ».

Στο τέλος θα εμφανίζεται  το σκορ του παίχτη, πόσες σωστές και λάθος απαντήσεις έδωσε, καθώς και το ποσοστό των σωστών απαντήσεων ( 100*(πλήθος_σωστών/5) ).

 

Εργασία 2

Δημιουργήστε ένα πρόγραμμα υπολογισμού φόρου εισοδήματος για φυσικά πρόσωπα. Το πρόγραμμα θα ζητά από τον χρήστη να εισάγει το ετήσιο εισόδημά του και στη συνέχεια θα υπολογίζει τον φόρο βάσει μιας συγκεκριμένης φορολογικής κλίμακας.

 Ο χρήστης αφού εισάγει το ετήσιο εισόδημά του, το πρόγραμμα θα υπολογίσει τον φόρο βάσει της παρακάτω κλίμακας:

Εισόδημα έως 10.000€: 0% φόρος.
Εισόδημα από 10.001€ έως 20.000€: 10% φόρος για το ποσό πάνω από 10.000€.
Εισόδημα από 20.001€ έως 40.000€: 20% φόρος για το ποσό πάνω από 20.000€.
Εισόδημα πάνω από 40.000€: 30% φόρος για το ποσό πάνω από 40.000€.
Το πρόγραμμα θα υπολογίζει και θα εμφανίζει το συνολικό ποσό φόρου που πρέπει να πληρώσει ο χρήστης, καθώς και το καθαρό εισόδημά του μετά την αφαίρεση του φόρου.

Χρησιμοποιήστε διαχείριση σφαλμάτων με try-except για τον έλεγχο της εγκυρότητας της εισόδου του χρήστη (π.χ. αν εισαχθεί κάτι άλλο αντί για αριθμό).

 

Παραδείγματα εκτέλεσης:

Εισάγετε το ετήσιο εισόδημά σας: 21000
Συνολικός φόρος: 1200.00€

Καθαρό εισόδημα: 19800.00€

Εισάγετε το ετήσιο εισόδημά σας: 43000
Συνολικός φόρος: 5900.00€

Καθαρό εισόδημα: 37100.00€

Εισάγετε το ετήσιο εισόδημά σας: 7000
Συνολικός φόρος: 0.00€

Καθαρό εισόδημα: 7000.00€