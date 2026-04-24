---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Übung 1: Grundlagen

Klicke oben auf 🚀 -> **Live Code**, um diese Seite interaktiv zu machen! 
*(Hinweis: Beim ersten Mal kann es 1-2 Minuten dauern, bis der Binder-Server im Hintergrund gestartet ist).*

### Deine Aufgabe
Schreibe eine Funktion `addiere(a, b)`, die zwei Zahlen addiert und das Ergebnis zurückgibt.

```{code-cell} python
def addiere(a, b):
    # DEIN CODE HIER
    pass
```


```{code-cell} python
try:
    assert addiere(2, 3) == 5, "Fehler: 2 + 3 sollte 5 ergeben!"
    assert addiere(-1, 1) == 0, "Fehler: -1 + 1 sollte 0 ergeben!"
    assert addiere(10, 20) == 30, "Fehler: 10 + 20 sollte 30 ergeben!"
    print("✅ Herzlichen Glückwunsch! Alle Tests bestanden. Dein Code ist korrekt.")
except AssertionError as e:
    print(f"❌ Autograder fehlgeschlagen: {e}")
except Exception as e:
    print(f"⚠️ Ein anderer Fehler ist aufgetreten: {e}")
```

