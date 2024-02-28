COLONE|TIPO|ATTRIBUTI|
---|---|---
id| NOTNULL | PRIMARY_KEY AUTO_INCREMENT
marca| varchar | NOTNULL
km| small | NOTNULL
anno| year | NOTNULL
modello| varchar | NOTNULL
fuel| char(2) | NOtNULL
cambio| char(1) | NOTNULL
colore| varchar | NULL
ruote| table | NULL
modifiche| table | NULL
targa | char(7) | NOTNULL
ultima manutenzione | date | NOTNULL
usura | char(2) | NOTNULL
Numero portiere | DECIMAL | NOTNULL
Motore | table | NOTNULL