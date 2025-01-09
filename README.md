# adise24_001057058



Μπορείτε να μεταβείτε στο παιχνίδι πατώντας τον σύνδεσμο: https://users.iee.ihu.gr/~iee2020001/adise24_001057058/html/

## ΕΠΕΞΗΓΗΣΗ PROJECT

Το project με όνομα BLOKUS περιλαμβάνει μια ιστοσελίδα στην οποία ο χρήστης αρχικά θα πρέπει να έχει κάνει την αυθεντικοποίηση του με τα κατάλληλα στοιχεία εισόδου (Όνομα και Κωδικός). Σε περίπτωση που δεν έχει λογαριασμό, μπορεί να φτιάξει έναν, πατώντας το κατάλληλο κουμπί που θα τον κατευθύνει σε ιστοσελίδα για την εγγραφή του. Εκεί θα πρέπει να συμπληρώσει (Όνομα, Κωδικό και Email).

Εφόσον η αυθεντικοποίηση ολοκληρωθεί με επιτυχία, περνώντας δηλαδή τους κατάλληλους ελέγχους εγκυρότητας, κατευθύνεται σε μια ιστοσελίδα αναμονής παικτών, στην οποία περιμένει μέχρι να συνδεθεί κάποιος άλλος στο σύστημα. Η κατάσταση του χρήστη αποθηκεύεται μέσω session cookies, οπότε ακόμα και αν βγει από τον browser και ξαναμπεί στο σύστημα, θα κατευθυνθεί και πάλι στην αναμονή παικτών.

Μόλις συνδεθεί άλλος χρήστης, εξαφανίζεται το παράθυρο αναμονής και οι χρήστες μπορούν να ξεκινήσουν να παίζουν. Παρέχεται επίσης η δυνατότητα στον χρήστη να αποσυνδεθεί, με αποτέλεσμα ο άλλος χρήστης να επιστρέφει στην κατάσταση αναμονής παικτών.

Τέλος, αν δύο παίκτες έχουν ήδη ξεκινήσει το παιχνίδι, το σύστημα αποτρέπει οποιονδήποτε άλλο να συνδεθεί, εμφανίζοντας ένα κατάλληλο μήνυμα που του λέει να περιμένει μέχρι κάποιος άλλος χρήστης να αποσυνδεθεί.

## ΕΠΕΞΗΓΗΣΗ ΤΩΝ APIs

Endpoint: https://users.iee.ihu.gr/~iee2020001/adise24_001057058/lib/board.php <br />
Μέθοδος: GET, POST <br />
Περιγραφή: Παρέχει τη δυνατότητα επιστροφής του board σε μορφή JSON και τροποποίησης στοιχείων ενός κομματιού του board. <br />

Endpoint: https://users.iee.ihu.gr/~iee2020001/adise24_001057058/lib/players.php
Μέθοδος: GET, POST
Περιγραφή: Παρέχει τη δυνατότητα επιστροφής πληροφοριών κατάστασης του παίκτη και τροποποίησης στοιχείων του.

Endpoint: https://users.iee.ihu.gr/~iee2020001/adise24_001057058/lib/login.php
Μέθοδος: POST
Περιγραφή: Παρέχει τη δυνατότητα αλλαγής της κατάστασης σύνδεσης του χρήστη στη βάση δεδομένων και δημιουργίας της συνεδρίας του.

Endpoint: https://users.iee.ihu.gr/~iee2020001/adise24_001057058/lib/logout.php
Μέθοδος: GET
Περιγραφή: Παρέχει τη δυνατότητα αλλαγής της κατάστασης σύνδεσης του χρήστη στη βάση δεδομένων και διαγραφής της συνεδρίας του.

Endpoint: https://users.iee.ihu.gr/~iee2020001/adise24_001057058/lib/check_status.php
Μέθοδος: GET
Περιγραφή: Επιστρέφει την κατάσταση του παιχνιδιού, ώστε να ελεγχθεί αν μπορεί κάποιος παίκτης να εισέλθει.

Endpoint: https://users.iee.ihu.gr/~iee2020001/adise24_001057058/lib/register.php
Μέθοδος: POST
Περιγραφή: Παρέχει τη δυνατότητα καταγραφής στοιχείων του χρήστη στη βάση δεδομένων.





