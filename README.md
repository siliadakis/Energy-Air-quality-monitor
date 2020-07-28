# energy-air-quality-monitor
Σύστημα παρακολούθησης της κατανάλωσης ηλεκτρικής ισχύος και της ποιότητας του ατμοσφαιρικού αέρα με δυνατότητα προβολής των στοιχείων σε πραγματικό χρόνο μέσω διαδικτύου.
Μόνιτορ παρακολούθησης Κατανάλωσης Ηλεκτρικής Ισχύος & Ποιότητας ατμοσφαιρικού αέρα (εσωτερικού χώρου)
Σχολείο 1ο ΕΠΑΛ Χίου - ΕΚ Χίου. 
Τομείς, ειδικότητες: 
Ηλεκτρονικής/γίας	ειδικότητα Τεχνικός ηλεκτρονικών & υπολογιστικών συστημάτων,εγκαταστάσεων.
Πληροφορικής	ειδικότητα Τεχνικός εφαρμογών πληροφορικής 
Συντάκτης: Ηλιαδάκης Σταμάτης
Υπεύθυνοι έργου : Ηλιαδάκης Σταμάτης, Θεοδωράκης Βασίλειος, Ρερρές Νικόλαος
Τάξεις: A - Β - Γ ΕΠΑΛ 

Σύντομη περιγραφή
Σύστημα παρακολούθησης της κατανάλωσης ηλεκτρικής ισχύος και της ποιότητας του ατμοσφαιρικού αέρα με δυνατότητα προβολής των στοιχείων σε πραγματικό χρόνο μέσω διαδικτύου.
Ειδικότερα θα χρησιμοποιηθούν αισθητήρες επαγωγικής μέτρησης του ρεύματος που καταναλώνεται σε εργαστήριο του σχολείου, καθώς και αισθητήρας που μετράει την ποιότητα του αέρα και συγκεκριμένα του CO2. Τα δεδομένα θα συλλέγονται και από μικροελεγκτές (ESP8266) και μέσω WiFi και του πρωτοκόλλου MQTT θα αποστέλλονται σε κεντρικό υπολογιστή RaspberryPI.
To RaspberryPI με τη χρήση του λογισμικού ανοιχτού κώδικα θα προβάλλει τα στοιχεία αυτά στο διαδίκτυο καθώς και θα ενημερώνει τους ενδιαφερόμενους σε περίπτωση μη επιτρεπτών ορίων. Επιπλέον στόχος είναι η δημιουργία βάσης δεδομένων και στατιστική επεξεργασία των μετρήσεων. Το τελικό αποτέλεσμα θα είναι προσβάσιμο από το διαδίκτυο προσφέροντας τις τιμές της ενέργειας και του CO2. Επίσης θα δίνει τα στοιχεία σε διαγράμματα

Λέξεις κλειδιά – Keywords
IΟΤ, internet of things, RaspberryPI, ESP8266, NodeRED, MQTT, Air Quality Sensors, CO2 sensor ,αισθητήρας CO2, Power Consumption, Electric Power meter, Μετρητής Ηλεκτρικής Ενέργειας, Open data, electric energy footprint, κλιματική αλλαγή.

Σκοπός – Εκπαιδευτικοί Στόχοι:

Σκοποί
Η σχεδίαση και υλοποίηση του συστήματος σκοπεύει :

1.	Στην δημιουργία ενός έξυπνου συστήματος παρακολούθησης της κατανάλωσης ηλεκτρικής ενέργειας και της ποιότητας του αέρα σε κλειστό χώρο με τη χρήση ανοικτών τεχνολογιών.
2.	Στη χρήση των ανοιχτών τεχνολογιών για την επίλυση προβλημάτων της καθημερινότητας συμβάλοντας στην σωστή διάχυση της πληροφορίας με άμεσο και έγκυρο - αξιόπιστο τρόπο.
1.	Στην ευαισθητοποίηση των μαθητών για θέματα που αφορούν
   a.	την κλιματική αλλαγή,
   b.	τις καλές πρακτικές κατανάλωσης ηλεκτρικού ρεύματος,
   c.	την ποιότητα του ατμοσφαιρικού αέρα και τους ρύπους του CO2.
3.	Στην ανάπτυξη καινοτόμας σκέψης.
 
Εκπαιδευτικοί στόχοι

