# Meetings notes

## Meeting 1.
* **DATE: 2019-02-13, 14:00**
* **ASSISTANTS: Mika Oja**
* **GRADE:** *To be filled by course staff*

### Minutes

General discussion about the current state of the project.
During the meeting we went through the requirements of the first deadline and checked that the project was advancing properly. One key-point was to clarify more the API-use in machine point of view (in automation, etc.). Although the subject was discussed in preliminary planning, the subject was not originally included in the documentation.

There was also discussion about the quality of resources used in this project: required scale and unimportance of business logic. The aim of the course is not business logic, but API and hypermedia implementation. The conclusion was that the project's current state is very good.

### Action points
The action points of the meeting were the following:
* Current state of the project
* Relevance of the RESTful technology/architecture
* Quality, scalability and size of the resources
* Importance of business logic
* How to mark code as your own
* The most important points of the project
* Django and Django REST Framework implementation
* API-use from machine point of view

### Comments from staff
*ONLY USED BY COURSE STAFF: Additional comments from the course staff*

## Meeting 2.
* **DATE: 2019-02-28, 14:30**
* **ASSISTANTS: Mika Oja**
* **GRADE:** *To be filled by course staff*

### Minutes
General discussion about the current state of the project.
The implementation of main resources was discussed and the removal of some resources, with emphasize on the interesting resources. The relationships of the resources were discussed. Marshmallow was suggested if the project group wanted to automate the project more. Hypermedia tests will be in portion 4 of the project. Portion 3 has large amount of documentation.
Criticism offered by the course supervisor: The current url architecture is flat, urls should be nested more with hierarchy. Hypermedia type still open in project. Advised to check examples, for example mason html.
Second critique: all methods are get, if machine client searches controls, controls should define methods. Schema needs to be defined if post is used. This is for deadline 3
API design discussed and serialisation needs to be finetuned.

Discussion about the client, not big difference if using hypermedia client, autogenerated client is not enough, when making client some specific operation might be good. API does not need to do everything. This is after third deadline.

Overall deadline 2 good.

### Action points
* Reread excercise 2
* Expand URL tree
* Finetune serialiser
* Plan hypermedia and client

### Comments from staff
*ONLY USED BY COURSE STAFF: Additional comments from the course staff*

## Meeting 3.
* **DATE: 2019-03-28, 15:30**
* **ASSISTANTS: Mika Oja**
* **GRADE:** *To be filled by course staff*

### Minutes
General discussion about the current state of the project.
Discussion about the use of PATCH request in the project, not necessary and can cause problems in the long run. Requires more knowledge and work to get to work. If motivated then can come up with usage for PATCH request. For example to be used for category moviedetail with many-to-many relationship to a few other resources. There are already many resources however.
Discussion about the hierarchy of the urls and categories. Would be good to see what movies are in a category, could be done with for example links to movies. Comments should have authors.

Use standards as much as possible when doing the project. Recommendation: Remove patch. Discussion about the format of the client. Deadline 3 is fine.

### Action points
* Plan client
* Trim resources
* Plan hypermedia

### Comments from staff
*ONLY USED BY COURSE STAFF: Additional comments from the course staff*

## Meeting 4.
* **DATE: 2019-05-02, 12:30**
* **ASSISTANTS: Mika Oja**
* **GRADE:** *To be filled by course staff*

### Minutes
Very quick glance at the state of the project. It was brought up that some sort of
coverage report for tests is required (using pytest, for example). Also every resource
requires tests of every possible scenario. Other than lack of all the possible test
scenarios the project was in a good state.

### Action points
* Create coverage report
* Create more test cases for every resource

### Comments from staff
*ONLY USED BY COURSE STAFF: Additional comments from the course staff*

## Final meeting
* **DATE: 16.05.2019**
* **ASSISTANTS: Mika Oja**
* **GRADE:** *To be filled by course staff*

### Minutes

Koko pisteytys:
1. Related workissä on ohjeistustekstiä 4 puuttuu, sovelluksia, konkreettiset esimerkit
2. Melkein täydet pisteet, kommentit
3. Error viesteissä kaikki paitsi 400 bad request, hal, meidän apin kannalta stateless ei toteudu/ ei ole määritelty, periaatteessa stateful koska user säilyy serverside, create actor list ei pitäisi tulla statesta, autentikaatio header tai json, apikey taulukosta pitäisi voida lukea, jos machine client ei tallenna cookie, hyvin kuitenkin pisteistä 2 kommentit koodissa
4. Serializerissa docstring, koodin kommentointi puutteellista 2 ei ole kuvattu dokumentit
5. Client

Kannattaa tehdä client jos haluaa nostaa arvosanan kolmesta neljään

### Action points
* Possible client

### Comments from staff
*ONLY USED BY COURSE STAFF: Additional comments from the course staff*
