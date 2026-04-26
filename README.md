# Opis projektu

Projekt ma na celu zbudowanie podstawowego projektu uczenia maszynowego przewidującego zgłoszenie roszczenia komunikacyjnego przez klienta firmy ubezpieczeniowej. W projekcie zawarte jest czyszczenie danych, analiza danych, trenowanie modelu oraz jego interpretacja.
Dane pochodzą z następującego źródła: https://www.kaggle.com/datasets/sagnik1511/car-insurance-data

# Etapy zawarte w projekcie:
1. Import i czyszczenie danych - usunięcie brakujących danych oraz zbędnych kolumn
2. Zamiana zmiennych tesktowych na zmienne numeryczne, przygotowywując model do działania
3. Stworzenie nowych zmiennych które dzielą liczbę złamań prawa przez lata spędzone za kółkiem
4. Analiza danych - stworzenie macierzy korelacji, wygenerowanie wykresów pomiędzy zgłaszanymi roszczeniami, a niektórymi zmiennymi. Stworzenie grupy ryzyka, która najczęściej powoduje roszczenia komunikacyjne
5. Modelowanie - Podział danych na zbiór treningowy i testowy oraz wytrenowanie modelu. Utworzenie macierzy pomyłki, która ocenia jak dobrze się sprawił model
6. Wnioskowanie - Przedstawienie wniosków na podstawie analizy danych i modelowania

# Wnioski:
1. Model poprawnie identyfikuje klientów bez zgłoszonych szkód w 88% i tych z zgłoszonymi szkodami w 69%
2. Najważniejsze 3 czynniki wpływające na dokładność modelu to: doświadczenie kierowcy, czy jest właścicielem auta oraz wiek auta. Pokrywa się to z wcześniej przeprowadzoną analizą.
3. Ocenianie ryzyka na podstawie wcześniejszych naruszeń przepisów nie jest skuteczne. Jest to potwierdzenie wniosku, który został wysunięty na etapie analizy danych tego zbioru

# Technologie zawarte w projekcie: 
Python (Pandas, Scikit-learn)
