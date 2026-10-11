# PLANIMETRIA: TRÓJKĄTY – KOMPLETNE KOMPENDIUM NA 100%
**Poziom podstawowy (szkoła ponadpodstawowa)**

---

## 📌 SPIS TREŚCI
1. **Twierdzenie Pitagorasa i działania na pierwiastkach**
2. **Własności trójkąta równoramiennego i równobocznego**
3. **Trójkąty charakterystyczne: $45^\circ - 45^\circ - 90^\circ$ oraz $30^\circ - 60^\circ - 90^\circ$**
4. **Rozcinanie trójkątów dowolnych na trójkąty szczególne (HIT SPRAWDZIANÓW)**
5. **Ważne punkty w trójkącie: Środek ciężkości i Ortocentrum**
6. **Przystawanie trójkątów (cechy BBB, BKB, KBK)**
7. **Wysokość w trójkącie prostokątnym opuszczona na przeciwprostokątną**
8. **KROK PO KROKU: Dokładne rozwiązania zadań ze zdjęć**
9. **Złota lista pułapek i błędów, na których ucinają punkty**

---

## 1. TWIERDZENIE PITAGORASA I PIERWIASTKI

> [!IMPORTANT]
> Twierdzenie Pitagorasa działa **TYLKO I WYŁĄCZNIE** w trójkątach prostokątnych!
> Jeśli przyprostokątne to $a$ i $b$, a przeciwprostokątna to $c$, to:
> $$a^2 + b^2 = c^2$$

### Działania na pierwiastkach, które musisz opanować do perfekcji:
Na sprawdzianie z tego działu boki niemal zawsze mają pierwiastki. Pamiętaj:
- Potęgowanie iloczynu z pierwiastkiem:
  $$(2\sqrt{5})^2 = 2^2 \cdot (\sqrt{5})^2 = 4 \cdot 5 = 20$$
  $$(3\sqrt{2})^2 = 3^2 \cdot (\sqrt{2})^2 = 9 \cdot 2 = 18$$
  $$(4\sqrt{2})^2 = 16 \cdot 2 = 32$$
  $$(2\sqrt{7})^2 = 4 \cdot 7 = 28$$
  $$(4\sqrt{6})^2 = 16 \cdot 6 = 96$$
- Mnożenie pierwiastków:
  $$\sqrt{3} \cdot \sqrt{3} = 3$$
  $$4\sqrt{3} \cdot \sqrt{3} = 4 \cdot 3 = 12$$
- Wyłączanie czynnika przed pierwiastek:
  $$\sqrt{189} = \sqrt{9 \cdot 21} = 3\sqrt{21}$$
  $$\sqrt{288} = \sqrt{144 \cdot 2} = 12\sqrt{2}$$
- Usuwanie niewymierności z mianownika:
  $$\frac{4\sqrt{6}}{\sqrt{2}} = 4\sqrt{\frac{6}{2}} = 4\sqrt{3}$$
  $$\frac{a}{\sqrt{2}} = \frac{a\sqrt{2}}{2}$$

---

## 2. TRÓJKĄT RÓWNORAMIENNY I RÓWNOBOCZNY

### A. Trójkąt równoramienny
- Posiada dwa ramiona równej długości ($b$) i podstawę ($a$).
- **Kluczowa cecha na sprawdzian:** Wysokość $h$ opuszczona na podstawę dzieli podstawę na **dwie równe połowy** ($\frac{a}{2}$ i $\frac{a}{2}$) oraz dzieli kąt przy wierzchołku na pół!
- Z twierdzenia Pitagorasa w połowie trójkąta:
  $$h^2 + \left(\frac{a}{2}\right)^2 = b^2$$

### B. Trójkąt równoboczny (bok $a$)
Wszystkie boki równe, wszystkie kąty mają po $60^\circ$.
Te dwa wzory **musisz znać na pamięć**:
1. **Wysokość:**
   $$h = \frac{a\sqrt{3}}{2}$$
