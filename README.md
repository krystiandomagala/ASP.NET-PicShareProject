# ASP.NET-PicShareProject
Projekt zaliczeniowy z programowania aplikacji w ASP.NET.
PicShare to aplikacja do udostępniania zdjęć. 
Zaimplementowano funkcje kont użytkowników (zwykłych jak i administratora)
Konta administratora posiadają prawo do usuwania wszystkich zdjęć, natomiast konto zwykłego użytkownika ma prawo jedynie do usuwania udostępnionych z tego konta zdjęć.
Użytkownik może zmienić swoje hasło lub pobrać plik json z danymi osobistymi, które zbiera aplikacja.
W sekcji "My Pictures" użytkownik może dodać plik z obrazem oraz wybrać kategorie do której ma być przyporządkowany na stronie. Ma również podgląd udostępnionych przez siebie zdjęć z opcją ich usunięcia.
Sekcja "Categories" zawiera kategorie obrazów.
Sekcja "All photos" zazwiera wszystkie obrazy udostępnione w aplikacji przez wszystkich użytkowników.

Do uruchomienia aplikacji i należy zmienić connectionString
    "PicShareDbContextConnection": "Server=<serwersql>;Database=MVCAuthDB;Trusted_Connection=True;MultipleActiveResultSets=true"
  
  i dokonać migracji 
  1. add-migration <nazwa>
  2. update-database
