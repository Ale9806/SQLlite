# SQLlite TUTORIAL

#### Create A New Table
```sql
CREATE TABLE Users(
 name VARCHAR(128),
 email VARCHAR(128)
 )
```
#### ADD record
```sql
INSER INTO Users(name,email) VALUES ('alejandro','ale@gmail.com')
```

#### Delete a record
```sql
DELETE FROM Users Where email='ale@gmail.com'
```

#### UPDATE a record
```sql
UPDATE Users  SET name='Charles' Where email='pmd@gmail.com'
```
#### Retrieving Records: Select
The selet statement retrieves a group of records - you can either retrieve all the record or
a subset of the records with a WHRE caluse
###### WIthout WHERE CLAUSE
```sql
SELECT * FROM Users
```
###### WIth WHERE CLAUSE
```sql
SELECT * FROM Users WHERE email='pmd@gmail.com'
```
#### SORT RECORDS
```sql
SELECT * FROM Users ORDER by name
```
### COUNT RECORDS
```sql
SELECT COUNT(*) FROM Users
```

