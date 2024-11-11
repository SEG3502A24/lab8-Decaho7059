# Nom : Gbegbe Decaho
# Stud Num : 300094197
# employeeGql

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TCK6WrAb)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17028155&assignment_repo_type=AssignmentRepo)


# Review execution
https://github.com/SEG3502A24/lab8-Decaho7059.git

####################################################################

http://localhost:4200

http://localhost:9000/graphiql

http://localhost:9000/graphiql?path=/graphql

#########################################################
execution
activation de MongoDB sur le docker 

>> ng serve pour le client
>> ./gradlew bootRun pour le server


####################################################
Ajout des 2 mutations de test

mutation {
  newBook(
    createBookInput : {
    bookNumber: 1020, 
    category : "kids",
    title : "Tales of times",
    cost : 100,
    year : "2010",
    description : "Great read for Kids"}){
    bookId
  }   
}

_____________________________________________________

mutation {
  newAuthor(
    createAuthorInput: {
      bookNumber: 1020,
      firstName : "Xala",
      lastName : "Zandra"}){
    firstName
  }
}