Οι μαθητές μετά την ολοκλήρωση του προγράμματος:
1.	Πρέπει να χρησιμοποιούν το περιβάλλον ανάπτυξης IDE Arduino για τον προγραμματισμό μικροελεγκτών (ESP8266).
2.	Nα ενσωματώνουν βιβλιοθήκες και κώδικα που αφορά την χρήση αισθητήρων και περιφερειακών στη λειτουργία του προγράμματος.
3.	Να εγκαθιστούν το λειτουργικό Raspbian στο RaspberryPI καθώς και των λογισμικών NodeRED και Mosquitto MQTT broker.
4.	Να προγραμματίζουν απλά προγράμματα στο περιβάλλον ανάπτυξης NodeRed
5.	Πρέπει να χρησιμοποιούν το πρόγραμμα fritzing (GNU GPLv3), ή ελεύθερα προγράμματα υλοποίησης ηλεκτρονικών πλακετών για τη δημιουργία πλακέτας PCB.

Περιγραφή

Υπόθεση
Πως μπορώ να δημιουργήσω ένα έξυπνο μετρητή ηλεκτρικής ενέργειας που ανά πάσα στιγμή να μου δείχνει τα KW κατανάλωσης από οποιοδήποτε σημείο;
Υπάρχει τρόπος να μετρήσω το CO2 και τους ρύπους στον ατμοσφαιρικό αέρα δίνοντας ανά πάσα στιγμή τα δεδομένα των μετρήσεων στη διάθεση του καθένα, θα μπορούσε το ίδιο σύστημα να ενημερώνει σε περίπτωση που τα όρια έφταναν σε όρια που χρήζουν προσοχής;
Πως μπορώ από τα στοιχεία αυτά να βελτιώσω την «ενεργειακή» συμπεριφορά μου σαν καταναλωτής, αλλά και να ενημερώνομαι σαν πολίτης συνεισφέροντας έτσι στη διαμόρφωση μιας κουλτούρας που σέβεται το περιβάλλον και τις επόμενες γενιές;


Η μέση άνοδος της θερμοκρασίας σε παγκόσμιο επίπεδο, οι αλλαγές στις βροχοπτώσεις, το λιώσιμο στους πάγους και τους παγετώνες της αρκτικής καθώς και η άνοδος της στάθμης του νερού στις θάλασσες είναι αποτελέσματα που δεν απασχολούν μόνο τους επιστήμονες και την ακαδημαϊκή κοινότητα αλλά επηρεάζουν την καθημερινότητα όλων μας. Είναι οι συνέπειες της κλιματικής αλλαγής που όλοι βιώνουμε τα τελευταία χρόνια πού όπως ορίζεται από τη “Σύμβαση-πλαίσιο των Ηνωμένων
 
Εθνών για την αλλαγή του κλίματος”  οφείλεται άμεσα ή έμμεσα σε ανθρώπινες δραστηριότητες. Σε κάθε περίπτωση οι πολίτες δεν χρειάζεται απλά να ευαισθητοποιηθούν και να ενημερώνονται υπεύθυνα για το πρόβλημα αλλά χρειάζεται σωστή και αξιόπιστη πληροφόρηση σε επίπεδο δεδομένων. Πέρα από τις πολιτικές που ορίζονται από τους παγκόσμιους οργανισμούς και τα κράτη ο πολίτης πρέπει να έχει στοιχεία που αφορούν σε ατομικό επίπεδο και τη δική του συμπεριφορά και δράση. Πρέπει λοιπόν να σκεφτούμε όλοι μας πόσο οι δικές μας συνήθειες επηρεάζουν το κλίμα του πλανήτη την έκκληση του CO2 και πως μπορούμε αλλάζοντας κάποια πράγματα στην καθημερινή μας ζωή να συνεισφέρουμε στην επίλυση του προβλήματος.

