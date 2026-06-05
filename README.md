# 📊 Tinder User Behavior & Engagement Dashboard

Kompleksowy projekt analityczny typu End-to-End, skupiający się na procesie ETL, zaawansowanej analizie danych oraz wizualizacji zachowań użytkowników aplikacji Tinder. Projekt został zrealizowany w programie Microsoft Excel z wykorzystaniem Power Query, a jego celem było przekształcenie surowych danych historycznych w interaktywny dashboard menedżerski (Executive Dashboard) wspierający decyzje biznesowe.

## 🚀 Demo projektu (Interaktywny Dashboard)

![Tinder Dashboard Demo](images/twój_plik.gif)

*Powyższy GIF prezentuje interaktywne działanie fragmentatorów (slicers) oraz dynamiczną reakcję wykresów na filtrowanie danych w czasie rzeczywistym.*

---

## 🎯 Cel projektu
Głównym wyzwaniem było uporządkowanie i zanalizowanie anonimowej, reprezentatywnej próbki danych historycznych dotyczących aktywności użytkowników (profilowanie, historia przesunięć w lewo/prawo, liczba dopasowań i wiadomości). Projekt miał za zadanie odpowiedzieć na kluczowe pytania biznesowe:
1. Jakie są różnice w zachowaniach i efektywności korzystania z aplikacji w zależności od płci i wieku?
2. Gdzie występują wąskie gardła w procesie konwersji (Swipe -> Match -> Chat)?
3. Jak segmentować użytkowników, aby zoptymalizować przychody z usług Premium?

## 📂 Źródło danych (Data Source)
Analiza została przeprowadzona na otwartym zbiorze danych (dataset), z którego czerpałem inspirację podczas tworzenia modelu:
* **Kaggle Dataset:** [Tutaj wklej nazwę zbioru lub link, np. Tinder User Behavior Data](TUTAJ_WKLEJ_LINK_Z_KAGGLE)
* *Uwaga: Analiza opiera się na wyodrębnionej, anonimowej próbce badawczej danych demograficznych i behawioralnych, a nie na globalnej, pełnej bazie platformy Tinder.*

---

## 🛠️ Architektura i użyte technologie
* **Power Query (ETL):** Pobranie surowego pliku danych, czyszczenie (usunięcie duplikatów i braków danych), transformacja typów danych, stworzenie spójnego modelu relacyjnego.
* **Tabele i Wykresy Przestawne (Pivot Tables & Charts):** Agregacja danych i wyliczenie zaawansowanych miar (np. współczynników konwersji).
* **Fragmentatory (Slicers):** Stworzenie intuicyjnego, interaktywnego panelu nawigacyjnego do szybkiej filtracji (płeć, grupy wiekowe, status aktywności).
* **Formatowanie Warunkowe (Conditional Formatting):** Automatyczne wyróżnianie skrajnych wartości, ułatwiające natychmiastową identyfikację anomalii w danych.

---

## 📈 Kluczowe wnioski (Data Insights)

* **Segmentacja użytkowników (Power vs. Low Users):** Analiza wykazuje wyraźny podział bazy. Grupa *Power Users* odpowiada za ponad 70% całkowitej aktywności w analizowanej próbce, generując jednocześnie najwyższy wskaźnik zaangażowania w wiadomościach tekstowych.
* **Współczynnik konwersji (Match Rate & Swipe Ratio):** Zauważalny jest silny „Gender Gap” w strategiach korzystania z aplikacji. Mężczyźni wykazują znacznie wyższy wskaźnik przesunięć w prawo (*Likes*), co jednak przekłada się na niższy procentowy *Match Rate* w porównaniu do kobiet, które selektywniej dobierają profile, osiągając wyższą efektywność pojedynczego przesunięcia.
* **Analiza lejka wiadomości (Engagement Funnel):** Część badanych użytkowników popada w tzw. "martwe dopasowania" – pary są tworzone, ale konwersacja nigdy nie rusza. Wskaźnik ten rośnie w młodszych grupach wiekowych, co wskazuje na spadek zaangażowania po początkowym sukcesie (dopasowaniu).

---

## 💡 Rekomendacje biznesowe i produktowe

* **Optymalizacja subskrypcji Premium:** Dla grupy *Low Usage Users* warto wdrożyć spersonalizowane, tańsze pakiety mikrosubskrypcji (np. dostęp na weekend), aby aktywować ich potencjał zakupowy. Z kolei dla *Power Users* należy promować pakiety zwiększające widoczność profilu (*Boost*).
* **Wprowadzenie funkcji "Icebreaker":** Aby zapobiegać "martwym dopasowaniom", aplikacja powinna automatycznie sugerować spersonalizowane pytania na start na podstawie wspólnych zainteresowań użytkowników, co podniesie wskaźnik rozpoczętych konwersacji.
* **Algorytmiczne wsparcie zaangażowania:** Rekomenduje się czasowe ograniczanie widoczności profili, które masowo przesuwają wszystkich użytkowników w prawo bez selekcji, na rzecz promowania profili dbających o wysoką jakość interakcji.

---

## 📂 Zawartość repozytorium
* `Tinder_Data_Analysis.xlsx` - Pełny plik Excel zawierający model danych, tabele przestawne oraz gotowy dashboard.
* `images/` - Folder z plikami graficznymi (interaktywny GIF prezentujący działanie projektu).

---
*Projekt został przygotowany w celach demonstracyjnych jako kluczowy element portfolio młodszego analityka danych (Junior Data Analyst).*
