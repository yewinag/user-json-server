# user-json-server
test json response

# nodejs 
install nodejs >10 version

# json-server
npm install -g json-server

# start json-sever
json-server --watch db.json
  #### in your projects directory


# GET route
### http://localhost:3000/users

# POST route
#### http://localhost:3000/users
```{
        "id": "22",
        "stdInfo": {
            "stdName": "Mirwaise",
            "stdAge": "23",
            "stdGender": "Male",
            "stdNo": "12345",
            "stdAddress": {
                "stdStreet": "786 Street",
                "stdCity": "Riyadh",
                "stdCountry": "Saudi Arabia",
                "stdPostal": "98765"
            }
        },
        "stdEdu": {
            "stdDept": "Computer Science",
            "stdSemester": "8",
            "stdMajor": "Web Programming"
        }
 }
 ```
# DELETE route
 ### http://localhost:3000/users/${id}

# UPDATE route
 #### http://localhost:3000/users/${id}
 ```{
        "id": ${id},
        "stdInfo": {
            "stdName": "abcdefg",
            "stdAge": "23",
            "stdGender": "Male",
            "stdNo": "12345",
            "stdAddress": {
                "stdStreet": "786 Street",
                "stdCity": "Riyadh",
                "stdCountry": "Saudi Arabia",
                "stdPostal": "98765"
            }
        },
        "stdEdu": {
            "stdDept": "Computer Science",
            "stdSemester": "8",
            "stdMajor": "Web Programming"
        }
 }
 ```


 