2. **Pole powierzchni:**
   $$P = \frac{a^2\sqrt{3}}{4}$$

*Przykład ze zdjęcia:* Bok $a = 10\text{ cm}$.
$$P = \frac{10^2\sqrt{3}}{4} = \frac{100\sqrt{3}}{4} = 25\sqrt{3}\text{ cm}^2$$

---

## 3. TRÓJKĄTY CHARAKTERYSTYCZNE (SZCZEGÓLNE)

To najważniejszy temat z Twoich notatek! Zamiast funkcji trygonometrycznych (sinus, cosinus), na poziomie podstawowym boki tych trójkątów wyznacza się z gotowych zależności.

```
       Trójkąt 45°-45°-90°                    Trójkąt 30°-60°-90°
         (połowa kwadratu)                (połowa trójkąta równobocznego)

               /|                                     /|
              / |                                    / |
             /  |                               2a  /  | a√3
       a√2  /   | a                                /   | (naprzeciw 60°)
           /    |                                 /    |
          /45° _|                                / 30° |
         /____|_|                               /______|
            a                                      a
                                            (naprzeciw 30°)
```

### Typ I: Kąty $45^\circ - 45^\circ - 90^\circ$ (połowa kwadratu)
- Przyprostokątne są równe: $a$ oraz $a$.
- Przeciwprostokątna to przekątna kwadratu: $c = a\sqrt{2}$.
- **Jak przeliczać:**
  - Znasz przyprostokątną $a$ $\rightarrow$ przeciwprostokątna to $a\sqrt{2}$.
  - Znasz przeciwprostokątną $c$ $\rightarrow$ przyprostokątna to $a = \frac{c}{\sqrt{2}} = \frac{c\sqrt{2}}{2}$.
  - *Przykład:* Jeśli $c = 4\sqrt{6}$, to $a = \frac{4\sqrt{6}}{\sqrt{2}} = 4\sqrt{3}$.

### Typ II: Kąty $30^\circ - 60^\circ - 90^\circ$ (połowa trójkąta równobocznego)
> [!CAUTION]
> Zapamiętaj położenie boków względem kątów:
> - Naprzeciw kąta **$30^\circ$** leży **najkrótszy bok**: $a$
> - Naprzeciw kąta **$60^\circ$** leży **średni bok**: $a\sqrt{3}$
> - Naprzeciw kąta **$90^\circ$** leży **przeciwprostokątna**: $2a$

- **Jak przeliczać:**
  1. Zawsze dąż do wyznaczenia boku $a$ (leżącego naprzeciw $30^\circ$)!
  2. Jeśli znasz przeciwprostokątną ($2a$), podziel ją przez $2$, aby mieć $a$.
  3. Jeśli znasz bok naprzeciw $60^\circ$ ($a\sqrt{3}$), podziel go przez $\sqrt{3}$, aby mieć $a$.

---

## 4. ROZCINANIE TRÓJKĄTÓW NA DWA TRÓJKĄTY SZCZEGÓLNE
Typowe zadanie ze sprawdzianu (obecne w Twoim zeszycie i na tablicy):
Mamy trójkąt, który **nie jest prostokątny**, ale znamy jego dwa kąty, np. $45^\circ$ i $60^\circ$ (trzeci kąt to $180^\circ - 45^\circ - 60^\circ = 75^\circ$).

### Schemat postępowania:
1. **Rysujemy wysokość** z wierzchołka o kącie $75^\circ$.
2. Wysokość dzieli kąt $75^\circ$ na dwa kąty: $45^\circ$ oraz $30^\circ$.
3. Powstają dwa trójkąty prostokątne:
   - Lewy: o kątach $45^\circ - 45^\circ - 90^\circ$.
   - Prawy: o kątach $30^\circ - 60^\circ - 90^\circ$.
4. Mają one **wspólny bok** – wysokość $h$!
5. Z jednego trójkąta wyliczamy wysokość $h$, a następnie przechodzimy z nią do drugiego trójkąta.

