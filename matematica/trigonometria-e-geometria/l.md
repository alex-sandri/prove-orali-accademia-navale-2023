# Risoluzione di triangoli

Risolvere un triangolo significa determinare tutti i suoi elementi a partire
dagli elementi noti.

| | Lato | Angolo opposto |
| :-: | :-: | :-: |
| Lato 1 / Cateto 1 | $a$ | $\alpha$ |
| Lato 2 / Cateto 2 | $b$ | $\beta$ |
| Lato 3 / Ipotenusa | $c$ | $\gamma$ |

## Triangoli rettangoli

### Teorema di Pitagora

Il quadrato dell'ipotenusa è uguale alla somma dei quadrati degli altri due
cateti, da cui derivano:

$a = \sqrt{c^2 - b^2}$\
$b = \sqrt{c^2 - a^2}$\
$c = \sqrt{a^2 + b^2}$

### 1° teorema

La misura di un cateto è uguale al prodotto tra l'ipotenusa e il seno
dell'angolo opposto al cateto o al coseno dell'angolo compreso tra il cateto e
l'ipotenusa.

| | |
| :-: | :-: |
| $a = c \sin{\alpha}$ | $b = c \sin{\beta}$ |
| $a = c \cos{\beta}$ | $b = c \cos{\alpha}$ |

### 2° teorema

La misura di un cateto è uguale al prodotto tra l'altro cateto e la tangente
dell'angolo opposto al primo o la cotangente dell'angolo opposto al secondo.

| | |
| :-: | :-: |
| $a = b \tan{\alpha}$ | $b = a \tan{\beta}$ |
| $a = b \cot{\beta}$ | $b = a \cos{\alpha}$ |

## Triangoli qualsiasi

### Teorema dei seni (o di Eulero)

Il rapporto tra la misura di un lato e il seno dell'angolo opposto è
**costante**.

$\frac{a}{\sin{\alpha}} = \frac{b}{\sin{\beta}} = \frac{c}{\sin{\gamma}}$

Da questo teorema deriva il ***teorema della corda***:

#### Teorema della corda

Il rapporto costante enunciato nel *teorema dei seni* è uguale al diametro della
circonferenza *circoscritta*.

$\frac{a}{\sin{\alpha}} = \frac{b}{\sin{\beta}} = \frac{c}{\sin{\gamma}} = 2r$

### Teorema del coseno (o di Carnot)

Il quadrato di un lato è uguale alla somma dei quadrati degli altri due
diminuita del doppio del prodotto di questi ultimi per il coseno dell'angolo
fra essi compreso.

$a^2 = b^2 + c^2 - 2bc \cos{\alpha}$\
$b^2 = a^2 + c^2 - 2ac \cos{\beta}$\
$c^2 = a^2 + b^2 - 2ab \cos{\gamma}$

### Teorema delle proiezioni

La misura di un lato è uguale alla somma dei prodotti degli altri due per il
coseno dell'angolo opposto all'altro lato (l'altro tra i due escluso quello da
calcolare).

$a = b \cos{\gamma} + c \cos{\beta}$\
$b = a \cos{\gamma} + c \cos{\alpha}$\
$c = a \cos{\beta} + b \cos{\alpha}$
