# PwSJ_laboratorium11 (9)


Utwórz na dysku katalog o nazwie ‘aplikacjaflask’. W tym katalogu utwórz plik o
nazwie `app.py`.
Przejrzyj materiał wykładowy.
Zadanie 1. Stwórz szablon aplikacji Flask, umieszczając poniższy kod w pliku
app.py
from flask import Flask
app = Flask(__name__)
@app.route("/")
def main():
 return "Pierwsza aplikacja Flask!"
if __name__ == "__main__":
 app.run()
Następnie w wierszu poleceń Anaconda zmień ścieżkę na katalpg w którym
znajduje się `app.py`. Uruchom serwer poleceniem `python app.py`.
Zadanie 2. Do projektu z zadania 1 dodaj szablon index.html. Szablon może
być zwykłym plikiem .html. W celu osiągnięcia efektu wizualnego zastosuj w
szablonie Bootstrap’a.
Zadanie 3. Do projektu z zadania 2 dodaj szablon ‘omnie.html’. Przerób ten
szablon (‘omnie1.html’) tak, aby możliwe było przekazywanie wartości
łańcuchowych przez URL (jak w przykładzie z wykładu).
