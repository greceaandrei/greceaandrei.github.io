<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

[Homepage](index.md)

# Diagrame de tip _flowchart_

```
flowchart LR
A[Anul I] --> |Tranzitie usoara| B[Anul II]
A -.-> |Tranzitie grea| C[\Anul IV/]
C --> |Tranzitie medie| D(Master)
```

```mermaid
flowchart LR
A[Anul I] --> |Tranzitie usoara| B[Anul II]
A -.-> |Tranzitie grea| C[\Anul IV/]
C --> |Tranzitie medie| D(Master)
```

** De retinut **
- Diagramele _flowchart_ _au noduri_ si _conectori_
- Nodurile au:
 - forma (data de parantezele folosite la descrierea _nodului_)
 - ID (sirul folosti in afra descrierii nodului)
 - Descriere (textul ce apare in caseta nodului si care este implementat in interiorul diferitelor tipuri de paranteze - ce decid forma casetei nodului)
 - Conectorii au:
   - Diferite tipuri de sageti sau chiar pot activa fara sageti
   - Diferite tipuri de linii: `-->` linie continua, `-.->` linie punctata, `--` linie continua fara sageti, `<-->` linie continua cu sageti in ambele sensuri, `==>` linie ingrosata cu sageata spre dreapta.