---

## 5. WAŻNE PUNKTY W TRÓJKĄCIE

### A. Środek ciężkości trójkąta
- **Co to jest środkowa?** Odcinek łączący wierzchołek trójkąta ze środkiem przeciwległego boku.
- Każdy trójkąt ma 3 środkowe, które przecinają się w **jednym punkcie** – nazywamy go **środkiem ciężkości trójkąta**.
- **Najważniejsza własność (ZADAWANA NA KAŻDYM SPRAWDZIANIE):**
  Środek ciężkości dzieli każdą środkową w stosunku **$2 : 1$**, licząc od wierzchołka!
  - Odległość środka ciężkości od wierzchołka = $\frac{2}{3}$ długości środkowej.
  - Odległość środka ciężkości od boku (podstawy) = $\frac{1}{3}$ długości środkowej.

```
                  C
                 / \
                /   \
               /  |  \        Odległość od wierzchołka: 2x = (2/3)·d
              /   |   \
             /    S    \  <- ŚRODEK CIĘŻKOŚCI
            /     |     \
           /      |      \    Odległość od podstawy: x = (1/3)·d
          A-------D-------B
                 |<- środek boku AB
```

### B. Ortocentrum trójkąta
- **Definicja:** Punkt przecięcia prostych zawierających **wysokości** trójkąta.
- **Pytanie testowe o położenie ortocentrum:**
  - W trójkącie **ostrokątnym** $\rightarrow$ leży **wewnątrz** trójkąta.
  - W trójkącie **prostokątnym** $\rightarrow$ leży **w wierzchołku kąta prostego**!
  - W trójkącie **rozwartokątnym** $\rightarrow$ leży **na zewnątrz** trójkąta (wysokości przecinają się na przedłużeniach boków).

---

## 6. PRZYSTAWANIE TRÓJKĄTÓW

Dwa trójkąty są **przystające** ($\equiv$), jeśli mają dokładnie taki sam kształt i takie same wymiary (jeden jest wierną kopią drugiego). Ich odpowiadające sobie boki i kąty są równe.

### Trzy cechy przystawania:
1. **BBB (Bok - Bok - Bok):**
   Jeśli trzy boki jednego trójkąta są równe trzem bokom drugiego trójkąta.
2. **BKB (Bok - Kąt - Bok):**
   Dwa boki i kąt **pomiędzy nimi** w jednym trójkącie są równe dwóm bokom i kątowi między nimi w drugim trójkącie.
3. **KBK (Kąt - Bok - Kąt):**
   Dwa kąty i bok **leżący między nimi** w jednym trójkącie są równe dwóm kątom i bokowi między nimi w drugim trójkącie.

> [!TIP]
> **Zasada rozwiązywania zadań z przystawania (np. Zadanie 1 z tablicy):**
> Zawsze najpierw oblicz trzeci kąt w każdym trójkącie ($180^\circ - \alpha - \beta$).
> Potem dopasowuj boki: bok leżący naprzeciw kąta o danej mierze w pierwszym trójkącie odpowiada bokowi leżącemu naprzeciw **takiego samego kąta** w drugim trójkącie!

---

## 7. WYSOKOŚĆ W TRÓJKĄCIE PROSTOKĄTNYM (Wierzchołek kąta prostego)

Jeśli w trójkącie prostokątnym o przyprostokątnych $a, b$ i przeciwprostokątnej $c$ poprowadzimy wysokość $h_c$ z kąta prostego na przeciwprostokątną:

Pole trójkąta można zapisać na dwa sposoby:
$$P = \frac{a \cdot b}{2} \quad \text{oraz} \quad P = \frac{c \cdot h_c}{2}$$

Porównując te pola, otrzymujemy genialny i szybki wzór:
$$h_c = \frac{a \cdot b}{c}$$

---

## 8. DOKŁADNE ROZWIĄZANIA ZADAŃ ZE ZDJĘĆ

