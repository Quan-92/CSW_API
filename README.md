GET (GET ALL) https://api-csw.herokuapp.com/api/employee/list

GET (FIND BY ID) https://api-csw.herokuapp.com/api/employee/1

POST (save) https://api-csw.herokuapp.com/api/employee/save
#### Body:
```json
  {
      "name": "Nguyen Van A",
      "salary": 1000000
   }
```

POST (update) https://api-csw.herokuapp.com/api/employee/update/1
#### Body:
```json
  {
      "name": "Nguyen Van A",
      "salary": 1000000
   }
```
POST (delete) https://api-csw.herokuapp.com/api/employee/delete/1
# CSW_API
