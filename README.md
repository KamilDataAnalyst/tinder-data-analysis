# 📊 Tinder User Behavior & Engagement Dashboard

Kompleksowy projekt analityczny typu End-to-End, skupiający się na procesie ETL, zaawansowanej analizie danych oraz wizualizacji zachowań użytkowników aplikacji Tinder. Projekt został zrealizowany w programie Microsoft Excel z wykorzystaniem Power Query, a jego celem było przekształcenie surowych danych historycznych w interaktywny dashboard menedżerski (Executive Dashboard) wspierający decyzje biznesowe.

## 🚀 Demo projektu (Interaktywny Dashboard)

<img width="800" height="322" alt="Image" src="https://github.com/user-attachments/assets/cd8638c0-5bee-410d-8287-afd47251aae2" />

*Powyższy GIF prezentuje interaktywne działanie fragmentatorów (slicers) oraz dynamiczną reakcję wykresów na filtrowanie danych w czasie rzeczywistym.*

---

## 🎯 Cel projektu
Głównym wyzwaniem było uporządkowanie i zanalizowanie anonimowej, reprezentatywnej próbki danych historycznych dotyczących aktywności użytkowników (profilowanie, historia przesunięć w lewo/prawo, liczba dopasowań i wiadomości). Projekt miał za zadanie odpowiedzieć na kluczowe pytania biznesowe:
1. Jakie są różnice w zachowaniach i efektywności korzystania z aplikacji w zależności od płci i wieku?
2. Gdzie występują wąskie gardła w procesie konwersji (Swipe -> Match -> Chat)?
3. Jak segmentować użytkowników, aby zoptymalizować przychody z usług Premium?

## 📂 Źródło danych (Data Source)
Analiza została przeprowadzona na otwartym zbiorze danych (dataset), z którego czerpałem inspirację podczas tworzenia modelu:
* **Kaggle Dataset:** https://www.kaggle.com/datasets/ashleyxu98/tinder
* *Uwaga: Analiza opiera się na wyodrębnionej, anonimowej próbce badawczej danych demograficznych i behawioralnych, a nie na globalnej, pełnej bazie platformy Tinder.*

---

## 🛠️ Architektura i użyte technologie
* **Power Query (ETL):** Pobranie surowego pliku danych, czyszczenie (zamiana kropek na przecinki), transformacja typów danych, stworzenie spójnego modelu relacyjnego.
* **Tabele i Wykresy Przestawne (Pivot Tables & Charts):** Agregacja danych i wyliczenie zaawansowanych miar (np. współczynników konwersji).
* **Fragmentatory (Slicers):** Stworzenie intuicyjnego, interaktywnego panelu nawigacyjnego do szybkiej filtracji (płeć, grupy wiekowe, status aktywności).

---

## 📈 Kluczowe wnioski (Data Insights)

* **Rozkład segmentów użytkowników (Segment Distribution):** Analiza wykazuje, że największa część użytkowników wpada w segment *High Usage* – stanowi on aż 59% populacji mężczyzn i 67% populacji kobiet w badanej próbce. Kobiety wyraźnie dominują nad mężczyznami w najwyższych grupach zaangażowania (*High* oraz *Power User*), osiągając w nich łącznie wynik 81% (vs 68% u mężczyzn).
* **Efektywność dopasowań (Match Efficiency):** Kobiety wykazują drastycznie wyższą skuteczność w zdobywaniu dopasowań. Mimo że wykonują wykładniczo mniej przesunięć w prawo (*Swipe Right / LIKE* – średnio 2 682 vs aż 20 405 u mężczyzn), to generują znacznie wyższą średnią liczbę dopasowań (*Matches* – średnio 990 u kobiet vs 619 u mężczyzn).
* **Dynamika wiadomości (Texting Dynamics):** Mężczyźni wysyłają średnio więcej wiadomości, niż otrzymują (2 182 wysłane vs 1 957 odebranych). U kobiet trend jest odwrotny – otrzymują one znacząco więcej komunikatów, niż same wysyłają (3 252 odebrane vs 2 584 wysłane).

---

## 💡 Rekomendacje biznesowe i produktowe

* **Monetyzacja segmentu High i Power:** Ponieważ połączone segmenty *High Usage* i *Power User* stanowią zdecydowaną większość bazy użytkowników (szczególnie u kobiet – 81%), aplikacja powinna rozwijać funkcje Premium dedykowane dla osób spędzających w aplikacji najwięcej czasu (np. zaawansowane filtry wyszukiwania czy status priorytetowego polubienia).
* **Wsparcie zaangażowania mężczyzn:** Z powodu dysproporcji w liczbie *Likes* do realnych dopasowań u mężczyzn (ponad 20 tysięcy przesunięć na jedyne 619 par), warto wdrożyć funkcje pomagające optymalizować profile męskie (np. inteligentny asystent wyboru najlepszego zdjęcia profilowego), co przełoży się na lepsze doświadczenia z użytkowania aplikacji.
* **Aktywacja segmentu Low Usage:** Użytkownicy z segmentu *Low Usage* logują się do aplikacji rzadko i mają bardzo mało konwersacji (średnio 23 u mężczyzn i 51 u kobiet). Należy wdrożyć dla nich automatyczne powiadomienia PUSH w momentach najwyższego ruchu w aplikacji, aby zachęcić ich do powrotu i częstszego wchodzenia w interakcje.

---

## 📂 Zawartość repozytorium
* 📊 **[Tinder Analysis.xlsx](Tinder%20Analysis.xlsx)** - Pełny plik Excel zawierający model danych, tabele przestawne oraz gotowy, interaktywny dashboard.
* 🎞️ **[Tinder summary dashboard.gif](Tinder%20summary%20dashboard.gif)** - Plik graficzny prezentujący dynamiczne działanie projektu i fragmentatorów.

---
*Projekt został przygotowany w celach demonstracyjnych jako kluczowy element portfolio młodszego analityka danych (Junior Data Analyst).*
