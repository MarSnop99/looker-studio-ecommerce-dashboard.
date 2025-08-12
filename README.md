Global E-commerce Operations: Command Center Dashboard
 Spis Treści
Opis Projektu
Link do Interaktywnego Dashboardu
Użyte Narzędzia i Technologie
Kluczowe Funkcjonalności i Zaimplementowane Techniki
Podgląd Dashboardu
Opis Projektu
Celem tego projektu było stworzenie w pełni funkcjonalnego i interaktywnego dashboardu analitycznego w Looker Studio, który służy jako centrum dowodzenia dla fikcyjnej firmy e-commerce "Superstore". Dashboard umożliwia menedżerom monitorowanie kluczowych wskaźników wydajności (KPI), analizę rentowności w różnych wymiarach, śledzenie trendów w czasie oraz dogłębną eksplorację danych produktowych i geograficznych.

Projekt ten demonstruje umiejętność przekształcania surowych danych w strategiczne wnioski biznesowe oraz biegłość w zaawansowanych funkcjach narzędzi Business Intelligence.

  Link do Interaktywnego Dashboardu
>> Kliknij tutaj, aby otworzyć interaktywny dashboard <<(https://lookerstudio.google.com/reporting/b1e17185-51cc-4528-b00e-b5c9806a6e21)

(Uwaga: Dashboard jest w pełni interaktywny. Zachęcam do korzystania z filtrów, klikania na mapę oraz drążenia danych w tabelach.)

  Użyte Narzędzia i Technologie
Wizualizacja i Analityka: Looker Studio
Źródło Danych: Google Sheets (zasilone z publicznego zbioru danych Superstore)
Logika Biznesowa: Zaawansowane formuły i funkcje w Looker Studio (SQL-like)
   Kluczowe Funkcjonalności i Zaimplementowane Techniki
Projekt ten nie jest tylko prostą wizualizacją. Zaimplementowałem w nim szereg zaawansowanych technik, aby stworzyć prawdziwe narzędzie analityczne:

Przygotowanie i Modelowanie Danych:

Transformacja i czyszczenie danych na poziomie źródła (Google Sheets).
Tworzenie pól obliczeniowych łączących wymiary w celu jednoznacznej identyfikacji geograficznej (CONCAT).
Konwersja typów danych w celu umożliwienia analizy szeregów czasowych (PARSE_DATE).
Zaawansowana Logika Biznesowa:

Analiza "What-If" z użyciem Parametrów: Stworzenie dynamicznego celu rentowności, który pozwala na symulację różnych scenariuszy biznesowych.
Instrukcje Warunkowe CASE: Implementacja złożonej logiki kategoryzującej wyniki finansowe na podstawie dynamicznie zdefiniowanego celu.
Wyrażenia Regularne RegEx: Użycie REGEXP_EXTRACT do parsowania i kategoryzacji danych tekstowych (np. wyodrębnienie roku z ID zamówienia).
Interaktywność i UX Dashboardu:

Cross-Filtering: Mapa działa jako intuicyjny, wizualny filtr dla całego raportu, umożliwiając natychmiastową analizę geograficzną.
Drążenie Danych (Drill-Down): Tabela przestawna pozwala na eksplorację danych produktowych na wielu poziomach hierarchii (od kategorii do podkategorii).
Formatowanie Warunkowe: Zastosowanie dynamicznych skal kolorów w celu wizualnego wyróżnienia kluczowych informacji i ułatwienia ich interpretacji.
Złożone Wizualizacje:

Wykres Kombinowany (Combo Chart): Wizualizacja metryk o różnych skalach (sprzedaż i rentowność) na jednej osi czasu z wykorzystaniem dwóch osi Y.
Tabela Przestawna (Pivot Table): Prezentacja danych w wielowymiarowej macierzy (produkty vs. segmenty klientów).
🖼️ Podgląd Dashboardu

<img width="1083" height="816" alt="image" src="https://github.com/user-attachments/assets/f5c6237d-5cee-4bd7-959b-8eae237c792a" />
