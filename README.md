# Rozpoznawanie czynności na podstawie danych z akcelerometru i żyroskopu

Pełna dokumentacja projektu znajduje się w pliku 'dokumentacja.ipynb'.

## Uruchomienie programu

W celu przeprowadzenia testów należy pobrać plik 'AI - template.ipnb' oraz 'XGB_classifier.model' i umieścić je w tym samym folderze co plik 'test_data.csv'. <br>
Następnie otworzyć plik 'AI - template.ipynb' przy pomocy Jupyter Notebook i uruchomić po kolei komórki kodu. <br><br>


## Opis problemu

Wśród grupy ochotników przeprowadzono badanie. Każdy z uczestników miał przez jakiś czas przyczepiony do pasa smartfon, który mierzył ich aktywność za pomocą akcelerometru
i żyroskopu. Dane są etykietowane czynnością jaką uczestnicy wykonywali. (plik data.csv). <br>
Waszym zadaniem jest stworzenie klasyfikatora w dowolnym języku programowania i
dowolnej technologii, który będzie rozpoznawał jaka w tym momencie wykonywana jest
czynność. Wasz model musi być możliwie jak najprostszy i jak najbardziej dokładny. Musi
także swoją formą umożliwiać automatyczne jego sprawdzenie na zbiorze danych, który
posiada tylko jury.

<br>

## Analiza danych

Po dogłębnej analizie naszego datasetu o wymiarach (11086, 572) doszliśmy do następujących wniosków:
- dataset jest zbalansowany 
![Output occurences piechart](/piechart.png) 
- występują dane, które są ze sobą wysoko skorelowane



### Parametry wejściowe:


### Output:
Przewidziana czynność spośród: LAYING, SITTING, STANDING, WALKING, WALKING_DOWNSTAIRS, WALKING_UPSTAIRS.
<br>
<br>

### Methods used:
1.	Logistic regression
2.	XGBoost
3.	Random Forest

### Indexes użyte do oceny naszych metod:
- Accuracy (liczba poprawnych przeidywań podzielona przez liczbę wszystkich przewidywań)
- F1 Score

<br>

# Autorzy:

Jacek Bleja <br>
Michał Wnuczyński <br>
Marcin Malinowski <br>
Dominik Jakubowski<br>
