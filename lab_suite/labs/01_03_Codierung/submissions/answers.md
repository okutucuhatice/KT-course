# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---

**2. Deine Kommentierung**

- Was zeigen die ausgegebenen Huffman-Codes?  
Die ausgegebenen Huffman-Codes zeigen, dass die Zeichen unterschiedlich lang codiert werden. Häufig vorkommende Zeichen bekommen kürzere Codes, während seltene Zeichen längere Codes erhalten.

- Warum haben häufigere Zeichen kürzere Codewörter?  
Häufigere Zeichen haben kürzere Codewörter, weil sie in der Nachricht öfter vorkommen. Dadurch braucht man insgesamt weniger Bits und die Codierung wird effizienter als bei einer festen Codierung mit gleich langen Codewörtern.

---

## Konsolenausgabe

```
Enter the string to compute Huffman Code Tree: ---------------------------------------------------------
Dictionary of Characters with char frequency:       {'B': 1, 'C': 6, 'A': 5, 'D': 3}
Dictionary converted into a list:                   dict_items([('B', 1), ('C', 6), ('A', 5), ('D', 3)])
List of characters sorted to descending frequency:  [('C', 6), ('A', 5), ('D', 3), ('B', 1)]
Huffman Code Dictionary:                            {'C': '0', 'B': '100', 'D': '101', 'A': '11'}

 Char | Huffman code 
----------------------
 'C'  |           0
 'A'  |          11
 'D'  |         101
 'B'  |         100
```
