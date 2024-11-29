# Tipi di dato
## Repo
**Name**: `gen-jaita138-tipi-di-dato-1`
## Todo
Definire in file di testo o pdf o excel gli attributi con relativi tipi di dato per le seguenti realta'
### Database 1
**Gestione di una Biblioteca**:
- Libri
- Membri
- Prestiti

### Database 2
**Catalogo di un Ristorante**:
- Piatti
- Ingredienti
- Clienti

### Database 3
**Catalogo di un Negozio di Fiori**
- Fiori
- Fornitori
- Clienti




	- Database 1


|        | Sql     | Java   |
| ------ | ------- | ------ |
| libri  | id      | class  |
| autore | varchar | string |
| titolo | varchar | string |
| pagine | int     | int    |

|             | Sql     | Java   |
| ----------- | ------- | ------ |
| membri      | id      | class  |
| nome        | varchar | string |
| cognome     | varchar | string |
| email       | varchar | string |
| cod.fiscale | varchar | string |


|          | Sql      | Java      |
| -------- | -------- | --------- |
| prestiti | Id       | class     |
| nome     | varchar  | string    |
| cognome  | varchar  | string    |
| orario   | datetime | localdate |


	- Database 2


|             | Sql     | Java   |
| ----------- | ------- | ------ |
| piatti      | id      | class  |
| nome        | varchar | string |
| descrizione | varchar | string |
| prezzo      | float   | float  |

|             | Sql     | Java   |
| ----------- | ------- | ------ |
| ingredienti | id      | class  |
| nome        | varchar | string |

|          | Sql     | Java   |
| -------- | ------- | ------ |
| clienti  | id      | class  |
| nome     | varchar | string |
| cognome  | varchar | string |
| telefono | varchar | string |
| citta    | varchar | string |
| cap      | varchar | string |


	- Database 3


|           | Sql     | Java   |
| --------- | ------- | ------ |
| fiori     | id      | class  |
| tipologia | varchar | string |
| colore    | varchar | string |
| nome      | varchar | string |

|             | Sql     | Java   |
| ----------- | ------- | ------ |
| fornitori   | id      | class  |
| nome        | varchar | string |
| cod.fiscale | varchar | string |
| iban        | varchar | string |
| citta       | varchar | string |

|         | Sql     | Java   |
| ------- | ------- | ------ |
| clienti | id      | class  |
| nome    | varchar | string |
| cognome | varchar | string |
| ordine  | varchar | string |