### ZADANIE 1 (z tablicy – Trójkąt równoramienny i środek ciężkości)
> **Treść:** W trójkącie równoramiennym podstawa ma długość 12, a ramiona mają długość 15. Jaka jest odległość środka ciężkości tego trójkąta od jego podstawy?

**Rozwiązanie krok po kroku:**
1. Wysokość opuszczona na podstawę dzieli ją na dwie równe części:
   $$x = \frac{12}{2} = 6$$
2. Z twierdzenia Pitagorasa liczymy wysokość $h$:
   $$h^2 + 6^2 = 15^2$$
   $$h^2 + 36 = 225$$
   $$h^2 = 225 - 36 = 189$$
   $$h = \sqrt{189} = \sqrt{9 \cdot 21} = 3\sqrt{21}$$
3. W trójkącie równoramiennym wysokość opuszczona na podstawę jest jednocześnie środkową.
4. Środek ciężkości dzieli środkową w stosunku $2:1$, a więc odległość od podstawy stanowi $\frac{1}{3}$ całej wysokości:
   $$d = \frac{1}{3} \cdot h = \frac{1}{3} \cdot 3\sqrt{21} = \sqrt{21}$$
**Odpowiedź:** Odległość wynosi $\sqrt{21}$.

---

### ZADANIE 2 (z zeszytu / tablicy – Obwód trójkąta z kątami $45^\circ$ i $60^\circ$)
> **Treść:** Oblicz obwód trójkąta podzielonego wysokością na dwa trójkąty szczególne, gdzie przeciwprostokątna w trójkącie $45^\circ-45^\circ-90^\circ$ wynosi $4\sqrt{6}$.

**Rozwiązanie krok po kroku:**
1. W lewym trójkącie ($45^\circ - 45^\circ - 90^\circ$):
   - Przeciwprostokątna to $a\sqrt{2} = 4\sqrt{6}$
   - Przyprostokątna (wysokość $h$):
     $$a = \frac{4\sqrt{6}}{\sqrt{2}} = 4\sqrt{3}$$
   - Zatem wysokość $h = 4\sqrt{3}$, a lewy fragment podstawy wynosi również $4\sqrt{3}$.
2. W prawym trójkącie ($30^\circ - 60^\circ - 90^\circ$):
   - Wysokość $h = 4\sqrt{3}$ leży naprzeciw kąta $30^\circ$, czyli $a = 4\sqrt{3}$.
   - Przeciwprostokątna (prawe ramię):
     $$2a = 2 \cdot 4\sqrt{3} = 8\sqrt{3}$$
   - Prawy fragment podstawy (naprzeciw $60^\circ$):
     $$a\sqrt{3} = 4\sqrt{3} \cdot \sqrt{3} = 4 \cdot 3 = 12$$
3. Cała podstawa trójkąta:
   $$podstawa = 4\sqrt{3} + 12$$
4. Obwód trójkąta:
   $$Ob = 4\sqrt{3} + 8\sqrt{3} + 12 = 12\sqrt{3} + 12$$

---

### ZADANIE 3 (z karty pracy – Zadanie 6)
> **Treść:** W trójkącie prostokątnym przeciwprostokątna jest 3 razy dłuższa od najkrótszego boku, a długość trzeciego boku wynosi $12\sqrt{2}$. Oblicz wysokość tego trójkąta poprowadzoną z wierzchołka kąta prostego.

**Rozwiązanie krok po kroku:**
1. Oznaczamy boki:
   - Najkrótsza przyprostokątna: $a = x$
   - Druga przyprostokątna: $b = 12\sqrt{2}$
   - Przeciwprostokątna: $c = 3x$
2. Stosujemy twierdzenie Pitagorasa:
   $$x^2 + (12\sqrt{2})^2 = (3x)^2$$
   $$x^2 + 144 \cdot 2 = 9x^2$$
   $$x^2 + 288 = 9x^2$$
   $$8x^2 = 288 \implies x^2 = 36 \implies x = 6$$