Ένας από τους βασικούς παράγοντες απελευθέρωσης CO2 είναι η κατανάλωση ηλεκτρικής ενέργειας που βασίζεται στις καύση ορυκτών καυσίμων . Με λίγα λόγια ο καταναλωτής μειώνοντας την κατανάλωση μπορεί να μειώσει το ενεργειακό του αποτύπωμα  ακολουθώντας κάποιες πρακτικές καλής συμπεριφοράς . Σκεπτόμενοι λίγο πιο έξυπνα στην εποχή της αμεσότητας που ζούμε θα ήταν καλό να μπορεί να παρακολουθεί τη κατανάλωση του ηλεκτρικού ρεύματος ανά πάσα στιγμή έχοντας πραγματική εικόνα για την ηλεκτρική ενέργεια που καταναλώνει σε πραγματικό χρόνο. Στη χώρα μας ο καταναλωτής για τη μέτρηση της ηλεκτρικής ενέργειας στο μεγαλύτερο ποσοστό χρησιμοποιεί το γνωστό ηλεκτρομηχανικό “ρολόι” μετρητή των KWH κατανάλωσης. Η πρόσβαση δεν είναι άμεση και αν κανείς θέλει να δει την κατανάλωση ή πρέπει να επισκέπτεται το μετρητή του σε τακτά χρονικά διαστήματα ή πρέπει να λάβει τον λογαριασμό της εταιρείας παροχής ενέργειας και να κρατάει στοιχεία. Η δημιουργία ενός μετρητή πραγματικού χρόνου κατανάλωσης ηλεκτρικής ενέργειας μπορεί να δώσει εικόνα της κατανάλωσης συμβάλοντας τόσο στην μείωση του ενεργειακού του αποτυπώματος όσο και στην οικονομική του κατάσταση του καταναλωτή. Συμβάλει επίσης στη διαμόρφωση σωστής ενεργειακής συμπεριφοράς και ευαισθητοποίησης των καταναλωτών. Για το λόγο αυτό θα δημιουργήσουμε ένα μετρητή κατανάλωσης ηλεκτρικής ενέργειας που με τρεις αισθητήρες SCT-013-000 YHDC  θα δίνει σε πραγματικό χρόνο για τις τρεις φάσεις τα δεδομένα στον κεντρικό υπολογιστή της εγκατάστασης RaspberryPI.

Η συγκέντρωση διοξειδίου του άνθρακα στον ατμοσφαιρικό αέρα (0,04% 418ppm real time monitor  ) σχετίζεται με την καθημερινή ζωή. Οι μετρήσεις δείχνουν ότι είναι η υψηλότερη τιμή εδώ και 2,1 εκατομμύρια χρόνια . Στις μέρες μας υπάρχουν διάφοροι αισθητήρες και μέθοδοι μέτρησης του CO στην ατμόσφαιρα. Ακόμα και οι οικιακές συσκευές ποιότητας αέρα είναι εφοδιασμένες με τέτοιου είδους αισθητήρες. Στην πρόταση μας συμπεριλαμβάνουμε ένα μικροελεγκτή με αισθητήρα μέτρησης eCO   με στόχο να δώσουμε τις μετρήσεις μας σε πραγματικό χρόνο διαδικτυακά έτσι ώστε οι χρήστες να έχουν εικόνα στο δικό τους χώρο. Η μέτρηση του CO2 θα γίνεται με τον αισθητήρα μέτρησης ποιότητας ατμοσφαιρικού αέρα εσωτερικού χώρου CCS811 της AMS  που εκτός από τα οργανικά σωματίδια δίνει τη μέτρηση του eCO2. Όπως και στην περίπτωση της ηλεκτρικής ενέργειας θα μεταδώσουμε τα στοιχεία μέσω wifi στον κεντρικό υπολογιστή RaspberryPI.

Τα δεδομένα από τους δύο μικροελεγκτές (ΚW ηλεκτρικής ενέργειας και ppm/parts-per-million - μέρη στο εκατομμύριο) με τη χρήση του πρωτοκόλλου MQTT (Message Queuing Telemetry Transport)   θα  μεταδίδονται  στο  RaspberryPI  ο  οποίος  αντίστοιχα  έχει  φορτώσει  το  ενδιάμεσο
λογισμικό Mosquitto  broker που είναι υπεύθυνο για τη λήψη όλων των μηνυμάτων, το φιλτράρισμα των μηνυμάτων, την επιλογή του ενδιαφερομένου και τη δημοσίευση του μηνύματος σε όλους τους
εγγεγραμμένους  πελάτες.  Στη  συνέχεια  τα  μηνύματα  οδηγούνται  στο  λογισμικό  Node  RED  και
επεξεργάζονται σύμφωνα με τον προγραμματισμό που ορίζει ο προγραμματιστής έτσι ώστε να δημοσιευθούν στο διαδίκτυο, να παρουσιαστούν στο διαδίκτυο με τη μορφή διαγραμμάτων, να καταγραφούν σε βάσεις δεδομένων ή να δημιουργήσουν νέα μηνύματα και ενέργειες από το  λογισμικό ή το υλικό του συστήματος.

Όνομα ομάδας: Η ομάδα μας είναι η ECO2-watchers. Το Ε από το Energy consumption. Το
CO2- από το διοξείδιο του άνθρακα.
Υλοποίηση

Για την υλοποίηση της κατασκευής - έργου θα χωριστούμε σε τρεις ομάδες εργασίας.

