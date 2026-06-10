# Kontekst biznesowy

Nasz zespół Performance Marketingu oflagował konkretny segment użytkowników (`flagged_segment`), który generuje niepokojąco wysokie koszty przy relatywnie niskim przychodzie z pojedynczego zamówienia.

Zarząd rozważa całkowite wyłączenie kampanii dla tego segmentu w celu optymalizacji budżetu.

# Twoje zadanie

Jako analityk masz zweryfikować tę hipotezę i podjąć decyzję:

**Tniemy budżet czy inwestujemy dalej?**

# Pytania do analizy:

## 1. Rentowność netto

Czy segment jest faktycznie stratny, gdy weźmiemy pod uwagę `marketing_cost`?

Oblicz:

```text
Profit = Revenue - Cost
```

## 2. Lojalność vs. Transakcyjność

Czy zachowanie tych użytkowników w czasie (Retention/Lifetime Orders) uzasadnia wyższy koszt ich pozyskania i obsługi (liczba sesji)?

## 3. Jakość danych

Czy ufasz tym danym?

Wskaż ewentualne anomalie, które mogą wpływać na wynik analizy.

## 4. Rekomendacja

Przedstaw konkretną decyzję biznesową:

* **Stop**
* **Continue**
* **Pivot** (zmiana strategii)

Uzasadnij ją jedną, kluczową metryką.

# Dane

**Plik:** `users_orders.csv`

## Opis kolumn

* `marketing_cost` – Bezpośredni koszt przypisany do zamówienia.
* Pozostałe kolumny:

  * `device`
  * `channel`
  * `country`
  * `sessions_before_order`
  * `lifetime_orders_so_far`
  * itd.
