# Algorytmy

Algorytm Kruskala :

•	algorytm wyznaczający minimalne drzewo rozpinające. Algorytm ten wykorzystuje strategię zachłanną, zawsze zwraca rozwiązanie optymalne.
Algorytm Kruskala kod:
Zaczynamy od lasu rozpinającego, złożonego z n drzew (jego koszt wynosi zero, jest więc najmniejszy z możliwych). W każdym następnym kroku alorytmu zmniejszamy liczbę drzew przez dołączenie nowej krawędzi o minimalnym koszcie, łączącej dwa (różne) drzewa aktualnie istniejącego lasu rozpinającego.


Algorytm Prima:

•	Algorytm Prima pozwala znaleźć w grafie nieskierowanym minimalne drzewo rozpinające. Każda z krawędzi musi mieć określoną wagę. To na podstawie tych wartości algorytm będzie dopasowywał je do drzewa. Punktem początkowym może być dowolny wierzchołek grafu. Innymi słowy minimalne drzewo rozpinające uzyskane na końcu zawsze będzie takie samo dla tego samego grafu


działanie:
Dla każdego wierzchołka określamy, że jego koszt wynosi nieskończoność, a poprzednik jest nieokreślony. Wybranemu wierzchołkowi przypisujemy wartość 0, a następnie tworzymy kolejkę wierzchołków do rozpatrzenia. W kolejce dane są posortowane po koszcie elementu. Następnie, dopóki kolejka nie jest pusta, wybieramy wierzchołek o najniższym koszcie i aktualizujemy jego sąsiadów, którzy występują w kolejce. Jeśli krawędź z wybranego wierzchołka z kolejki do sąsiada ma niższą wartość niż sąsiad ma koszt to aktualizujemy informacje
