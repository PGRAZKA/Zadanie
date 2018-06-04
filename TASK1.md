**Scenariusz dotyczy** | Formularz rejestracyjny
------------ | -------------
**Cel testu** | Sprawdzenie prawidłowego działania formularza
**Sposób dostępu** |
**Kroki w  scenariuszu** | odpowiedź systemu
wpisz adres mailowy do którego masz dostęp
wpisz hasło  w pole password
wpisz identyczne hasło
wpisz dowolny nick w polu Last Name
naciśnij register |System powinien wyświetlić informację o poprawnej rejestracji
Sprawdź adres podany wcześniej e-mail | Przyszedł maila potwierdzający rejestrację

**Scenariusz dotyczy** | Formularz rejestracyjny
------------ | -------------
**Cel testu** | Sprawdzenie prawidłowego komunikowania o błędnym adresie e-mail
**Sposób dostępu** |
**Kroki w  scenariuszu** | odpowiedź systemu
Wpisz adres mailowy bez znaku @ | powinna pojawić się informacja o błędnym adresie e-mail

**Scenariusz dotyczy** | Formularz rejestracyjny
------------ | -------------
**Cel testu** | Sprawdzenie prawidłowego działania fkomunikatu o wprowadzeniu różnych haseł
**Sposób dostępu** |
**Kroki w  scenariuszu** | odpowiedź systemu
wpisz hasło w pole password
wpisz hasło różne od poprzedniego | powinien wyświetlić się komunikat o różnych hasłach

**Scenariusz dotyczy** | Formularz rejestracyjny
------------ | -------------
**Cel testu** | Sprawdzenie prawidłowego działania komunikatu o wprowadzeniu zbyt krótkiego hasła
**Sposób dostępu** |
**Kroki w  scenariuszu** | odpowiedź systemu
wpisz 1 literę hasło w pole password | powinien wyświetlić się komunikat o zbyt krótkim haśle

**Scenariusz dotyczy** | Formularz rejestracyjny
------------ | -------------
**Cel testu** | Sprawdzenie prawidłowego działania komunikatu o wprowadzeniu zajęj już nazwy
**Sposób dostępu** | Istnienie już nicku o tej samej nazwie w systemie
wpisz nick który już został wcześniej zarejestrowany w polu Last Name | powinien wyświetlić się komunikat, że nick jest zajęty
