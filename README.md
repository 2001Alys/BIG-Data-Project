# BIG-Data-Project

## **Analiza powodów decyzji banku dotyczącej udzielenia kredytu mieszkaniowego na podstawie danych „Loan-Approval-Prediction-Dataset”**

### Źródło danych

Dane wykorzystane w projekcie pochodzą z platformy Kaggle:

https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset/data

---

# Opis danych do analizy

## Charakterystyka zbioru danych

- **Liczba rekordów:** 4269
- **Liczba atrybutów:** 13

### Lista atrybutów

| Atrybut | Opis |
|----------|----------|
| `loan_id` | Identyfikator wniosku kredytowego *(nie będzie wykorzystywany w analizie)* |
| `no_of_dependents` | Liczba osób na utrzymaniu *(numeryczny)* |
| `education` | Wykształcenie wyższe *(Graduate / Not Graduate → 1 / 0)* |
| `self_employed` | Status samozatrudnienia *(Yes / No → 1 / 0)* |
| `income_annum` | Roczny dochód kredytobiorcy *(tys.)* |
| `loan_amount` | Kwota kredytu *(tys.)* |
| `loan_term` | Okres kredytowania w miesiącach |
| `cibil_score` | Ocena zdolności kredytowej |
| `residential_assets_value` | Wartość nieruchomości mieszkalnych *(tys.)* |
| `commercial_assets_value` | Wartość nieruchomości komercyjnych *(tys.)* |
| `luxury_assets_value` | Wartość dóbr luksusowych *(tys.)* |
| `bank_asset_value` | Wartość aktywów zgromadzonych w bankach *(tys.)* |
| `loan_status` | Status decyzji kredytowej *(Approved / Rejected → 1 / 0)* |

---

# Założenia projektowe

## Cel projektu

Celem projektu jest:

- identyfikacja czynników mających największy wpływ na decyzję banku dotyczącą przyznania kredytu hipotecznego,
- określenie siły wpływu poszczególnych atrybutów na decyzję kredytową,
- opracowanie modelu predykcyjnego umożliwiającego przewidywanie decyzji banku dla nowych wniosków kredytowych,
- ocena jakości i skuteczności opracowanych modeli analitycznych.

---

# Wybrane techniki analizy

## 1. Eksploracyjna Analiza Danych (EDA)

Analiza danych obejmująca:

- badanie rozkładów zmiennych,
- identyfikację wartości odstających,
- analizę zależności pomiędzy cechami,
- analizę korelacji pomiędzy zmiennymi.

### Wykorzystane wizualizacje

- histogramy,
- wykresy punktowe (*scatter plots*),
- macierz korelacji,
- wykresy pudełkowe (*boxplot*).

---

## 2. Klastrowanie

Podział klientów na podobne grupy w celu:

- identyfikacji segmentów klientów,
- wykrycia wspólnych cech kredytobiorców,
- analizy zależności pomiędzy segmentem klienta a decyzją kredytową.

---

## 3. Drzewa decyzyjne

Analiza wpływu poszczególnych atrybutów na decyzję banku:

- tworzenie reguł decyzyjnych,
- wyznaczenie najważniejszych cech wpływających na przyznanie kredytu,
- interpretacja procesu decyzyjnego banku.

---

## 4. Walidacja krzyżowa

Ocena jakości modeli przy użyciu walidacji krzyżowej:

- sprawdzenie stabilności modelu,
- ograniczenie ryzyka przeuczenia (*overfitting*),
- porównanie skuteczności różnych modeli.

---

## 5. Regresja i predykcja

Budowa modelu predykcyjnego umożliwiającego ocenę:

> Czy dla podanych parametrów klienta bank przyzna kredyt hipoteczny?

Analiza pozwoli określić prawdopodobieństwo uzyskania pozytywnej decyzji kredytowej na podstawie dostępnych danych.

---

# Oczekiwane rezultaty

Projekt powinien umożliwić:

- wskazanie najważniejszych czynników wpływających na decyzję kredytową,
- wizualizację zależności występujących w danych,
- segmentację klientów na podstawie podobnych cech,
- budowę modelu wspomagającego proces podejmowania decyzji kredytowych,
- ocenę skuteczności opracowanego modelu predykcyjnego.

---

# Autorzy

Projekt realizowany w ramach projektu uczelnianego.
