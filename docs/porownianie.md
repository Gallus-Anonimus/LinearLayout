# Porównanie LinearLayout i ConstraintLayout
## Liczba linii
- app/src/main/res/layout/activity_main.xml - 68 linii.
- app/src/main/res/layout/activity_main_constraint.xml - 104 linii.

Liczbę linii sprawdziłem po zapisaniu obu plików, licząc wszystkie wiersze kodu, również puste.

## Który układ był szybszy do napisania i dlaczego?

Szybszy do napisania był LinearLayout, ponieważ elementy umieszcza się kolejno, jeden pod drugim. Nie trzeba ustawiać ograniczeń dla każdego widoku. W ConstraintLayout trzeba określić powiązania między elementami i rodzicem.

## Który układ łatwiej zmienić, gdy dodamy nowe pole w środku formularza?

W tym formularzu łatwiejszy do modyfikacji jest LinearLayout. Wystarczy wstawić nową etykietę i pole w odpowiednim miejscu kodu, a kolejne elementy automatycznie przesuną się w dół.

W ConstraintLayout trzeba dodatkowo sprawdzić i zmienić ograniczenia elementów znajdujących się poniżej nowego pola. Zaletą ConstraintLayout jest natomiast większa swoboda rozmieszczania elementów w bardziej złożonych interfejsach.