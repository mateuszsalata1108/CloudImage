# CloudImages

Projekt zaliczeniowy z przedmiotu "Przetwarzanie danych w chmurze obliczeniowej"

Autor: Mateusz Sałata

## Opis aplikacji

Aplikacja CloudImages pozwala użytkownikom na przechowywanie zdjęć w chmurze oraz wyświetlanie ich. 
Aby uzyskać dostęp do głównych funkcjonalności aplikacji należy zalogować lub zarejestrować się.

## Aplikacja

Po uruchomieniu aplikacji ukazuje się ekran rejestracji z możliwością założenia konta lub przejścia do ekranu logowania

![Rejestracja](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/Rejestracja.png)

Wymagany jest poprawny format maila

![Walidacja](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/RejestracjaWalidacja.png)

Po pomyślnej rejestracji przechodzi się na ekran logowania

![Logowanie](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/Logowanie.png)

Po zalogowaniu użytkownik przechodzi do widoku dodawania zdjęcia.
Progress bar pojawiający się po kliknięciu "Prześlij" informuje użytkownika o trwającym procesie przesyłania.

![Dodawanie](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/AddPhoto.png)

Po wybraniu zdjęcia z galerii, użytkownik może przesłać zdjęcie. 

![Przesyłanie](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/AddedPhoto.png)

Następnie, wszystkie zdjęcia można wyświetlić po kliknięciu przycisku "Pokaż zdjęcia"

![Galeria](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/ShowAll.png)

## Baza

Linki do zdjęć znajdują się w bazie

![Linki](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/RealtimeDatabase.png)

Same zdjęcia, natomiast, w Storage

![Pliki](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/Storage.png)

## Kod

Rejestracja - przypisanie pól, ustawienie funkcji przycisków oraz funkcja tworzenia użytkownika

![Rejestracja](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/RegisterActivity1.png)

![Rejestracja2](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/RegisterActivity2.png)

Logowanie - analogicznie do rejestracji

![Logowanie](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/Logowanie1.png)

Model 

![Model](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/Model.png)

Adapter służący do pobierania zdjęć z bazy w celu wyświetlenia ich w postaci listy. Wykorzystuje bibliotekę Glide.

![Adapter](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/Adapter.png)

Widok dodawania plików

![Dodawanie](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/Main.png)

Funkcje przesyłające plik do bazy

![Prześlij](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/MainDodawanie.png)

![Prześlij2](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/FunkcjaDodaj%C4%85ca.png)

![Uri](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/Uri.png)

Widok wszystkich przesłanych zdjęć

![Galeria](https://github.com/mateuszsalata1108/CloudImages/blob/main/Screenshots/GetAll.png)