Στην πρώτη ομάδα συμμετέχουν οι μαθητές της πρώτης τάξης. Στο πλαίσιο του μαθήματος “Αρχές ηλεκτρολογίας ηλεκτρονικής” θα μελετήσουν τα θεωρητικό μέρος του πρότζεκτ που αφορά την κατανάλωση της ηλεκτρικής ενέργειας, την κλιματική αλλαγή και τους τρόπους και αισθητήρες μέτρησεις της ηλεκτρικής ενέργειας και του CO2.
Αντιστοίχως οι μαθητές της Β τάξης των Τομέων Ηλεκτρονικής/γίας και Πληροφορικής θα ασχοληθούν με τον προγραμματισμό των μικροελεγκτών ESP8266 που θα συνδεθούν με τους αισθητήρες και θα μεταδίδουν τα δεδομένα στον κεντρικό υπολογιστή. Αυτό θα γίνει στα πλαίσια του μαθήματος “Εισαγωγή στα υπολογιστικά συστήματα και στα δίκτυα επικοινωνιών.” O προγραμματισμός των μικροελεγκτών ESP8266 θα γίνει με τη βοήθεια του Arduino IDE . Αρχικά τα κυκλώματα που ενσωματώνουν τους αισθητήρες θα δημιουργηθούν σε breadboard ενώ στη συνέχεια θα δημιουργήσουν τις πλακέτες με τη βοήθεια του προγράμματος ανοικτού υλικού fritzing  ή του easyeda (online pcb editor) .

Τέλος οι μαθητές της Γ τάξης του Τομέα Ηλεκτρονικής/γίας θα ασχοληθούν με την εγκατάσταση τη δικτύωση και τον προγραμματισμό των απαιτούμενων λογισμικών (Raspbian - NodeRED - Mosquitto broker) στο RaspberryPI στα πλαίσια του μαθήματος ρομποτικής. Επίσης θα ενημερωθούν για τους τρόπους ασφάλειας του δικτυακού συστήματος.

Μέθοδος υλοποίησης : Ερευνητική εργασία.

Προδιαγραφές

Υλικό
●	RaspberryPI  με κάρτα SD 16G byte            τεμ. 1
●	ESP8266 WiFi Module                          τεμ. 1
●	ESP32 WiFi Module                            τεμ. 1
●	Αισθητήρας CCS811 Air Quality Sensor         τεμ. 1
●	Αισθητήρας ρεύματος SCT-013-000 YHDC 100A	 τεμ. 3
●	Voltage Regulator LD1117					 τεμ. 2
●	Πλακέτα pcb 10x8cm μονής όψης				 τεμ. 2
●	Τροφοδοτικό USB								 τεμ. 2

Λογισμικό
●	Arduino IDE
●	Raspbian
●	NodeRED
●	Mosquitto broker
●	Fritzing ή easyeda online pcb editor
●	Notepad++
●	Github


Αναφορές

  https://drive.google.com/file/d/1dmUcZpEUjEuXGqg8yiJj8ybF2pW4HEma/view?usp=sharing
  https://el.wikipedia.org/wiki/%CE%A3%CF%8D%CE%BC%CE%B2%CE%B1%CF%83%CE%B7-%CE%A0%CE%BB%CE%B1%CE%AF%CF%83%CE%B9%CE%BF_%CF%84%CF%89%CE%BD_%CE%97%CE%BD%CF%89%CE%BC%CE%AD%CE%BD%CF%89%CE%BD_%CE%95%CE%B8%CE%BD%CF%8E%CE%BD_%CE%B3%CE%B9%CE%B1_%CF%84%CE%B9%CF%82_%CE%9A%CE%BB%CE%B9%CE%BC%CE%B1%CF%84%CE%B9%CE%BA%CE%AD%CF%82_%CE%9C%CE%B5%CF%84%CE%B1%CE%B2%CE%BF%CE%BB%CE%AD%CF%82 
  http://openergy.okfn.gr/#/pages/eu2020-targets
  http://www.wwf.gr/footprint/
  http://www.wwf.gr/images/pdfs/wwf_odigos%20ex_energeias.pdf
  https://learn.openenergymonitor.org/electricity-monitoring/ct-sensors/yhdc-sct-013-000-ct-sensor-report
  https://www.esrl.noaa.gov/gmd/ccgg/trends/
  https://www.youtube.com/watch?time_continue=32&v=Yb3NsMJ-YQ8
  https://en.wikipedia.org/wiki/Global_warming_potential
  https://www.sciosense.com/products/environmental-sensors/ccs811-gas-sensor-solution/
  http://mqtt.org/ 
  https://mosquitto.org/
  https://nodered.org/
  https://www.arduino.cc/en/main/software
  https://fritzing.org/
  https://easyeda.com/