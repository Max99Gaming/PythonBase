<div align="center">
  <img height="250" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/935px-Python-logo-notext.svg.png"  />
</div>

###

<h1 align="left">Python facile</h1>

###

Python è un linguaggio di programmazione ad alto livello, interpretato, dinamico e orientato agli oggetti. È un linguaggio molto popolare e utilizzato in molteplici contesti, come lo sviluppo web, l'analisi dei dati, l'intelligenza artificiale e la robotica.

Ecco alcuni concetti base di Python con relativi esempi di codice:

### Variabili e tipi di dati
[Scopri di più sulle variabili](https://github.com/onlyymax/PythonBase/blob/main/VARIABILI.md)

In Python, le variabili sono utilizzate per memorizzare valori. Il tipo di dato della variabile viene determinato automaticamente in base al valore che gli viene assegnato.

```python
# Esempio di variabile
x = 10
y = "Ciao, mondo!"
```

Python supporta vari tipi di dati, tra cui:

- Integers: numeri interi senza parte decimale
- Floats: numeri con parte decimale
- Strings: sequenze di caratteri
- Lists: sequenze di elementi ordinati
- Tuples: sequenze di elementi immutabili
- Dictionaries: collezioni di elementi con una chiave associata

```python
# Esempio di tipi di dati
x = 10
y = 3.14
z = "Ciao, mondo!"
lista = [1, 2, 3, 4]
tupla = (1, "due", 3.0)
dizionario = {"nome": "Mario", "cognome": "Rossi", "età": 30}
```

### Operatori

Python supporta numerosi operatori che possono essere utilizzati per eseguire operazioni su variabili e tipi di dati. Questi includono operatori aritmetici, operatori di confronto e operatori logici.

```python
# Esempio di operatori aritmetici
x = 10
y = 3
somma = x + y
differenza = x - y
prodotto = x * y
divisione = x / y
modulo = x % y
esponente = x ** y

# Esempio di operatori di confronto
a = 10
b = 5
c = 10
uguale = a == b
diverso = a != b
maggiore = a > b
minore = a < b
maggiore_uguale = a >= c
minore_uguale = b <= c

# Esempio di operatori logici
p = True
q = False
r = True
e = p and q
o = p or q
non_p = not p
```

### Condizioni e cicli

Python supporta le strutture di controllo condizionale e cicli per eseguire operazioni in base a determinate condizioni o per un numero specifico di volte.

```python
# Esempio di if-else
x = 10
if x > 5:
    print("x è maggiore di 5")
else:
    print("x è minore o uguale a 5")

# Esempio di for loop
lista = [1, 2, 3, 4]
for elemento in lista:
    print(elemento)

# Esempio di while loop
i = 0
while i < 5:
    print(i)
    i += 1
```

### Funzioni

Le funzioni in Python sono blocchi di codice riutilizzabili che possono essere richiamati da diverse parti del programma.

```python
# Esempio di funzione
def saluta(nome):
    print("Ciao, " + nome + "!")

# Richiamo della funzione
saluta("Mario")
```

Questi sono solo alcuni dei concetti di base di Python. Con una buona comprensione di questi concetti, è possibile iniziare a scrivere programmi Python più complessi.
