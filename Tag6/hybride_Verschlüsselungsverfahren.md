* **Was bezweckt der Session-Key?**
  Der Session-Key ist ein einmaliger Schlüssel für die symmetrische Verschlüsselung der Nachricht.

* **Was ist der wesentliche Unterschied zu RSA oder Diffie-Hellman?**
  Hybride Verfahren kombinieren symmetrische und asymmetrische Verschlüsselung – RSA und DH allein sind rein asymmetrisch.


* **Unterschied zu RSA:**
  RSA verschlüsselt die ganze Nachricht asymmetrisch, was langsam ist. Hybride Verfahren (z. B. RSA-AES) verschlüsseln nur den Session-Key mit RSA – die eigentliche Nachricht wird schnell mit AES (symmetrisch) verschlüsselt.

* **Unterschied zu Diffie-Hellman:**
  Diffie-Hellman dient nur dem sicheren Austausch eines gemeinsamen Schlüssels, verschlüsselt aber keine Nachrichten direkt. Hybride Verfahren verschlüsseln Inhalte aktiv mit diesem Schlüssel.



![image](https://github.com/user-attachments/assets/8ce0a64d-307e-43d6-a19a-c2be03da3b53)
