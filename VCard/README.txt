Wywołanie:
localhost:8080/
localhost:8080/search?name
localhost:8080/download/{fullName}

Opis:
Po uruchomieniu servera i wywołaniu localhost:8080/ zostanie wyświetlone okienko do wpisania szukanego ciągu znaków z imienia bądź nazwiska pracownika PŁ. 
"Search" wygeneruje listę znalezionych pracowników. 
"Wygeneruj VCard" przy wybranym pracowniku spowoduje rozpoczęcie pobierania pliku vcf o nazwie wybranego pracownika.


METODA			ŻADANIE						ODPOWIEDŹ
GET				/							Wyświetla stronę z formularzem i przyciskiem SEARCH
GET				/search?name				Wyświetla listę pracowników PŁ podanych w parametrze name
GET				/download/{fullName}		Generuje VCard pracownika dla imienia i nazwiska podanego jako parametr
