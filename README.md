### 1. Korak
Pokrenuti json server:
```sh
$ json-server --watch db.json
```
### 2. Korak
import postman collectiona:
- otvoriti postman
 - gore desno (pored narancastog gumba) odabrati import
 - odabrati datoteku iz ovog repoa - ```json-server.postman_collection.json```
 
### 3. Korak
Testirati HTTP metode
 - GET - ```/users``` -> dohvat svih usera
 - GET - ```/users/1``` -> dhovat usera sa ```ID = 1```
 - DELETE - ```/users/1``` -> brisanje usera sa ```ID = 1 ```
 - POST - ```/users``` -> dodavanje usera (pogledati headers i body zahtjeva)
 - PUT - ```/users/1``` -> uređivanje (edit) usera sa ```ID = 1``` (pogledati headers i body zahtjeva)

### 4. Zadaci
 - koje su razlike između ```PUT``` i ```POST``` metoda?
 - što je tijelo HTTP zahteva a što zaglavlje i opisati - za svaku HTTP metodu - za što se koristi jedno a za što drugo.
 - proučiti koje još HTTP metode postoje
 - prouciti glavne skupine HTTP status code-ova : ```2XX```; ```3XX```; ```4XX```; ```5XX```

### 5. Primjedbe
Želiš li raditi sa sa webom bilo da je to integrirano ili ovako dva odvojena projekta (frontend i backend), ovo moras dobro znati. Ako bilo što nije jasno pitaj - makar i dva puta.
