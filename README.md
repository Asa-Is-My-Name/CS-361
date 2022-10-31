# CS-361 Microservice Implementation README
A. To request data from the microservice, write "popup" into a txt file called receive.txt while having the microservice running in the background.

Example Call while microservice is running: 
```
  with open('receive.txt', 'w') as f:
    f.write("popup")
```
B. To recieve data from the microservice, have a txt file called send.txt that the microservice will send data through. Once it receive a request, it will write the appropriate data into send.txt while clearing the data it recieved from recieve.txt

[UML Diagram for Microservice](MicroserviceUML.png)
