POSTMAN: 

1. Send message: POST
http://localhost:9091/produce/message
{
    "studentId": "051",
    "name": "Kaibil51",
    "rollNumber": "051"
}


2. Consume message: GET
http://localhost:9091/consume/message