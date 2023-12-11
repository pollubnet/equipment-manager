# equipment-manager

Testowy projekt do zabawy z Blazorem, wersja oryginalna na spotkaniu Grupy .NET
11 grudnia 2023.

Składa się z dwóch części: aplikacji Blazor WASM do prezentowania przedmiotów i
przenoszenia ich pomiędzy listą dostępnych i listą aktualnie "założonych"
przedmiotów (maksymalnie 6 slotów); oraz biblioteki klas z projektu
[item-generator](https://github.com/pollubnet/item-generator), zawierającej typy
takie jak przedmiot czy jego statystyki.

W zakładce [Issues](https://github.com/pollubnet/equipment-manager/issues) jest
lista zadań do poprawy w tym projekcie.

## Uruchomienie projektu

Projekt wykorzystuje API z projektu
[item-generator](https://github.com/pollubnet/item-generator), który to musi być
uruchomiony wcześniej, aby ten mógł z niego skorzystać. W pliku
`Pages/Home.razor` jest na sztywno ustawiony adres serwera z którym aplikacja
się komunikuje.
