Calculator.java - 134 loc
LICENSE - 17 loc
Start.java - 19 loc
Total: 170 loc
LOC je izračunat ne uključujući prazne linije i uključujući komentare

statička analiza

Calculator.java - line 1 - fajl nije stavljen u imenovani package, to otežava organizaciju
Calculator.java - line 4 - nije definisan privatni konstruktor i zato je omogućeno kreiranje još objekata iako to nije potrebno
Calculator.java - line 18 - treba preimenovati metodu "ToString" da ju se ne bi pomiješalo sa metodom toString iz superclass java.lang.Object
Calculator.java - line 24 - ime metode "Run" ne prati standardna pravila imenovanja u javi. treba koristiti camelCase i validne karaktere
Calculator.java - line 37 - treba preimenovati metodu ”ToString”
Calculator.java - line 63 - varijabla ”exc” se ne koristi u tom bloku koda i nije ju potrbno pisati ovdje
Calculator.java - line 70 - izraz ”Float.toString(finalResult);” se može vratiti i bez ”textResult” varijable
Calculator.java - line 74 - treba preimenovati metodu ”Calculator” da prati standardna pravila imenovanja u javi
Calculator.java - line 183 - ”return;” je suvišan jer metoda svakako završava
Start.java - line 1 - fajl nije stavljen u imenovani package
Start.java - line 5 - parametar ”args” je neiskorišten u main metodi
Start.java - line 6 - treba preimenovati varijablu "Expression" da prati standardna pravila imenovanja u javi
Start.java - line 8 - bolje je koristiti logger umjesto ”System.out” zbog lakšeg održavanja
Start.java - line 19 - logger povećava fleksibilnost outputa za razliku od ”System.out”