3. Boki trójkąta to:
   - $a = 6$
   - $b = 12\sqrt{2}$
   - $c = 3 \cdot 6 = 18$
4. Wysokość $h$ z wierzchołka kąta prostego liczymy ze wzoru $h = \frac{a \cdot b}{c}$:
   $$h = \frac{6 \cdot 12\sqrt{2}}{18} = \frac{72\sqrt{2}}{18} = 4\sqrt{2}$$
**Odpowiedź:** Wysokość wynosi $4\sqrt{2}$.

---

### ZADANIE 4 (z karty pracy – Zadanie 1: Pitagoras)
- **Podpunkt a:** Przyprostokątne $4$ i $2\sqrt{5}$. Szukamy przeciwprostokątnej $x$:
  $$x^2 = 4^2 + (2\sqrt{5})^2 = 16 + 20 = 36 \implies x = 6$$
- **Podpunkt b:** Przyprostokątna $2$, przeciwprostokątna $\sqrt{13}$. Szukamy przyprostokątnej $y$:
  $$2^2 + y^2 = (\sqrt{13})^2 \implies 4 + y^2 = 13 \implies y^2 = 9 \implies y = 3$$
- **Podpunkt c:** Przyprostokątne $c$ i $3\sqrt{2}$, przeciwprostokątna $4\sqrt{2}$:
  $$c^2 + (3\sqrt{2})^2 = (4\sqrt{2})^2 \implies c^2 + 18 = 32 \implies c^2 = 14 \implies c = \sqrt{14}$$

---

### ZADANIE 5 (z karty pracy – Zadanie 2d rozwiązywane na tablicy)
> **Treść:** Dwa połączone trójkąty prostokątne o wspólnej przyprostokątnej $\sqrt{3}$. Pierwszy ma przeciwprostokątną $\sqrt{7}$, drugi ma przeciwprostokątną $2\sqrt{7}$. Oblicz różnicę odcinków $w = |BD| - |CD|$.

**Rozwiązanie krok po kroku:**
1. W trójkącie mniejszym:
   $$(\sqrt{3})^2 + |CD|^2 = (\sqrt{7})^2 \implies 3 + |CD|^2 = 7 \implies |CD|^2 = 4 \implies |CD| = 2$$
2. W trójkącie większym:
   $$(\sqrt{3})^2 + |BD|^2 = (2\sqrt{7})^2 \implies 3 + |BD|^2 = 4 \cdot 7 = 28 \implies |BD|^2 = 25 \implies |BD| = 5$$
3. Szukany odcinek:
   $$w = |BD| - |CD| = 5 - 2 = 3$$

---

## 9. ZŁOTA LISTA PUŁAPEK NA SPRAWDZIANIE

1. **Pomylenie boków w $30^\circ - 60^\circ - 90^\circ$:**
   - Zawsze sprawdzaj dwa razy: naprzeciw $30^\circ$ leży $a$, a naprzeciw $60^\circ$ leży $a\sqrt{3}$. Nigdy na odwrót!
2. **Pytanie o odległość środka ciężkości:**
   - Przeczytaj dokładnie pytanie: czy pytają o odległość od **wierzchołka** ($\frac{2}{3}h$), czy od **podstawy** ($\frac{1}{3}h$)?
3. **Zapomnienie o nawiasie przy potęgowaniu:**
   - Pisz $(2\sqrt{5})^2 = 4 \cdot 5 = 20$, a nie $2\sqrt{5}^2 = 10$.
4. **Ortocentrum w trójkącie prostokątnym:**
   - Częste pytanie jednokrotnego wyboru na sprawdzianie: gdzie leży ortocentrum w trójkącie prostokątnym? Odpowiedź: **w wierzchołku kąta prostego**.
5. **Cechy przystawania:**
   - W cesze BKB kąt **musi leżeć między danymi bokami**, nie gdziekolwiek!
